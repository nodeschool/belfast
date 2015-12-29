#Getting Started
This is a short guide intended to get attendees up and running with [node](http://nodejs.org), [npm](https://www.npmjs.com/)
and [nodeschool workshops](http://nodeschool.io/#workshopper-list).

## Install Node.js
Using a version manager such as [nvm](https://github.com/creationix/nvm) is the simplest way to get node installed as
this offers many advantages. Windows users can use [nvm-windows](https://github.com/coreybutler/nvm-windows)

- [NVM](#nvm)
- [NVM-Windows](#nvmwindows)

### <a name="nvm"></a>NVM
A prerequisite is to have GIT installed before continuing.

```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.30.1/install.sh | bash
```

Add the following to your profile `~/.bashrc`, `~/.profile`, or `~/.zshrc`
```
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh" # This loads nvm
```

Now you need to source your profile eg:
```
source ~/.profile
```
or close and reopen your terminal.

Note: full installation instructions for nvm can be found at: https://github.com/creationix/nvm

### <a name="nvmwindows"></a>NVM-Windows
From the [nvm-windows GitHub](https://github.com/coreybutler/nvm-windows) download the installer for the
[latest release](https://github.com/coreybutler/nvm-windows/releases/download/1.1.0/nvm-setup.zip) and install it. At the
time of writing this guide,`v1.1.0` is the latest. Run the installer, then open a terminal and type `nvm` to verify the program is on your path.


### Installing Node
With nvm or nvm-windows installed you can go ahead and install the latest version of node.js

#### OSX and Linux
```
nvm ls-remote
```

This will show a list of available versions of node you can install. At the time of writing this, it was v5.5.0. To install
this we will type:

```
nvm install v5.3.0
```

#### Windows
```
nvm install latest
```
###
This will install `node` and `npm` executables onto your PATH. You can verify these have been installed with:

```
node -v
v5.3.0
```

```
npm -v
3.3.12
```

If you see the above output you're ready for the next section where we'll install our first workshop.

You can also download the latest version of Node for Windows from [Download Node for Windows](https://nodejs.org/en/download/)

## Installing a Workshop
Node school has lots of [workshops](http://nodeschool.io/#workshopper-list) with new workshops being published regularly
however they all use npm for easy installation. In this example we will install `learnyounode, one of the first workshops
and a great starting place.

```
npm install -g learnyounode
```

The `-g` globally installs the module placing `learnyounode` on your path so from the terminal type `learnyounode` to
start the workshop.
