---
id: basic-structure
title: Basic SPA Boilerplate Structure
sidebar_label: Structure
---

The structure ir generated by this command
`tree -l 5 -a  --ignore 'node_modules,/, .git/,  .temp/, dist/, client/, reports/ website/, .DS_Store'`

```
├── .gitignore
├── .gulpenvrc
├── .scripts-lint.yml
├── .stylelintrc
├── .travis.yml
├── LICENSE
├── README.md
├── app
|  ├── assets
|  |  ├── fonts
|  |  |  └── OpenSans
|  |  |     ├── OpenSans-Bold.ttf
|  |  |     ├── OpenSans-ExtraBold.ttf
|  |  |     ├── OpenSans-Italic.ttf
|  |  |     ├── OpenSans-Light.ttf
|  |  |     ├── OpenSans-Regular.ttf
|  |  |     └── OpenSans-Semibold.ttf
|  |  └── images
|  |     └── example.jpg
|  ├── index.html
|  ├── scripts
|  |  ├── app.js
|  |  └── vendor.js
|  └── styles
|     ├── app.scss
|     ├── base
|     |  ├── _fonts.scss
|     |  ├── _globals.scss
|     |  ├── _icons.scss
|     |  ├── _states.scss
|     |  ├── _utilities.scss
|     |  ├── _variables.scss
|     |  └── mixins
|     |     ├── _fonts.scss
|     |     ├── _icomoon.scss
|     |     └── _medias.scss
|     ├── components
|     |  └── _ck-site.scss
|     └── vendor
|        └── _normalize.scss
├── gulpfile.js
├── package-lock.json
├── package.json
├── tasks
|  ├── assets.js
|  ├── clean.js
|  ├── config
|  |  ├── helpers.js
|  |  └── options.js
|  ├── copy.js
|  ├── plugins
|  |  ├── commons.js
|  |  ├── globals.js
|  |  └── uglify.js
|  ├── rules
|  |  ├── scripts-lint.js
|  |  └── scripts.js
|  ├── serve.js
|  ├── styles-lint.js
|  ├── styles.js
|  └── watch.js
├── tasks.config.json
└── webpack.config.js
```