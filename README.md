# react-library-starter

Small set of starter files to bootstrap your react library development process. Uses rollup

To get started:
```bash
git clone https://github.com/mDibyo/react-library-starter [your-library-name]
cd your-library-name

# Remove this repository and initialize your own repository
rm -rf .git
git init

yarn # or `npm install`
```

Now, you can start editing `src/index.js`. To build:
```bash
yarn build # or `npm build`
```

To publish,
Edit `package.json` and then,
```bash
yarn publish # or `npm publish`
```
As part of the publishing process, the build script will be run.
