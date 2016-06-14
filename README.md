# Send Grid Plugin #

## Description ##

This plugin sends emails through SendGrid using their API.

## Installation ##

### Dependencies ###

This plugin is for phplist 3 and requires php version 5.4 or later.

It also requires the php curl extension to be installed.

### Set the plugin directory ###
The default plugin directory is `plugins` within the admin directory.

You can use a directory outside of the web root by changing the definition of `PLUGIN_ROOTDIR` in config.php.
The benefit of this is that plugins will not be affected when you upgrade phplist.

### Install through phplist ###
The recommended way to install is through the Plugins page (menu Config > Manage Plugins) using the package
URL `https://github.com/bramley/phplist-plugin-sendgrid/archive/master.zip`.
The installation should create

* the file SendGridPlugin.php
* the directory SendGridPlugin

### Install manually ###
If the automatic installation does not work then you can install manually.
Download the plugin zip file from <https://github.com/bramley/phplist-plugin-sendgrid/archive/master.zip>

Expand the zip file, then copy the contents of the plugins directory to your phplist plugins directory.
This should contain

* the file SendGridPlugin.php
* the directory SendGridPlugin

##Usage##

For guidance on using the plugin see the plugin's page within the phplist documentation site <https://resources.phplist.com/plugin/sendgrid>

## Changes required to phplist files ##

phplist does not currently support using a plugin to send emails,
therefore one phplist file needs to be modified in order to use the plugin.
The necessary code change is described on the plugin's documentation page.

## Support ##

Please raise any questions or problems in the user forum <https://discuss.phplist.org/>.

## Donation ##

This plugin is free but if you install and find it useful then a donation to support further development is greatly appreciated.

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=W5GLX53WDM7T4)

## Version history ##

    version     Description
    1.0.0+20160615  Initial release