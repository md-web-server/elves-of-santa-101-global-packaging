Elves of santa 101, global packaging.

This repository is purposely kept simple as a hello world template to enable others to allow other elves to join team North-Pole and publish global packages.

This is one way to create a global package, in the future this repo will suport other global install implementations. If they exist.

The current implementation was sourced from: https://ourcodeworld.com/articles/read/393/how-to-create-a-global-module-for-node-js-properly

This program is helpful for an experiment that I am working on for my screensaver application:
https://www.npmjs.com/package/aerial_desktop

## Usage:
// Anything in < > field means enter your specific information

```bash
git clone --depth=1 https://github.com/michaeldimmitt/elves-of-santa-101-global-packaging.git <your-project-name>
cd <your-project-name>
npm login
npm publish

cd ~
npm install -g <your-project-name>
```
