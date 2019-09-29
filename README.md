## Google Translate Min Permissions
### Introduction
 
Minimal permissions version. This extension creates a context menu item in the browser, when you click on a menu item, the current page url, link or the previously selected text is sent to Google Translate. You can also setup default language in the option page.

### How to use
#### Changing the default language
First you should change the default language settings by accessing to about:addons > To Google Translate option page.

#### Translating text
Select any text in some web page and then right click with your mouse

![Firefox Google Translate Screenshot](https://addons.cdn.mozilla.net/user-media/previews/full/225/225342.png)

![Firefox Google Translate Add-On](https://addons.cdn.mozilla.net/user-media/previews/full/225/225338.png)

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