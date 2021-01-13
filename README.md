# load-web-page-jsdom-mocha
<img src=https://dnajs.org/graphics/dnajs-logo.png align=right width=160 alt=logo>

_Minimal example of loading a web page into jsdom and testing with Mocha_

[![Build](https://travis-ci.com/dnajs/load-web-page-jsdom-mocha.svg)](https://travis-ci.com/dnajs/load-web-page-jsdom-mocha)

### Instructions
Execute `spec-runner.sh.command` or enter the terminal commands:
```shell
$ git clone https://github.com/dnajs/load-web-page-jsdom-mocha
$ cd load-web-page-jsdom-mocha
$ npm install
$ npm test  #runs "mocha spec.js"
```

For development testing, set the `url` variable in **spec.js** to your local web server, such as:
`http://localhost:8080`

<img src=https://raw.githubusercontent.com/dnajs/load-web-page-jsdom-mocha/master/screenshot.png
   width=400 alt=screenshot>

### Comparison
For a Puppeteer version, check out:<br>
[load-web-page-puppeteer-mocha](https://github.com/dnajs/load-web-page-puppeteer-mocha)

---
[dnajs.org](https://dnajs.org) | [MIT License](LICENSE.txt)
