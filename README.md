# joomla-gulp-release
============
Gulp release builder for Standard Joomla Components, Modules, Plugins and Libraries.

### Install
#### To install all the dependencies,

```
sudo npm install --save-dev gulp
```

#### After installing `gulp` now you need to install `joomla-gulp-release`

```
sudo npm install --save-dev joomla-gulp-release
```

### Using Gulp build system
#### Following tasks and switches are available:

Use this command to release component.
Version and other information can be set in `gulp-config.json` file.

    gulp release:component

This command is to release the extensions.

    gulp release:extensions


This command will read the base directory and create zip files for each of the folder.

#### === Switches ===
Pass an argument to choose different folder

    --folder {source direcory}  Default: "./plugins"

Pass an argument to change suffix for extension

    --suffix {text of suffix}   Default: "plg_"

#### Example Usage:

	gulp release:extensions --folder ./modules --suffix ext_


#### Help
Gulp Default task is set to show you help.

```
gulp
```
