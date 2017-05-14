## Baseado em SB Admin v2.0 rewritten in AngularJS

[![Join the chat at https://gitter.im/start-angular/sb-admin-angular](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/start-angular/sb-admin-angular?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This project is a port of the famous Free Admin Bootstrap Theme [SB Admin v2.0](http://startbootstrap.com/template-overviews/sb-admin-2/) to Angular Theme.

Find out more [Free Angular Themes at StartAngular.com](http://www.startangular.com/).

## Instalação
####1. Clone projeto em um diretório local:
git clone  https://github.com/Gabrielvitoria/inventario.git

####2. Certifique que tenha instalado os componentes:
NodeJs
[bower](http://bower.io/), 
[grunt-cli](https://www.npmjs.com/package/grunt-cli) 
[npm](https://www.npmjs.org/) installed globally
 
 
Via Node execute os seguintes comandos:
$ npm apt-get install npm
$ npm npm install -g grunt-cli
$ npm npm install -g bower
```
####3. Os proximos comandos deverão ser executados dentro do riretório que foi baixado

$ cd `project-directory`
```
- bower install is ran from the postinstall
```sh
$ npm install 
```
- a shortcut for `grunt serve`
```sh
$ npm start
```
- a shortcut for `grunt serve:dist` to minify the files for deployment
```sh
$ npm run dist 
```

**Note:**
If you get this following error, 
```text
Error: EACCES, permission denied '.config/configstore/insight-bower.yml'
You don't have access to this file.
```
changing ownner .config

```sh
sudo chown -R [user name] ~/.config
```


## Roadmap

- Add sample AJAX calls and make the directives more modular

### Automation tools
- [Grunt](http://gruntjs.com/)
