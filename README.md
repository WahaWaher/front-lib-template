# Frontend Library Template
Simplify and speed up the process of creating frontend libraries, plugins, etc..

# Get started
#### 1. Clone
```bash
git clone https://github.com/WahaWaher/front-lib-template library-name
cd library-name
```

#### 2. Install
```bash
yarn
```

#### 3. Be sure to fill/edit package.json (fields: name, varsion, description, lib, etc.)
#### 4. Run once "prepare" script
```bash
yarn prepare # will replace strings, rename some files and clear some dirs
```
#### 5. Dev, Build, Publish!
```bash
yarn dev # run development server (by default url: http://localhost:3000, dir: './dev')
yarn build # make production build (by default dir: './build')
yarn publish # pulish npm package
```