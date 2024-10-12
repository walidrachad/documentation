# documentation for cocoapods instalation
Install Xcode Command Line Tools if you haven’t already:
xcode-select --install

Install Homebrew if you don’t have it:
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

Install the latest Ruby version using Homebrew (this will also install required dependencies):
brew install ruby

Add the newly installed Ruby to your PATH by adding the following line to your ~/.zshrc or ~/.bash_profile file:
export PATH="/usr/local/opt/ruby/bin:$PATH"
Afterward, restart your terminal or run source ~/.zshrc or source ~/.bash_profile.

Install Cocoapods:
brew install cocoapods
Link Cocoapods:
brew link --overwrite cocoapods 
brew link --overwrite cocoapods --dry-run

pod --version 
