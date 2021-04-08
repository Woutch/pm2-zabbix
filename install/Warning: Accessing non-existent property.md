To remove the warnings:
Warning: Accessing non-existent property 'cat' of module exports inside circular dependency

Edit the file bellow

pm2-zabbix/node_modules/shelljs/src/common.js
455 line
// if (shell[name] && !wrapOptions.overWrite) {
// throw new Error('unable to overwrite ' + name + ' command');
// }
