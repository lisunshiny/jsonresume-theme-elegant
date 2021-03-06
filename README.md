# Elegant Theme [![npm version](https://badge.fury.io/js/jsonresume-theme-elegant.svg)](http://badge.fury.io/js/jsonresume-theme-elegant)

Responsive theme for [JsonResume](https://jsonresume.org/) inspired by card layouts.

[Theme Preview](http://themes.jsonresume.org/elegant)

### Supported Social Profiles
* angellist
* behance
* bitbucket
* codepen
* dribbble
* dribble
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

### Credits
* [Ryan B. Harvey](https://github.com/nihonjinrxs), [Chris Vogt](https://github.com/chrisvogt), [ThomWright](https://github.com/ThomWright), [JamesonNetworks](https://github.com/JamesonNetworks), [Elaniobro](https://github.com/Elaniobro) & [Rui](https://github.com/rpbaltazar) for their pull requests
* Floating Menu: inspired by [Smart Fixed Navigation](http://codyhouse.co/demo/smart-fixed-navigation/index.html)

### Contributing
```
$ git clone https://github.com/mudassir0909/jsonresume-theme-elegant.git
$ cd jsonresume-theme-elegant
$ npm install
$ grunt watch // watches for less file changes
$ grunt exec:run_server // Do this in a new terminal tab to run node server
```

Visit [http://localhost:8888](http://localhost:8888) to see the theme in action.

##### Testing JSON changes
You can test your changes by updating `resume.json` file inside `node_modules/resume-schema/` folder. You might want to rerun `grunt exec:run_server` whenever you make any changes to `resume.json`

##### Updating Styles
All the LESS files are organized under the folder `assets/less/`. Please go through the comments inside `theme.less` to find out which file to put your LESS changes. Grunt compiles `assets/less/theme.less` to `assets/css/theme.css` which is used eventually in the theme.

**_Please Do not make any changes inside `assets/css/theme.css`_**

##### Updating Javascript
All the javascript changes go into `index.js` which is responsible for rendering the theme.

### Roadmap

[https://github.com/mudassir0909/jsonresume-theme-elegant/labels/enhancement](https://github.com/mudassir0909/jsonresume-theme-elegant/labels/enhancement)
