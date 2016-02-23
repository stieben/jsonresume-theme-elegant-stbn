# JSON Resume theme: Elegant (stbn fork)

Responsive theme for [JSON Resume](https://jsonresume.org/), inspired by card layouts.

[Theme Preview](http://themes.jsonresume.org/theme/elegant)

## Social profiles

The profiles are shown in the order in which they are specified in the `basics.profiles` array.
By default, only 5 profiles are shown & others are revealed on demand.

![Profile Section](https://raw.githubusercontent.com/mudassir0909/jsonresume-theme-elegant/master/screenshots/profile.png)

### Supported profiles

* angellist
* behance
* bitbucket
* codepen
* dribbble
* dribble
* exercism
* facebook
* foursquare
* instagram
* github
* googleplus
* gratipay
* hackernews
* lastfm
* linkedin
* pinterest
* reddit
* skype
* soundcloud
* spotify
* stackexchange
* stackoverflow
* tumblr
* twitter
* vimeo
* youtube

## Credits

* Original theme by [Mudassir](https://github.com/mudassir0909/jsonresume-theme-elegant).
* Thanks to all the [contributors](https://github.com/stieben/jsonresume-theme-elegant-stbn/graphs/contributors)!
* Floating menu inspired by [Smart Fixed Navigation](http://codyhouse.co/demo/smart-fixed-navigation/index.html).

## Contributing

```
$ git clone https://github.com/stieben/jsonresume-theme-elegant-stbn.git
$ cd jsonresume-theme-elegant-stbn
$ npm install
$ grunt watch // watches for Less file changes
$ grunt exec:run_server // do this in a new terminal tab to run node server
```

Visit [http://localhost:8888](http://localhost:8888) to see the theme in action.

### Testing JSON changes

You can test your changes by updating the `resume.json` file inside the `node_modules/resume-schema/` folder.
You might want to rerun `grunt exec:run_server` whenever you make any changes to `resume.json`.

### Updating styles

All the Less files are organized under the folder `assets/less/`.
Please go through the comments inside `theme.less` to find out into which file to put your Less changes.
Grunt compiles `assets/less/theme.less` to `assets/css/theme.css` which is used eventually in the theme.

**Please do not make any changes inside of `assets/css/theme.css`** – they will be overridden.

### Updating JavaScript

All the JavaScript changes go into `index.js` which is responsible for rendering the theme.

## Roadmap

[See upstream](https://github.com/mudassir0909/jsonresume-theme-elegant/labels/enhancement).
