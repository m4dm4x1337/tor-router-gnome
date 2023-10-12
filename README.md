# Tor-Router Gnome

## Description

**Tor-Router Gnome** is an app indicator for the GNOME desktop that allows you to quickly enable and disable system-wide TOR routing.

## Installation

Download the Debian package and run this commands:

```bash
sudo dpkg -i tor-router-gnome_1.0_all.deb || sudo apt-get -f install
```

The `tor-router-gnome` package depends on the `tor-router` package which should be installed first.

## Usage

You can find the shortcut to start the program in the Applications menu under the Internet menu item.


## Configuration

No configuration is required, although you can personalize Tor-Router Gnome using environment variables. You can find out more about this in the manual:

```bash
man tor-router-gnome
```

## Alternative graphical user interface (GUI)

There are **two** graphical user interfaces!

The first is this app indicator for the GNOME desktop that allows you to easily start/stop Tor-Router.

The second is a web GUI that can display a lot of additional information and enable remote management and monitoring of Tor-Router.

## Internationalization (i18n)

Tor-Router and its GUIs are able to use language files to display text in the user's language. So far, the only additional language other than English is German. If you want to create another language file, download the German .po file (which also contains the English translations), and replace all the "msgstr" entries (there aren't too many). Then send me a pull request or simply post the file to the issue tracker (if you don't know how to git).

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

## License

This project is licensed under the GPLv3 License. See the COPYING file for details.

## Author

The Tor-Router Debian package was created by m4dm4x1337.

## Donations 🥺

 ❤️ Please donate ❤️

![QR code for donations](about:blank)

This project is open source, and the only income comes from the donators. If you like the project, please donate, thank you!

[bitcoin:bc1q9ha0l0tt7dghcpgext8jppejandefeshcukpxx](bitcoin:bc1q9ha0l0tt7dghcpgext8jppejandefeshcukpxx)
