# Redmine Custom CSS plugin

Allows to input CSS directly from Redmine to customize Redmine appearance.\
Edit the CSS in the plugin's configuration page. Path to configuration is /settings/plugin/redmine_custom_css

Please note that there is nothing for now to prevent an admin injecting HTML in the page!

## Features

* Allows to input CSS to customize Redmine's theme
* Hey, that's all for now!

## Compatibility

Redmine 2.x ~ 4.x stable

Tested on:
* 4.2.x (Rails 6.1)
* 3.4.x (this and prior - branch Redmine_3x)
* 3.3.x
* 3.0.3
* 2.5.0
* 2.4.2

## Roadmap


## Downloading and installing the plugin

Download the plugin using git. Open a terminal in your Redmine installation's "plugins" directory and type:

>$ git clone https://github.com/martin-denizet/redmine_custom_css.git

If you use Rails prior 6.1 switch to the branch Redmine_3x.

>$ git fetch\
>$ git checkout Redmine_3x

The installation is now finished and you will be able to use the plugin after you restart your Redmine instance.

No need to migrate the database!

## Usage

After installing, navigate to plugin configuration (/settings/plugin/redmine_custom_css) and start inputing CSS.

## Credits

Thank to CodeMirror for their very cool editor licensed under MIT license! http://codemirror.net/

## Contributors

* Eduard Kuleshov : Coding

Previous contibutors:
* @martin-denizet : Coding
* @onlyjob : Licensing expertise
* @virtualmarc : Bugfix
* @Daiben : Testing

## License TL;DR

GPLv3+\
Copyright (C) 2021 Eduard Kuleshov <eduard.kuleshov@gmail.com>\
Copyright (C) 2018 Martin DENIZET <martin.denizet@supinfo.com>

## License

redmine_custom_css - "redmine_custom_css" is Redmine plugin to add custom CSS
editable through web interface\
Copyright (C) 2021 Eduard Kuleshov <eduard.kuleshov@gmail.com>\
Copyright (C) 2018 Martin DENIZET <martin.denizet@supinfo.com>

This file is part of redmine_custom_css.

redmine_custom_css is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

redmine_custom_css is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with redmine_custom_css.  If not, see <http://www.gnu.org/licenses/>.

