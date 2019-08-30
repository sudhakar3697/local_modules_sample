# local_modules_sample
Sample showing the usage of local modules with npm

https://nodesource.com/blog/avoiding-common-challenges-node-js

### Initial folder structure
local_modules_sample
<ul>
    <li>
    local_modules
             <ul>
             <li>
             sysinfo
             <ul>
                 <li>index.js</li>
                 <li>package.json</li>
             </ul>
             </li>
            </ul>
    </li>
    <li>index.js</li>
    <li>package.json</li>
 </ul>
 
  ### After npm install
  local_modules_sample
<ul>
    <li>
    local_modules
             <ul>
             <li>
             sysinfo
             <ul>
                 <li>index.js</li>
                 <li>package.json</li>
             </ul>
             </li>
            </ul>
    </li>
     <li>
    node_modules
             <ul>
             <li>
             sysinfo (link to local_modules/sysinfo is created)
             <ul>
                 <li>index.js</li>
                 <li>package.json</li>
             </ul>
             </li>
            </ul>
    </li>
    <li>index.js</li>
    <li>package-lock.json</li>
    <li>package.json</li>
 </ul>
