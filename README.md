# local_modules_sample
Sample showing the usage of local modules with npm

https://nodesource.com/blog/avoiding-common-challenges-node-js

### Initial folder structure
<pre>
->local_modules_sample
    ->local_modules
        ->sysinfo
            index.js
            package.json
    index.js
    package.json
 </pre>   
  ### After npm install
  <pre>
  ->local_modules_sample
    ->local_modules
        ->sysinfo
            index.js
            package.json
    ->node_modules
        ->sysinfo (link to local_modules/sysinfo is created)
            index.js
            package.json
    index.js
    package-lock.json
    package.json
    </pre>
