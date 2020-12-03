# node-version-change

<p>NVM Install Current Project</p>

`[[ -s $HOME/.nvm/nvm.sh ]] && . $HOME/.nvm/nvm.sh  # This loads NVM`

<p>Start Old Project</p>

````
nvm i 11.15.0
rm -rf node_modules
rm -rf package-lock.json
npm cache clean
npm install
