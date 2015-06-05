# Plugin Directory Boilerplate

A quick simple boilerplate for the directory structure needed for using the WordPress Plugin Directory.

## Contents

The Plugin Directory Boilerplate includes the following files:

* `.gitignore`. Used to exclude certain files from the repository.
* `CHANGELOG.md`. The list of changes to the core project.
* `README.md`. The file that you’re currently reading.
* A `plugin-name` subdirectory that contains the Assets folder with the image sizes needed to display on WordPress.org and a trunk folder for your plugin code.
* A `trunk` folder for the contents of your plugin folder and the GPL v2 included.
* Inside the trunk folder is a sample `README.txt` file you can edit so that the directory information is pulled from it correctly. 

## License

The Plugin Directory Boilerplate is licensed under the GPL v2 or later.

> This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License, version 2, as published by the Free Software Foundation.

> This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

> You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301 USA

## Important Notes

### Licensing

The trunk directory includes the GPL v2; however, if you opt to use third-party code that is not compatible with v2, then you may need to switch to using code that is GPL v3 compatible.

For reference, [here's a discussion](http://make.wordpress.org/themes/2013/03/04/licensing-note-apache-and-gpl/) that covers the Apache 2.0.

### Assets

The `assets` directory contains three files.

1. `banner-772x250.png` is used to represent the plugin’s header image.
2. `icon-256x256.png` is a used to represent the plugin’s icon image (which is new as of WordPress 4.0).
3. `screenshot-1.png` is used to represent a single screenshot of the plugin that corresponds to the “Screenshots” heading in your plugin `README.txt`.

The WordPress Plugin Repository directory structure contains three directories:

1. `assets`
2. `branches`
3. `trunk`

The Boilerplate offers support for `assets` and `trunk` as `branches` is something that isn’t often used and, when it is, is done so under advanced circumstances.

When committing code to the WordPress Plugin Repository, all of the banner, icon, and screenshot should be placed in the `assets` directory of the Repository, and the core code should be placed in the `trunk` directory.


# Credits

The Plugin Directory Boilerplate is an offshoot of the WordPress Plugin Boilerplate by Tom McFarlin. After being passed on to Devin Vinson in 2015 this was pulled out as a separate repo.

After being unsure what to name this, the always helpful Ryan McCue assisted in the final naming (because names are important okay!).
