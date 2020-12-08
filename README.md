# node-version-change

<p>NVM Install Current Project</p>

`[[ -s $HOME/.nvm/nvm.sh ]] && . $HOME/.nvm/nvm.sh  # This loads NVM`

<p>Mac</p>

```
nvm i 11.15.0
rm -rf node_modules
rm -rf package-lock.json
npm cache clean
npm install
```

<p>Windows</p>

```
nvm i 11.15.0
nvm use 11.15.0
rm -r node_modules
rm -r package-lock.json
npm cache clean / npm cache clean --force
npm install
```
