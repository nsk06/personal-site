## [nsk06.github.io/personal-site](https://nsk06.github.io/personal-site/)

My personal website. Easily modifiable, and built using modern javascript with Node.js, React, Express, React-Router, Hot Module Reloading, Webpack and many other technologies.

### Dependencies:
Tested with:
* node >= v8, v9, v10, v11
* Recommend [nvm](https://github.com/creationix/nvm#installation) for managing node versions
* Recommend [yarn](https://yarnpkg.com/lang/en/docs/install/#mac-stable) >= 1.0.0


### Set up:

You may wish to fork this repository or remove my remote origin and add your own. Go [here](https://help.github.com/articles/changing-a-remote-s-url/) for more information on changing remotes.  

1. To download the repository and install dependencies, run the following commands:
```bash
git clone git://github.com/mldangelo/personal-site.git
cd personal-site
yarn
```
If you do not have `yarn` installed, you may run `npm install` instead.

2. Next, you should create a `.env` file. To do this, run:
```bash
cp sample.env .env
```
and set values as appropriate. Most people will not need to make changes.

3. Run the following command to build the react application and serve it with hot module reloading:
```bash
npm run dev
```
Navigate to `<ip>:<port>` default: [http://localhost:7999](http://localhost:7999) to view my website.

This completes set up instructions. Please continue reading to learn how to modify this site to make it your own.

### Contributors
- [Nonidh Singh](https://github.com/nsk06)

### Acknowlegements
- Special thanks to [michael](https://github.com/mldangelo) for inspiration.
