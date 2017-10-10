<p align="center">
  <img src="https://user-images.githubusercontent.com/3791941/31036931-072760fe-a534-11e7-8cd7-0565bdc2727c.png" width="100" height="60">

  <h3 align="center">Electron: Start to Finish<br></h3>
</p>

# electron-codepen

**Clone and run for a quick way to see Electron in action.**

This is a minimal Electron application based on the [Quick Start Guide](http://electron.atom.io/docs/tutorial/quick-start) within the Electron documentation.

**Use this app along with the [Electron API Demos](http://electron.atom.io/#get-started) app for API code examples to help you get started.**

A basic Electron application needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.

You can learn more about each of these components within the [Quick Start Guide](http://electron.atom.io/docs/tutorial/quick-start).

## Prerequisites

- [Install Git](#install-git)
- [Get familiar with Git commands](#get-familiar-with-git-commands)
- [Install a text editor](#install-a-text-editor)
- [Install Node.js](#install-nodejs)

#### Install Git

##### macOS
Mac users, while you probably already have _a_ version of Git on your system, it may be out-of-date. You can [download an updated installer package here](https://git-scm.com/download/mac).


Advanced users might consider installing the latest stable version of Git with [Homebrew](https://brew.sh), e.g.: 
  ```sh
  brew install git
  ```

##### Windows
[Git for Windows](https://git-for-windows.github.io/) provides both Git and a Bash emulation environment to use Git on the command line.

##### Linux
While some Linux distributions come with a version of Git installed, it's often out-of-date. [This guide](https://git-scm.com/download/linux) has recommended commands to install Git with your distribution's preferred package manager.

##### Get familiar with Git commands
You'll want to know how to [fork](https://help.github.com/articles/fork-a-repo/) and [clone](https://help.github.com/articles/cloning-a-repository/) a Git repository, and how to [check out a branch](https://git-scm.com/docs/git-checkout#git-checkout-emgitcheckoutemltbranchgt).

If you need a refresher, consider [exploring our free on-demand training](https://services.github.com/on-demand/).

#### Install a text editor
Perhaps consider [Atom](https://atom.io/) if you're looking for an awesomely hackable text editor for the 21st century!

#### Install Node.js
> **Q:** Why do we need to install Node.js if Electron includes Node.js?
>
> **A:** While Electron does include its own internal version of Node.js, what we'll install first includes `npm`, the Node Package Manager. NPM is what powers our dependency installation and build processes.

For all platforms, visit [nodejs.org](https://nodejs.org/en/download/) to download the installer package. For our purposes today, we recommend the "LTS" package.

For advanced users: if you later want to install multiple versions of node and npm on your system you can use tools like [`nvm`](https://github.com/creationix/nvm) or [`n`](https://github.com/tj/n).

Once you've got Node.js installed you will have the `node` and `npm` commands available in your terminal. You should be able to `npm install` packages now, without using `sudo`. If you see errors when installing packages with npm, you may need to [fix your permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions).


## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/satelliteworkshops/electron-codepen
# Go into the repository
cd electron-codepen
# Install dependencies
npm install
# Run the app
npm start
```

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## Resources for Learning Electron

- [electron.atom.io/docs](http://electron.atom.io/docs) - all of Electron's documentation
- [electron.atom.io/community/#boilerplates](http://electron.atom.io/community/#boilerplates) - sample starter apps created by the community
- [electron/electron-quick-start](https://github.com/electron/electron-quick-start) - a very basic starter Electron app
- [electron/simple-samples](https://github.com/electron/simple-samples) - small applications with ideas for taking them further
- [electron/electron-api-demos](https://github.com/electron/electron-api-demos) - an Electron app that teaches you how to use Electron
- [hokein/electron-sample-apps](https://github.com/hokein/electron-sample-apps) - small demo apps for the various Electron APIs

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
