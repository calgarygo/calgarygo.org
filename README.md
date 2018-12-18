# calgarygo.org

The Calgary Go site is a static site built with the Go tool, Hugo!

## Installing

```sh
# Grab hugo
brew install hugo

# Grab the project
git clone https://github.com/calgarygo/calgarygo.org.git
cd calgarygo.org
git submodule update --init --recursive

# Build the project
hugo serve

# You should be able to visit http://localhost:1313/ and see the site rendered!
```
