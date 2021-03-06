# Historic Tale Construction Kit - Artifaces

[Check out the online demo!](http://artifaces.leschatscosmiques.net)

> Craft thy own Japanese 19th century fireworks 
> Pop colors and zwims and zamms  
> Explode 

Yokohama city's public library hall released dematerialized versions of old catalogues of firework (www.city.yokohama.lg.jp/kyoiku/library/digitalarchive/hirayama.html).
We could not resist the urge of detouring them to offer everyone the beautiful experience of Japanese fireworkks, with a little help from the team that conceived the generator of medieval Bayeux tapestries.

## Features
This brand new Historic Tale Construction Kit allows you to
* Drag, drop, scale, rotate any item from the Bayeux image bank
* Do the same with text with different fonts and colors
* Bring elements to the front/back of the scene (this **is** life changing)
* Work on several images (pages) at once
* Export those pages as PNG or as GIF
* Save a working copy of your tapestry to your disk, to finish it later
* Use brushes to quickly add crowds, birds, or battlefield
* Use keyboard shortcuts for almost all of the above
* Download a standalone version to use it anywhere without any server

### Universe
This kit is based on the [Bayeux Tapestry](http://www.bayeuxmuseum.com/en/la_tapisserie_de_bayeux_en.html), a 70-meters long piece of art telling the story of the Battle of Hastings. However, every Bayeux-related pictures, fonts and settings are stored in a single folder, that can be easily swapped with, say, Japanese Prints, Cave Painting, whatever your heart desires.

Feel free to fork this project and create your own Historic Tale Construction Kit with anything that comes to mind :)  
To do so, put your content to the ``content`` folder and index it in the [config.js](https://github.com/htck/bayeux/blob/master/htck/app/content/config.js) file.

## Technical Stuff
This kit is written mostly using RaphaelJS and AngularJS, but it also uses a bunch of really cool libraries, such as [angular-hotkeys](https://github.com/chieffancypants/angular-hotkeys), [canvg](https://github.com/gabelerner/canvg), [FileSaver.js](https://github.com/eligrey/FileSaver.js), [Raphael.FreeTransform](https://github.com/AliasIO/Raphael.FreeTransform), [Raphael.json](https://github.com/AliasIO/Raphael.JSON), [gifshot](https://github.com/yahoo/gifshot), [Canvas-to-Blob](https://github.com/blueimp/JavaScript-Canvas-to-Blob). They helped us build an app that works everywhere, client-side without the need for any back-end. Huge thanks to them.

### Vagrant
If you want to work on the _Historic Tale Construction Kit_ by yourself, you can use the vagrant box by launching ``vagrant up``. **Attention**, you will need to have admin rights if you want to run it on windows. Or set up a development environnement.

### Setting up a development environnement
If you do not want to use vagrant, you will need to install the following globally
```
sudo apt-get install nodejs
sudo npm install npm -g
sudo npm install -g bower
sudo npm install -g grunt-cli
```

------

Then either way go to the ``htck`` folder and install dependencies using
```
npm install
bower install
```
You can then run a development server using the command ``grunt serve``

## Contribute
If you experienced a bug, we're sorry! If you can fix it, we gladly accept pull requests. If you can't, you can still open an issue here on GitHub and we will try to address it shortly.

This project is [MIT-licensed](https://github.com/htck/bayeux/blob/master/LICENSE) and any open source contribution is welcome!
