# Github default Jekyll static page
Best to use this guide: https://pages.github.com/

Make a repository named `username.github.io` to get that address.

Check out themes on https://jekyllrb.com/docs/themes/

## Creating Content

* Text is rendered from markdown files
* intenral links point to separate files [anotherpage](another_page)

## DIY

To access more themes, you need to leave the github button pushing.

### MacOS
https://jekyllrb.com/docs/installation/macos/

#### One time commands for setup
```
# install brew if not already installed.
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
# install ruby and jekyll
brew install ruby
# add to path
echo 'export PATH=/opt/homebrew/opt/ruby/bin:$PATH' >> ~/.zshrc
echo 'export PATH=`gem environment gemdir`/bin:$PATH' >> ~/.zshrc
# update path
source ~/.zshrc
# install jekyll
brew install jekyll
```

#### Testing


