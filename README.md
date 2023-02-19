Build started
git clone -q --branch=master https://github.com/RomanEvd/react-thunk /home/appveyor/projects/react-thunk
git checkout -qf dd014d930d9ffea4d50463c6d3849bf6074f8f8e
Configuring 'stack'
Enabling Node 12
v12.22.12 is already installed.
Now using node v12.22.12 (npm v6.14.16)
Running "install" scripts
npm install
npm WARN read-shrinkwrap This version of npm is compatible with lockfileVersion@1, but package-lock.json was generated for lockfileVersion@2. I'll try to do my best with it!
> core-js@3.27.2 postinstall /home/appveyor/projects/react-thunk-1and2/node_modules/core-js
> node -e "try{require('./postinstall')}catch(e){}"
> core-js-pure@3.27.2 postinstall /home/appveyor/projects/react-thunk-1and2/node_modules/core-js-pure
> node -e "try{require('./postinstall')}catch(e){}"
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@2.3.2 (node_modules/fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@2.3.2: wanted {"os":"darwin","arch":"any"} (current: {"os":"linux","arch":"x64"})
added 1496 packages from 691 contributors and audited 1498 packages in 33.407s
232 packages are looking for funding
  run `npm fund` for details
found 1 high severity vulnerability
  run `npm audit fix` to fix them, or `npm audit` for details
Running "build_script" scripts
npm run build
> task@0.1.0 build /home/appveyor/projects/react-thunk-1and2
> react-scripts build 
Creating an optimized production build...
Compiled successfully.
File sizes after gzip:
  60.83 kB  build/static/js/main.17719b6f.js
  1.78 kB   build/static/js/787.a5a00b74.chunk.js
  338 B     build/static/css/main.8689ed05.css
The project was built assuming it is hosted at /react-thunk-1and2/.
You can control this with the homepage field in your package.json.
The build folder is ready to be deployed.
Find out more about deployment here:
  https://cra.link/deployment
Running "test" phase
Updating build cache...
Cache 'node_modules' - Updated
Build completed