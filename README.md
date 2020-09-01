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

#### 3. Be sure to fill/edit package.json (fields: name, version, description, lib, etc.)
#### 4. Run once "first" script
```bash
yarn first # will replace strings, rename some files and clear some dirs
```
#### 5. Dev and Build!
```bash
yarn dev # run development server (by default url: http://localhost:3000, dir: './dev')
yarn build # make production build (by default dir: './build')
```