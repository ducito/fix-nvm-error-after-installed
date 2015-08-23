## fix-nvm-error-after-installed

[https://www.npmjs.com/package/nvm](https://www.npmjs.com/package/nvm)
 
### NVM
 Used to install and managing different versions of node and installing local versions into repos.
 
### Install
 
 `npm install -g nvm`

### Setup

`export PATH=./node_modules/.bin:$PATH`

### Fix `"local" not implemented yet.` error.

`git clone git://github.com/creationix/nvm.git ~/.nvm`

`printf "\n\n# NVM\nif [ -s ~/.nvm/nvm.sh ]; then\n\tNVM_DIR=~/.nvm\n\tsource ~/.nvm/nvm.sh\nfi" >> ~/.bashrc`

`NVM_DIR=~/.nvm`

`source ~/.nvm/nvm.sh`