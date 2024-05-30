# QLocalAppInstaller
Also known as qlai (`/kʰlaɪ/`). An application for linux that installs applications into your user's home directory, and assists with creating application and command line shortcuts.

## Why?
Useful on devices like the Steam Deck where you can't install packages to root, so you can install a zip or tarball to your home directory and assist you in creating shortcuts in your application menu and CLI commands. Also useful for applications that are distributed in zip files or tarballs and have no other methods of being installed. The result is an application that functions seamlessly with the system and feels like an installed package.

## Usage
**NOT READY FOR USE LOL**
Run QLocalAppInstaller for first time use. This will initialise its directories at ~/.qlai and add itself to ~/bin
You can use QLocalAppInstaller in two ways; command-line, or by running from your application menu: qlai installer (or qlai manager to manage current installations)

### CLI
#### Installing packages
you can run the `qlai install` command to install a package, passing it the path or URL to your package.
```qlai install ~/Downloads/package.tar.gz```

This will start a wizard which will allow you to configure your application for use.

Passing a URL will allow you to check for updates as long as it's a yeah that

#### Managing packages
You can manage qlai packages by running the `qlai manage` command, followed by the registered name of your package.

##### Adding shortcuts
`qlai manage mypackage shortcut add shortcutcliname`
This will throw you into a wizard thingy that lets you set up the package stuffs yeah that. ill finish this readme when im not tired.