# Blender Add-on Manager

This is the application to manage add-on released on GitHub.
You can install/uninstall/update all add-on's released on GitHub with this application.

*This tools is on testing now. Lots of bugs may be existed in this tools, and is fixing them in order*


## Download URL

|Version|Download URL|
|---|---|
|0.3|[Download](https://github.com/nutti/Blender-Add-on-Manager/releases/tag/v0.3)|
|0.2|[Download](https://github.com/nutti/Blender-Add-on-Manager/releases/tag/v0.2)|
|0.1|[Download](https://github.com/nutti/Blender-Add-on-Manager/releases/tag/v0.1)|


## Support Languages

**English** only.


## Features

This application has features as follows.

* Search add-ons released on GitHub (about 2,000 add-ons are avaliable)
* Manage add-ons
  * Install add-on released on GitHub
  * Uninstall add-on which is already installed (only **External** support level)
  * Update add-on released on GitHub


## Tutorials

See [Wiki Page](https://github.com/nutti/Blender-Add-on-Manager-for-GitHub/wiki/Tutorial_EN)


## Related Links

Project "Blender Add-on Manager" is on going.
See the link below for further details.

* [Blender Artist Thread](https://blenderartists.org/forum/showthread.php?418833-Blender-Add-on-Manager-(About-2-000-add-ons-are-available))


## Change Log

|Version|Release Date|Change Log|
|---|---|---|
|0.3|2017.4.11|[1] Move config/DB file to user directory<br>[2] Improve server's stability<br>[3] Error popup<br>[4] Fix bug<br> - Failed to run application developed by unidentified developer on macOS<br> - Failed to load add-on at Blender installed by this application|
|0.2|2017.4.2|[1] Support macOS<br>[2] Add features<br> - Link button to Add-on repository<br> - Case-insensitive search<br>[3]Fix bug<br> - Failed to install when ```__init__.py``` is located on the top directory|
|0.1|2017.3.25|First release for testing|


## Bug Report / Feature Request

This project is on going.  
If you want to report problem or request feature, please make issue.

https://github.com/nutti/Blender-Add-on-Manager-for-GitHub/issues

## Contribution

If you want to contribute this project, please send pull request to **develop** branch.  
DO NOT send pull request to **master** branch.

https://github.com/nutti/Blender-Add-on-Manager/tree/develop

To build and run application for testing.

```sh
$ git clone https://github.com/nutti/Blender-Add-on-Manager.git
$ cd Blender-Add-on-Manager
$ npm install
$ bower install
$ gulp
$ gulp start
```

To build application for relase.

```sh
$ git clone https://github.com/nutti/Blender-Add-on-Manager.git
$ cd Blender-Add-on-Manager
$ npm install
$ bower install
$ gulp

$ npm run build     # for Windows/linux

or

$ node build_mac.js     # for macOS
```


## License

MIT License.
