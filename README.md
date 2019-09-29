## Google Translate Min Permissions
### Introduction
 
Minimal permissions version. This extension creates a context menu item in the browser, when you click on a menu item, the current page url, link or the previously selected text is sent to Google Translate. You can also setup default language in the option page.

### How to use
#### Changing the default language
![about addons Firefox Google Translate](https://addons.cdn.mozilla.net/user-media/previews/full/225/225337.png)
First you should change the default language settings by accessing to about:addons > To Google Translate option page.

#### Translating text
Select any text in some web page and then right click with your mouse

![Firefox Google Translate Screenshot](https://addons.cdn.mozilla.net/user-media/previews/full/225/225342.png)
Go to Google Translate at the bottom of your right click menu. You will see three options. Translate will only translate the selection, Listen lets you hear what the selection sounds like and Translate this page will translate the entire page.
![Google Translate in Firefox Example](https://addons.cdn.mozilla.net/user-media/previews/full/225/225341.png)

You can also click the toolbar button for a quick Google translation.
![Firefox Google Translate Add-On](https://addons.cdn.mozilla.net/user-media/previews/full/225/225338.png)

If you have not selected any text, the right click menu will show the option to translate the entire page.
![Firefox Translate Extension](https://addons.cdn.mozilla.net/user-media/previews/full/225/225340.png)

### Testing out the extension
You can test the extension in Firefox with *web-ext*. *web-ext* can be installed with the Node Package Manager.
```sh
sudo npm install --global web-ext
```
Download the code from Github
```sh
git clone https://github.com/mold-resistant/to-google-translate.git
cd to-google-translate
make prepare
```

Run in the root folder extension the command
```sh
web-ext run
```

### Contributors of new features
1. [chr314](https://github.com/chr314)
2. [piroor](https://github.com/piroor)

### Privacy guru
1. [mold-resistant](https://github.com/mold-resistant)