# Masters Touch Salon
Masters Touch Salon is a Christian owned and operated salon that has established itself as a forerunner for cutting edge style, creating some of the latest trends in the industry.

TODO: Add prod url here

## Let’s do this whole development thing
Here are some instructions to get your machine set up like a developer:

* [Xcode dev tools](http://osxdaily.com/2014/02/12/install-command-line-tools-mac-os-x/)
	* `xcode-select —-install`
* [Homebrew](https://brew.sh/)
	* `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`
*  [Oh My ZSH](https://github.com/robbyrussell/oh-my-zsh) Lets make your terminal look pretty and easier to read! (Optional) 
	* `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
* [Nvm](https://github.com/creationix/nvm)
	* `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash`
	* `nvm install 12.22.8 && nvm alias default 12.22.8`
* [Rbenv](https://github.com/rbenv/rbenv)

1. `brew update && brew upgrade ruby-build`
2. `brew install rbenv`
3. `rbenv init`
4. Close your terminal and open a new one
5. Verify that rbenv is properly set up using this [rbenv-doctor](https://github.com/rbenv/rbenv-installer/blob/main/bin/rbenv-doctor) script:
`curl -fsSL https://github.com/rbenv/rbenv-installer/raw/main/bin/rbenv-doctor | bash`
5. `rbenv install 3.1.0`
6. `rbenv global 3.1.0`
7. Close your terminal and open a new one
* [Download Visual Studio Code - Mac, Linux, Windows](https://code.visualstudio.com/Download)
	* Once installed and launched:
		1. `Cmd+Shift+P`
		2. Type: `>shell command` and install
* Generate a new [SSH key](https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
	1. `ssh-keygen -t rsa -b 4096 -C “/your_email@example.com/“`
	2. When you’re prompted to “Enter a file in which to save the key,” press Enter
	3. Then you will be asked add a secure passphrase
`> Enter passphrase (empty for no passphrase): /[Type a passphrase]/`
For more info on [SSH key passphrase](https://help.github.com/en/github/authenticating-to-github/working-with-ssh-key-passphrases) 4. Once you have generated your SSH key you need to add it to your GitHub in setting/keys


## Now let get this project running
1. `rbenv exec gem install bundler`
2. `rbenv exec bundle install`
3. `nom install`
4. `rbenv exec middleman`

Then you should see the site at localhost:4567

### Install Helpful VS Code Plugins (optional)
* [advanced-new-file](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file) Create new directories while creating a new file, and fuzzy-matching autocomplete to create new files relative to existing path.
* [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare) enables real-time collaboration. It gives the ability to share a session with someone else, allowing them to edit code as well as share a server and debugging session.
* [Setting Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync) allows settings, extensions, and keyboard shortcuts across multiple devices.
