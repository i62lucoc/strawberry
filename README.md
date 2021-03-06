# Project: Strawberry

Scripting operations related to setting up a new GNU/Linux installation.

### Why?

As a Arch Linux user, I like starting fresh once in a while, because Arch. Well, turns out installing all software I need is kind of tedious. So I'm building, with your help :), a framework that generates the **one and only** script you need to set up our freshly new install of your favorite GNU/Linux distro. 

## Features

Strawberry is a tool to create a script that helps you setting up distros. Just proceed with the install of your prefered OS, and execute the file. It will download package, set dotfiles, clone GitHub repos, edit files...

There are several modules built-in in the Strawberry framework:

* **Git:** Enter your personal info, like name or email.
* **GitHub repo cloning:** Clone where desire a GitHub repository.
* **Generate SSH key & upload it:** Generates a RSA key & upload it to GitHub for authentification.
* **Download packages:** Automatic download & install of packages from your desire package manager (apt, yum, pacman).
* **Change your default shell:** Choose your preferred shell easily.
* **Create links:** Create hard & soft link with the 'ln' command.
* **Edit files:** Add, edit or remove lines from a specific file in your system.

And so much more to come...
 
## Setting up Strawberry

### Download

Clone the repository with the clone command, or just download the zip.

```
$ git clone git@github.com:jesusrp98/strawberry.git
```

### Setup

In order to generate your final script, just fill the configuration files under the [conf](conf) folder, where all user provided information should be. Then, run the [setup.sh](setup.sh) script.

## Edit your script

There is an example provided, called [example.sh](example.sh). Also, the generated script has lots of comments explaining what does what, so editing your script after its incepcion, with a little bit of Bash knowledge shouldn't be difficoult.

## Authors

* **Ángel Heredia** - aka anthares101 - [GitHub](https://github.com/anthares101).
* **Carlos Luque** - [GitHub](https://github.com/i62lucoc).
* **Victoriano Pedrajas**
* **Miguel Ángel Ramírez**
* **Jesús Rodríguez** - aka Chechu - [GitHub](https://github.com/jesusrp98), [Twitter](https://twitter.com/jesusrp98).

## License

This project is licensed under the GNU GPL v3 License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* Arch is kinda tedious sometimes :/
* Built just for fun :)
