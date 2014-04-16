# Brocade Vyatta syntax package for Sublime Text 2

Sublime Text 2 Syntax Definitition for Vyatta router/switch/firewall configurations. This package will highlight Vyatta configuration and commands within Sublime Text 2.

## Installing

**Without Git:** Download the zip from github, and extract the files to your Sublime Text "Packages" directory, into a new directory named `Vyatta`. You can find the packages directy by going to Preferences -> Browse packages, within Sublime Text 2.

**With Git:** Clone the repository in your Sublime Text "Packages" directory:

    git clone git://github.com/suidroot/sublime-vyatta-syntax.git

## Usage
Once installed navigate to View->Syntax->Vyatta to apply the Vyatta syntax to the document.

This syntax definition will automatically be applied to .txt files and .cfg files.

## Customizing
Once Vyatta syntax is turned on you can then try different color schemes by going to Preferences -> Color Schemes.

If you wish to customize this even further for your own needs navigate to the Vyatta package (Preferences -> Browse Packages). Edit the `Vyatta Definitions.json-tmlanguage` file within Sublime Text 2. After your changes go to Tools -> Build, to rebuild the syntax definitions.

