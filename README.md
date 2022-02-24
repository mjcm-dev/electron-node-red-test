# electron-node-red

This is an Electron template to embed Node-RED with a Dashboard generated by node-red-dashboard.

You can base off this model and update the package.json file to include your own required dependencies.

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/mjcm-dev/electron-node-red-test.git
# Go into the repository
cd electron-node-red
# Install dependencies and run the app
npm install && npm start
```

## TL:DR - building runtimes

You can run `npm run build` to build binaries of "everything".

Builds are created in the `dist` directory.

## Packaging your application
```
# build for OSX 64 bits
npm run build:osx

# build for Windows 64 bits
npm run build:win64

# build for Linux 64 bits
npm run build:linux64
```

Learn more about Electron and its API in the [documentation](http://electron.atom.io/docs/latest).

Use `Node-RED` command to run. Flows are stored in `~/.node-red`.

If you build Node-RED package with community nodes, rename pakcage-pack.json to package.json.

## License [CC0 (Public Domain)](LICENSE.md)

## See also
 - **Electron Node-RED Project which this project was forked from** - https://github.com/natcl/electron-node-red & https://github.com/dceejay/electron-node-red
 - **Stand-alone Starter Project** - https://github.com/dceejay/node-red-project-starter
 - **Bluemix Starter Project** - https://github.com/dceejay/node-red-bluemix-starter
