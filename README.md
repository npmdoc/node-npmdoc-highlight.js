# api documentation for  [highlight.js (v9.10.0)](https://highlightjs.org/)  [![npm package](https://img.shields.io/npm/v/npmdoc-highlight.js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-highlight.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-highlight.js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-highlight.js)
#### Syntax highlighting with language autodetection.

[![NPM](https://nodei.co/npm/highlight.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/highlight.js)

[![apidoc](https://npmdoc.github.io/node-npmdoc-highlight.js/build/screenCapture.buildCi.browser.apidoc.html.png)](https://npmdoc.github.io/node-npmdoc-highlight.js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-highlight.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-highlight.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ivan Sagalaev"
    },
    "bugs": {
        "url": "https://github.com/isagalaev/highlight.js/issues"
    },
    "contributors": [
        {
            "name": "Ivan Sagalaev",
            "url": "original author"
        },
        {
            "name": "Jeremy Hull"
        },
        {
            "name": "Oleg Efimov"
        },
        {
            "name": "Peter Leonov"
        },
        {
            "name": "Victor Karamzin"
        },
        {
            "name": "Vsevolod Solovyov"
        },
        {
            "name": "Anton Kovalyov"
        },
        {
            "name": "Nikita Ledyaev"
        },
        {
            "name": "Konstantin Evdokimenko"
        },
        {
            "name": "Dmitri Roudakov"
        },
        {
            "name": "Yuri Ivanov"
        },
        {
            "name": "Vladimir Ermakov"
        },
        {
            "name": "Vladimir Gubarkov"
        },
        {
            "name": "Brian Beck"
        },
        {
            "name": "MajestiC"
        },
        {
            "name": "Vasily Polovnyov"
        },
        {
            "name": "Vladimir Epifanov"
        },
        {
            "name": "Alexander Makarov"
        },
        {
            "name": "Vah"
        },
        {
            "name": "Shuen-Huei Guan"
        },
        {
            "name": "Jason Diamond"
        },
        {
            "name": "Michal Gabrukiewicz"
        },
        {
            "name": "Ruslan Keba"
        },
        {
            "name": "Sergey Baranov"
        },
        {
            "name": "Zaripov Yura"
        },
        {
            "name": "Oleg Volchkov"
        },
        {
            "name": "Vasily Mikhailitchenko"
        },
        {
            "name": "Jan Berkel"
        },
        {
            "name": "Vladimir Moskva"
        },
        {
            "name": "Loren Segal"
        },
        {
            "name": "Andrew Fedorov"
        },
        {
            "name": "Igor Kalnitsky"
        },
        {
            "name": "Valerii Hiora"
        },
        {
            "name": "Nikolay Zakharov"
        },
        {
            "name": "Dmitry Kovega"
        },
        {
            "name": "Sergey Ignatov"
        },
        {
            "name": "Antono Vasiljev"
        },
        {
            "name": "Stephan Kountso"
        },
        {
            "name": "pumbur"
        },
        {
            "name": "John Crepezzi"
        },
        {
            "name": "Andrey Vlasovskikh"
        },
        {
            "name": "Alexander Myadzel"
        },
        {
            "name": "Evgeny Stepanischev"
        },
        {
            "name": "Dmytrii Nagirniak"
        },
        {
            "name": "Luigi Maselli"
        },
        {
            "name": "Denis Bardadym"
        },
        {
            "name": "Aahan Krish"
        },
        {
            "name": "Ilya Baryshev"
        },
        {
            "name": "Aleksandar Ruzicic"
        },
        {
            "name": "Joe Cheng"
        },
        {
            "name": "Angel G. Olloqui"
        },
        {
            "name": "Jason Tate"
        },
        {
            "name": "Sergey Tikhomirov"
        },
        {
            "name": "Marc Fornos"
        },
        {
            "name": "Yoshihide Jimbo"
        },
        {
            "name": "Casey Duncan"
        },
        {
            "name": "Eugene Nizhibitsky"
        },
        {
            "name": "Alberto Gimeno"
        },
        {
            "name": "Kirk Kimmel"
        },
        {
            "name": "Nathan Grigg"
        },
        {
            "name": "Dr. Drang"
        },
        {
            "name": "Robin Ward"
        },
        {
            "name": "Dmitry Medvinsky"
        },
        {
            "name": "Jason Jacobson"
        },
        {
            "name": "Jonas Follesø"
        },
        {
            "name": "Dan Allen"
        },
        {
            "name": "noformnocontent"
        },
        {
            "name": "Damien White"
        },
        {
            "name": "Alexander Marenin"
        },
        {
            "name": "Cédric Néhémie"
        },
        {
            "name": "Simon Madine"
        },
        {
            "name": "Benjamin Pannell"
        },
        {
            "name": "Eric Knibbe"
        },
        {
            "name": "Poren Chiang"
        },
        {
            "name": "Kelley van Evert"
        },
        {
            "name": "Kurt Emch"
        },
        {
            "name": "Mehdi Dogguy"
        },
        {
            "name": "Nicolas Braud-Santoni"
        },
        {
            "name": "Ralf Bitter"
        },
        {
            "name": "Sylvestre Ledru"
        },
        {
            "name": "Troy Kershaw"
        },
        {
            "name": "Zena Treep"
        },
        {
            "name": "Daniel Kvasnicka"
        },
        {
            "name": "Carlo Kok"
        },
        {
            "name": "Bram de Haan"
        },
        {
            "name": "Seongwon Lee"
        },
        {
            "name": "Zaven Muradyan"
        },
        {
            "name": "Jan T. Sott"
        },
        {
            "name": "Brent Bradbury"
        },
        {
            "name": "Martin Dilling-Hansen"
        },
        {
            "name": "Ilya Vassilevsky"
        },
        {
            "name": "Josh Adams"
        },
        {
            "name": "Dan Tao"
        },
        {
            "name": "Jeff Escalante"
        },
        {
            "name": "Jun Yang"
        },
        {
            "name": "Nikolay Lisienko"
        },
        {
            "name": "Heiko August"
        },
        {
            "name": "Domen Kožar"
        },
        {
            "name": "Travis Odom"
        },
        {
            "name": "innocenat"
        },
        {
            "name": "Arthur Bikmullin"
        },
        {
            "name": "Pascal Hurni"
        },
        {
            "name": "Roman Shmatov"
        },
        {
            "name": "Nic West"
        },
        {
            "name": "Panu Horsmalahti"
        },
        {
            "name": "Flaviu Tamas"
        },
        {
            "name": "Damian Mee"
        },
        {
            "name": "Christopher Kaster"
        },
        {
            "name": "Chris Eidhof"
        },
        {
            "name": "Nate Cook"
        },
        {
            "name": "Matt Diephouse"
        },
        {
            "name": "Erik Osheim"
        },
        {
            "name": "Guillaume Laforge"
        },
        {
            "name": "Lucas Mazza"
        },
        {
            "name": "Maxim Dikun"
        },
        {
            "name": "Henrik Feldt"
        },
        {
            "name": "Anton Kochkov"
        },
        {
            "name": "Michael Allen"
        },
        {
            "name": "JP Verkamp"
        },
        {
            "name": "Adam Joseph Cook"
        },
        {
            "name": "Sergey Vidyuk"
        },
        {
            "name": "Radek Liska"
        },
        {
            "name": "Jose Molina Colmenero"
        },
        {
            "name": "Max Mikhailov"
        },
        {
            "name": "Bryant Williams"
        },
        {
            "name": "Erik Paluka"
        },
        {
            "name": "Luke Holder"
        },
        {
            "name": "David Mohundro"
        },
        {
            "name": "Nicholas Blumhardt"
        },
        {
            "name": "Christophe de Dinechin"
        },
        {
            "name": "Taneli Vatanen"
        },
        {
            "name": "Jen Evers-Corvina"
        },
        {
            "name": "Kassio Borges"
        },
        {
            "name": "Cedric Sohrauer"
        },
        {
            "name": "Mickaël Delahaye"
        },
        {
            "name": "Hakan Özler"
        },
        {
            "name": "Trey Shugart"
        },
        {
            "name": "Vincent Zurczak"
        },
        {
            "name": "Adam Joseph Cook"
        },
        {
            "name": "Edwin Dalorzo"
        },
        {
            "name": "mucaho"
        },
        {
            "name": "Dennis Titze"
        },
        {
            "name": "Jon Evans"
        },
        {
            "name": "Brian Quistorff"
        },
        {
            "name": "Jonathan Suever"
        },
        {
            "name": "Alexis Hénaut"
        },
        {
            "name": "Chris Kiehl"
        },
        {
            "name": "Peter Piwowarski"
        },
        {
            "name": "Kenta Sato"
        },
        {
            "name": "Anthony Scemama"
        },
        {
            "name": "Taufik Nurrohman"
        },
        {
            "name": "Pedro Oliveira"
        },
        {
            "name": "Gu Yiling"
        },
        {
            "name": "Thomas Applencourt"
        },
        {
            "name": "Andrew Farmer"
        },
        {
            "name": "Sergey Mashkov"
        },
        {
            "name": "Raivo Laanemets"
        },
        {
            "name": "Kenneth Fuglsang"
        },
        {
            "name": "David Anson"
        },
        {
            "name": "Louis Barranqueiro"
        },
        {
            "name": "Tim Schumacher"
        },
        {
            "name": "Lucas Werkmeister"
        },
        {
            "name": "Dan Panzarella"
        },
        {
            "name": "Bruno Dias"
        },
        {
            "name": "Jay Strybis"
        },
        {
            "name": "Guillaume Gomez"
        },
        {
            "name": "Janis Voigtländer"
        },
        {
            "name": "Dirk Kirsten"
        },
        {
            "name": "MY Sun"
        },
        {
            "name": "Vadimtro"
        },
        {
            "name": "Benjamin Auder"
        },
        {
            "name": "Dotan Dimet"
        },
        {
            "name": "Manh Tuan"
        },
        {
            "name": "Philippe Charrière"
        },
        {
            "name": "Stefan Bechert"
        },
        {
            "name": "Samuel Reed"
        },
        {
            "name": "Yury Selivanov"
        },
        {
            "name": "Tsuyusato Kitsune"
        },
        {
            "name": "Mick MacCallum"
        },
        {
            "name": "Kristoffer Gronlund"
        },
        {
            "name": "Søren Enevoldsen"
        },
        {
            "name": "Daniel Rosenwasser"
        },
        {
            "name": "Ladislav Prskavec"
        },
        {
            "name": "Jan Kühle"
        },
        {
            "name": "Stefan Wienert"
        },
        {
            "name": "Nikita Savchenko"
        },
        {
            "name": "Stefania Mellai"
        },
        {
            "name": "Nebuleon Fumika"
        },
        {
            "name": "prince"
        },
        {
            "name": "Brendan Rocks"
        },
        {
            "name": "Raphaël Assénat"
        },
        {
            "name": "Matt Evans"
        },
        {
            "name": "Martin Braun"
        },
        {
            "name": "Boris Cherny"
        },
        {
            "name": "John Foster"
        },
        {
            "name": "Robert Dodier"
        },
        {
            "name": "Anthony Dugois"
        },
        {
            "name": "Qeole"
        },
        {
            "name": "Denis Ciccale"
        },
        {
            "name": "Michael Johnston"
        },
        {
            "name": "Taras"
        },
        {
            "name": "Philipp Wolfer"
        },
        {
            "name": "Mikko Kouhia"
        },
        {
            "name": "Billy Quith"
        },
        {
            "name": "Herbert Shin"
        },
        {
            "name": "Tristano Ajmone"
        },
        {
            "name": "Taisuke Fujimoto"
        },
        {
            "name": "Boone Severson"
        },
        {
            "name": "Victor Zhou"
        },
        {
            "name": "Lars Schulna"
        },
        {
            "name": "Jacob Childress"
        },
        {
            "name": "Gavin Siu"
        },
        {
            "name": "Builder's Brewery"
        },
        {
            "name": "Sergey Bronnikov"
        },
        {
            "name": "Joe Eli McIlvain"
        },
        {
            "name": "Stephan Boyer"
        },
        {
            "name": "Alex McKibben"
        },
        {
            "name": "Daniel Gamage"
        },
        {
            "name": "Matthew Daly"
        },
        {
            "name": "Magnus Madsen"
        },
        {
            "name": "Camil Staps"
        },
        {
            "name": "Alexander Lichter"
        },
        {
            "name": "Nicolas Le Gall"
        },
        {
            "name": "Kenton Hamaluik"
        },
        {
            "name": "Marvin Saignat"
        },
        {
            "name": "Michael Rodler"
        },
        {
            "name": "Sergey Sobko"
        },
        {
            "name": "Hale Chan"
        },
        {
            "name": "Matt Evans"
        },
        {
            "name": "Kasper Andersen"
        },
        {
            "name": "Philipp A."
        },
        {
            "name": "Guannan Wei"
        },
        {
            "name": "Sam Wu"
        },
        {
            "name": "Ike Ku"
        },
        {
            "name": "Andres Täht"
        },
        {
            "name": "Rene Saarsoo"
        }
    ],
    "dependencies": {},
    "description": "Syntax highlighting with language autodetection.",
    "devDependencies": {
        "bluebird": "^3.0.1",
        "commander": "^2.3.0",
        "del": "^2.0.2",
        "gear": "^0.9.4",
        "gear-lib": "^0.9.2",
        "glob": "^7.0.3",
        "js-beautify": "^1.5.10",
        "jsdom": "^9.2.1",
        "lodash": "^4.0.0",
        "mocha": "^2.0.1",
        "should": "^9.0.2",
        "tiny-worker": "^1.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f9f0b14c0be00f0e4fb1e577b749fed9e6f52f55",
        "tarball": "https://registry.npmjs.org/highlight.js/-/highlight.js-9.10.0.tgz"
    },
    "engines": {
        "node": "*"
    },
    "homepage": "https://highlightjs.org/",
    "keywords": [
        "highlight",
        "syntax"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "jga"
        },
        {
            "name": "isagalaev"
        }
    ],
    "name": "highlight.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/isagalaev/highlight.js.git"
    },
    "scripts": {
        "test": "mocha test/",
        "test-browser": "mocha test/browser/"
    },
    "version": "9.10.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module highlight.js](#apidoc.module.highlight.js)
1.  [function <span class="apidocSignatureSpan">highlight.js.</span>COMMENT (begin, end, inherits)](#apidoc.element.highlight.js.COMMENT)
1.  [function <span class="apidocSignatureSpan">highlight.js.</span>configure (user_options)](#apidoc.element.highlight.js.configure)
1.  [function <span class="apidocSignatureSpan">highlight.js.</span>fixMarkup (value)](#apidoc.element.highlight.js.fixMarkup)
1.  [function <span class="apidocSignatureSpan">highlight.js.</span>getLanguage (name)](#apidoc.element.highlight.js.getLanguage)
1.  [function <span class="apidocSignatureSpan">highlight.js.</span>highlight (name, value, ignore_illegals, continuation)](#apidoc.element.highlight.js.highlight)
1.  [function <span class="apidocSignatureSpan">highlight.js.</span>highlightAuto (text, languageSubset)](#apidoc.element.highlight.js.highlightAuto)
1.  [function <span class="apidocSignatureSpan">highlight.js.</span>highlightBlock (block)](#apidoc.element.highlight.js.highlightBlock)
1.  [function <span class="apidocSignatureSpan">highlight.js.</span>inherit (parent)](#apidoc.element.highlight.js.inherit)
1.  [function <span class="apidocSignatureSpan">highlight.js.</span>initHighlighting ()](#apidoc.element.highlight.js.initHighlighting)
1.  [function <span class="apidocSignatureSpan">highlight.js.</span>initHighlightingOnLoad ()](#apidoc.element.highlight.js.initHighlightingOnLoad)
1.  [function <span class="apidocSignatureSpan">highlight.js.</span>listLanguages ()](#apidoc.element.highlight.js.listLanguages)
1.  [function <span class="apidocSignatureSpan">highlight.js.</span>registerLanguage (name, language)](#apidoc.element.highlight.js.registerLanguage)
1.  object <span class="apidocSignatureSpan">highlight.js.</span>APOS_STRING_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>BACKSLASH_ESCAPE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>BINARY_NUMBER_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>CSS_NUMBER_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>C_BLOCK_COMMENT_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>C_LINE_COMMENT_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>C_NUMBER_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>HASH_COMMENT_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>METHOD_GUARD
1.  object <span class="apidocSignatureSpan">highlight.js.</span>NUMBER_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>PHRASAL_WORDS_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>QUOTE_STRING_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>REGEXP_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>TITLE_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>UNDERSCORE_TITLE_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.</span>js.highlight
1.  string <span class="apidocSignatureSpan">highlight.js.</span>BINARY_NUMBER_RE
1.  string <span class="apidocSignatureSpan">highlight.js.</span>C_NUMBER_RE
1.  string <span class="apidocSignatureSpan">highlight.js.</span>IDENT_RE
1.  string <span class="apidocSignatureSpan">highlight.js.</span>NUMBER_RE
1.  string <span class="apidocSignatureSpan">highlight.js.</span>RE_STARTERS_RE
1.  string <span class="apidocSignatureSpan">highlight.js.</span>UNDERSCORE_IDENT_RE

#### [module highlight.js.highlight](#apidoc.module.highlight.js.highlight)
1.  [function <span class="apidocSignatureSpan">highlight.js.</span>highlight (name, value, ignore_illegals, continuation)](#apidoc.element.highlight.js.highlight.highlight)
1.  [function <span class="apidocSignatureSpan">highlight.js.highlight.</span>COMMENT (begin, end, inherits)](#apidoc.element.highlight.js.highlight.COMMENT)
1.  [function <span class="apidocSignatureSpan">highlight.js.highlight.</span>configure (user_options)](#apidoc.element.highlight.js.highlight.configure)
1.  [function <span class="apidocSignatureSpan">highlight.js.highlight.</span>fixMarkup (value)](#apidoc.element.highlight.js.highlight.fixMarkup)
1.  [function <span class="apidocSignatureSpan">highlight.js.highlight.</span>getLanguage (name)](#apidoc.element.highlight.js.highlight.getLanguage)
1.  [function <span class="apidocSignatureSpan">highlight.js.highlight.</span>highlightAuto (text, languageSubset)](#apidoc.element.highlight.js.highlight.highlightAuto)
1.  [function <span class="apidocSignatureSpan">highlight.js.highlight.</span>highlightBlock (block)](#apidoc.element.highlight.js.highlight.highlightBlock)
1.  [function <span class="apidocSignatureSpan">highlight.js.highlight.</span>inherit (parent)](#apidoc.element.highlight.js.highlight.inherit)
1.  [function <span class="apidocSignatureSpan">highlight.js.highlight.</span>initHighlighting ()](#apidoc.element.highlight.js.highlight.initHighlighting)
1.  [function <span class="apidocSignatureSpan">highlight.js.highlight.</span>initHighlightingOnLoad ()](#apidoc.element.highlight.js.highlight.initHighlightingOnLoad)
1.  [function <span class="apidocSignatureSpan">highlight.js.highlight.</span>listLanguages ()](#apidoc.element.highlight.js.highlight.listLanguages)
1.  [function <span class="apidocSignatureSpan">highlight.js.highlight.</span>registerLanguage (name, language)](#apidoc.element.highlight.js.highlight.registerLanguage)
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>APOS_STRING_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>BACKSLASH_ESCAPE
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>BINARY_NUMBER_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>CSS_NUMBER_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>C_BLOCK_COMMENT_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>C_LINE_COMMENT_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>C_NUMBER_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>HASH_COMMENT_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>METHOD_GUARD
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>NUMBER_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>PHRASAL_WORDS_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>QUOTE_STRING_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>REGEXP_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>TITLE_MODE
1.  object <span class="apidocSignatureSpan">highlight.js.highlight.</span>UNDERSCORE_TITLE_MODE
1.  string <span class="apidocSignatureSpan">highlight.js.highlight.</span>BINARY_NUMBER_RE
1.  string <span class="apidocSignatureSpan">highlight.js.highlight.</span>C_NUMBER_RE
1.  string <span class="apidocSignatureSpan">highlight.js.highlight.</span>IDENT_RE
1.  string <span class="apidocSignatureSpan">highlight.js.highlight.</span>NUMBER_RE
1.  string <span class="apidocSignatureSpan">highlight.js.highlight.</span>RE_STARTERS_RE
1.  string <span class="apidocSignatureSpan">highlight.js.highlight.</span>UNDERSCORE_IDENT_RE



# <a name="apidoc.module.highlight.js"></a>[module highlight.js](#apidoc.module.highlight.js)

#### <a name="apidoc.element.highlight.js.COMMENT"></a>[function <span class="apidocSignatureSpan">highlight.js.</span>COMMENT (begin, end, inherits)](#apidoc.element.highlight.js.COMMENT)
- description and source-code
```javascript
COMMENT = function (begin, end, inherits) {
  var mode = hljs.inherit(
    {
      className: 'comment',
      begin: begin, end: end,
      contains: []
    },
    inherits || {}
  );
  mode.contains.push(hljs.PHRASAL_WORDS_MODE);
  mode.contains.push({
    className: 'doctag',
    begin: '(?:TODO|FIXME|NOTE|BUG|XXX):',
    relevance: 0
  });
  return mode;
}
```
- example usage
```shell
...
  mode.contains.push({
    className: 'doctag',
    begin: '(?:TODO|FIXME|NOTE|BUG|XXX):',
    relevance: 0
  });
  return mode;
};
hljs.C_LINE_COMMENT_MODE = hljs.COMMENT('//', '$');
hljs.C_BLOCK_COMMENT_MODE = hljs.COMMENT('/\\*', '\\*/');
hljs.HASH_COMMENT_MODE = hljs.COMMENT('#', '$');
hljs.NUMBER_MODE = {
  className: 'number',
  begin: hljs.NUMBER_RE,
  relevance: 0
};
...
```

#### <a name="apidoc.element.highlight.js.configure"></a>[function <span class="apidocSignatureSpan">highlight.js.</span>configure (user_options)](#apidoc.element.highlight.js.configure)
- description and source-code
```javascript
function configure(user_options) {
  options = inherit(options, user_options);
}
```
- example usage
```shell
...
'''

You can use any tags instead of '<pre><code>' to mark up your code. If
you don't use a container that preserve line breaks you will need to
configure highlight.js to use the '<br>' tag:

'''javascript
hljs.configure({useBR: true});

$('div.code').each(function(i, block) {
  hljs.highlightBlock(block);
});
'''

For other options refer to the documentation for ['configure'][4].
...
```

#### <a name="apidoc.element.highlight.js.fixMarkup"></a>[function <span class="apidocSignatureSpan">highlight.js.</span>fixMarkup (value)](#apidoc.element.highlight.js.fixMarkup)
- description and source-code
```javascript
function fixMarkup(value) {
  return !(options.tabReplace || options.useBR)
    ? value
    : value.replace(fixMarkupRe, function(match, p1) {
        if (options.useBR && match === '\n') {
          return '<br>';
        } else if (options.tabReplace) {
          return p1.replace(/\t/g, options.tabReplace);
        }
        return '';
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.highlight.js.getLanguage"></a>[function <span class="apidocSignatureSpan">highlight.js.</span>getLanguage (name)](#apidoc.element.highlight.js.getLanguage)
- description and source-code
```javascript
function getLanguage(name) {
  name = (name || '').toLowerCase();
  return languages[name] || languages[aliases[name]];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.highlight.js.highlight"></a>[function <span class="apidocSignatureSpan">highlight.js.</span>highlight (name, value, ignore_illegals, continuation)](#apidoc.element.highlight.js.highlight)
- description and source-code
```javascript
function highlight(name, value, ignore_illegals, continuation) {

  function subMode(lexeme, mode) {
    var i, length;

    for (i = 0, length = mode.contains.length; i < length; i++) {
      if (testRe(mode.contains[i].beginRe, lexeme)) {
        return mode.contains[i];
      }
    }
  }

  function endOfMode(mode, lexeme) {
    if (testRe(mode.endRe, lexeme)) {
      while (mode.endsParent && mode.parent) {
        mode = mode.parent;
      }
      return mode;
    }
    if (mode.endsWithParent) {
      return endOfMode(mode.parent, lexeme);
    }
  }

  function isIllegal(lexeme, mode) {
    return !ignore_illegals && testRe(mode.illegalRe, lexeme);
  }

  function keywordMatch(mode, match) {
    var match_str = language.case_insensitive ? match[0].toLowerCase() : match[0];
    return mode.keywords.hasOwnProperty(match_str) && mode.keywords[match_str];
  }

  function buildSpan(classname, insideSpan, leaveOpen, noPrefix) {
    var classPrefix = noPrefix ? '' : options.classPrefix,
        openSpan    = '<span class="' + classPrefix,
        closeSpan   = leaveOpen ? '' : spanEndTag

    openSpan += classname + '">';

    return openSpan + insideSpan + closeSpan;
  }

  function processKeywords() {
    var keyword_match, last_index, match, result;

    if (!top.keywords)
      return escape(mode_buffer);

    result = '';
    last_index = 0;
    top.lexemesRe.lastIndex = 0;
    match = top.lexemesRe.exec(mode_buffer);

    while (match) {
      result += escape(mode_buffer.substring(last_index, match.index));
      keyword_match = keywordMatch(top, match);
      if (keyword_match) {
        relevance += keyword_match[1];
        result += buildSpan(keyword_match[0], escape(match[0]));
      } else {
        result += escape(match[0]);
      }
      last_index = top.lexemesRe.lastIndex;
      match = top.lexemesRe.exec(mode_buffer);
    }
    return result + escape(mode_buffer.substr(last_index));
  }

  function processSubLanguage() {
    var explicit = typeof top.subLanguage === 'string';
    if (explicit && !languages[top.subLanguage]) {
      return escape(mode_buffer);
    }

    var result = explicit ?
                 highlight(top.subLanguage, mode_buffer, true, continuations[top.subLanguage]) :
                 highlightAuto(mode_buffer, top.subLanguage.length ? top.subLanguage : undefined);

    // Counting embedded language score towards the host language may be disabled
    // with zeroing the containing mode relevance. Usecase in point is Markdown that
    // allows XML everywhere and makes every XML snippet to have a much larger Markdown
    // score.
    if (top.relevance > 0) {
      relevance += result.relevance;
    }
    if (explicit) {
      continuations[top.subLanguage] = result.top;
    }
    return buildSpan(result.language, result.value, false, true);
  }

  function processBuffer() {
    result += (top.subLanguage != null ? processSubLanguage() : processKeywords());
    mode_buffer = '';
  }

  function startNewMode(mode) {
    result += mode.className? buildSpan(mode.className, '', true): '';
    top = Object.create(mode, {parent: {value: top}});
  }

  function processLexeme(buffer, lexeme) {

    mode_buffer += buffer;

    if (lexeme == null) {
      processBuffer();
      return 0;
    }

    var new_mode = subMode(lexeme, top);
    if (new_mode) {
      if (new_mode.skip) {
        mode_buffer += lexeme;
      } else {
        if (new_mode.excludeBegin) {
          mode_buffer += lexeme;
        }
        processBuffer();
        if (!new_mode.returnBegin && !new_mode.excludeBegin) {
          mode_buffer = lexeme;
        }
      }
      startNewMode(new_mode, lexeme);
      return new_mode.returnBegin ? 0 : lexeme.length;
    }

    var end_mode = endOfMode(top, lexeme);
    if (end_mode) {
      var origin = top;
      if (origin.skip) {
        mode_buffer += lexeme;
      } else {
        if (!(origin.returnEnd || origin.excludeEnd)) {
          mode_buffer += lexeme;
        }
        processBuffer();
        if (origin.excludeEnd) {
          mode_buffer = lexeme;
        } ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.highlight.js.highlightAuto"></a>[function <span class="apidocSignatureSpan">highlight.js.</span>highlightAuto (text, languageSubset)](#apidoc.element.highlight.js.highlightAuto)
- description and source-code
```javascript
function highlightAuto(text, languageSubset) {
  languageSubset = languageSubset || options.languages || objectKeys(languages);
  var result = {
    relevance: 0,
    value: escape(text)
  };
  var second_best = result;
  languageSubset.filter(getLanguage).forEach(function(name) {
    var current = highlight(name, text, false);
    current.language = name;
    if (current.relevance > second_best.relevance) {
      second_best = current;
    }
    if (current.relevance > result.relevance) {
      second_best = result;
      result = current;
    }
  });
  if (second_best.language) {
    result.second_best = second_best;
  }
  return result;
}
```
- example usage
```shell
...
'''

In worker.js:

'''javascript
onmessage = function(event) {
  importScripts('<path>/highlight.pack.js');
  var result = self.hljs.highlightAuto(event.data);
  postMessage(result.value);
}
'''


## Getting the Library
...
```

#### <a name="apidoc.element.highlight.js.highlightBlock"></a>[function <span class="apidocSignatureSpan">highlight.js.</span>highlightBlock (block)](#apidoc.element.highlight.js.highlightBlock)
- description and source-code
```javascript
function highlightBlock(block) {
  var node, originalStream, result, resultNode, text;
  var language = blockLanguage(block);

  if (isNotHighlighted(language))
      return;

  if (options.useBR) {
    node = document.createElementNS('http://www.w3.org/1999/xhtml', 'div');
    node.innerHTML = block.innerHTML.replace(/\n/g, '').replace(/<br[ \/]*>/g, '\n');
  } else {
    node = block;
  }
  text = node.textContent;
  result = language ? highlight(language, text, true) : highlightAuto(text);

  originalStream = nodeStream(node);
  if (originalStream.length) {
    resultNode = document.createElementNS('http://www.w3.org/1999/xhtml', 'div');
    resultNode.innerHTML = result.value;
    result.value = mergeStreams(originalStream, nodeStream(resultNode), text);
  }
  result.value = fixMarkup(result.value);

  block.innerHTML = result.value;
  block.className = buildClassName(block.className, language, result.language);
  block.result = {
    language: result.language,
    re: result.relevance
  };
  if (result.second_best) {
    block.second_best = {
      language: result.second_best.language,
      re: result.second_best.relevance
    };
  }
}
```
- example usage
```shell
...

Here’s an equivalent way to calling ['initHighlightingOnLoad'][1] using
jQuery:

'''javascript
$(document).ready(function() {
  $('pre code').each(function(i, block) {
    hljs.highlightBlock(block);
  });
});
'''

You can use any tags instead of '<pre><code>' to mark up your code. If
you don't use a container that preserve line breaks you will need to
configure highlight.js to use the '<br>' tag:
...
```

#### <a name="apidoc.element.highlight.js.inherit"></a>[function <span class="apidocSignatureSpan">highlight.js.</span>inherit (parent)](#apidoc.element.highlight.js.inherit)
- description and source-code
```javascript
function inherit(parent) {  // inherit(parent, override_obj, override_obj, ...)
  var key;
  var result = {};
  var objects = Array.prototype.slice.call(arguments, 1);

  for (key in parent)
    result[key] = parent[key];
  objects.forEach(function(obj) {
    for (key in obj)
      result[key] = obj[key];
  });
  return result;
}
```
- example usage
```shell
...
  illegal: '\\n',
  contains: [hljs.BACKSLASH_ESCAPE]
};
hljs.PHRASAL_WORDS_MODE = {
  begin: /\b(a|an|the|are|I'm|isn't|don't|doesn't|won't|but|just|should|pretty|simply|enough|gonna|going|wtf|so|such|will|you|your
|like)\b/
};
hljs.COMMENT = function (begin, end, inherits) {
  var mode = hljs.inherit(
    {
      className: 'comment',
      begin: begin, end: end,
      contains: []
    },
    inherits || {}
  );
...
```

#### <a name="apidoc.element.highlight.js.initHighlighting"></a>[function <span class="apidocSignatureSpan">highlight.js.</span>initHighlighting ()](#apidoc.element.highlight.js.initHighlighting)
- description and source-code
```javascript
function initHighlighting() {
  if (initHighlighting.called)
    return;
  initHighlighting.called = true;

  var blocks = document.querySelectorAll('pre code');
  ArrayProto.forEach.call(blocks, highlightBlock);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.highlight.js.initHighlightingOnLoad"></a>[function <span class="apidocSignatureSpan">highlight.js.</span>initHighlightingOnLoad ()](#apidoc.element.highlight.js.initHighlightingOnLoad)
- description and source-code
```javascript
function initHighlightingOnLoad() {
  addEventListener('DOMContentLoaded', initHighlighting, false);
  addEventListener('load', initHighlighting, false);
}
```
- example usage
```shell
...
The bare minimum for using highlight.js on a web page is linking to the
library along with one of the styles and calling
['initHighlightingOnLoad'][1]:

'''html
<link rel="stylesheet" href="/path/to/styles/default.css">
<script src="/path/to/highlight.pack.js"></script>
<script>hljs.initHighlightingOnLoad();</script>
'''

This will find and highlight code inside of '<pre><code>' tags; it tries
to detect the language automatically. If automatic detection doesn’t
work for you, you can specify the language in the 'class' attribute:

'''html
...
```

#### <a name="apidoc.element.highlight.js.listLanguages"></a>[function <span class="apidocSignatureSpan">highlight.js.</span>listLanguages ()](#apidoc.element.highlight.js.listLanguages)
- description and source-code
```javascript
function listLanguages() {
  return objectKeys(languages);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.highlight.js.registerLanguage"></a>[function <span class="apidocSignatureSpan">highlight.js.</span>registerLanguage (name, language)](#apidoc.element.highlight.js.registerLanguage)
- description and source-code
```javascript
function registerLanguage(name, language) {
  var lang = languages[name] = language(hljs);
  if (lang.aliases) {
    lang.aliases.forEach(function(alias) {aliases[alias] = name;});
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.highlight.js.highlight"></a>[module highlight.js.highlight](#apidoc.module.highlight.js.highlight)

#### <a name="apidoc.element.highlight.js.highlight.highlight"></a>[function <span class="apidocSignatureSpan">highlight.js.</span>highlight (name, value, ignore_illegals, continuation)](#apidoc.element.highlight.js.highlight.highlight)
- description and source-code
```javascript
function highlight(name, value, ignore_illegals, continuation) {

  function subMode(lexeme, mode) {
    var i, length;

    for (i = 0, length = mode.contains.length; i < length; i++) {
      if (testRe(mode.contains[i].beginRe, lexeme)) {
        return mode.contains[i];
      }
    }
  }

  function endOfMode(mode, lexeme) {
    if (testRe(mode.endRe, lexeme)) {
      while (mode.endsParent && mode.parent) {
        mode = mode.parent;
      }
      return mode;
    }
    if (mode.endsWithParent) {
      return endOfMode(mode.parent, lexeme);
    }
  }

  function isIllegal(lexeme, mode) {
    return !ignore_illegals && testRe(mode.illegalRe, lexeme);
  }

  function keywordMatch(mode, match) {
    var match_str = language.case_insensitive ? match[0].toLowerCase() : match[0];
    return mode.keywords.hasOwnProperty(match_str) && mode.keywords[match_str];
  }

  function buildSpan(classname, insideSpan, leaveOpen, noPrefix) {
    var classPrefix = noPrefix ? '' : options.classPrefix,
        openSpan    = '<span class="' + classPrefix,
        closeSpan   = leaveOpen ? '' : spanEndTag

    openSpan += classname + '">';

    return openSpan + insideSpan + closeSpan;
  }

  function processKeywords() {
    var keyword_match, last_index, match, result;

    if (!top.keywords)
      return escape(mode_buffer);

    result = '';
    last_index = 0;
    top.lexemesRe.lastIndex = 0;
    match = top.lexemesRe.exec(mode_buffer);

    while (match) {
      result += escape(mode_buffer.substring(last_index, match.index));
      keyword_match = keywordMatch(top, match);
      if (keyword_match) {
        relevance += keyword_match[1];
        result += buildSpan(keyword_match[0], escape(match[0]));
      } else {
        result += escape(match[0]);
      }
      last_index = top.lexemesRe.lastIndex;
      match = top.lexemesRe.exec(mode_buffer);
    }
    return result + escape(mode_buffer.substr(last_index));
  }

  function processSubLanguage() {
    var explicit = typeof top.subLanguage === 'string';
    if (explicit && !languages[top.subLanguage]) {
      return escape(mode_buffer);
    }

    var result = explicit ?
                 highlight(top.subLanguage, mode_buffer, true, continuations[top.subLanguage]) :
                 highlightAuto(mode_buffer, top.subLanguage.length ? top.subLanguage : undefined);

    // Counting embedded language score towards the host language may be disabled
    // with zeroing the containing mode relevance. Usecase in point is Markdown that
    // allows XML everywhere and makes every XML snippet to have a much larger Markdown
    // score.
    if (top.relevance > 0) {
      relevance += result.relevance;
    }
    if (explicit) {
      continuations[top.subLanguage] = result.top;
    }
    return buildSpan(result.language, result.value, false, true);
  }

  function processBuffer() {
    result += (top.subLanguage != null ? processSubLanguage() : processKeywords());
    mode_buffer = '';
  }

  function startNewMode(mode) {
    result += mode.className? buildSpan(mode.className, '', true): '';
    top = Object.create(mode, {parent: {value: top}});
  }

  function processLexeme(buffer, lexeme) {

    mode_buffer += buffer;

    if (lexeme == null) {
      processBuffer();
      return 0;
    }

    var new_mode = subMode(lexeme, top);
    if (new_mode) {
      if (new_mode.skip) {
        mode_buffer += lexeme;
      } else {
        if (new_mode.excludeBegin) {
          mode_buffer += lexeme;
        }
        processBuffer();
        if (!new_mode.returnBegin && !new_mode.excludeBegin) {
          mode_buffer = lexeme;
        }
      }
      startNewMode(new_mode, lexeme);
      return new_mode.returnBegin ? 0 : lexeme.length;
    }

    var end_mode = endOfMode(top, lexeme);
    if (end_mode) {
      var origin = top;
      if (origin.skip) {
        mode_buffer += lexeme;
      } else {
        if (!(origin.returnEnd || origin.excludeEnd)) {
          mode_buffer += lexeme;
        }
        processBuffer();
        if (origin.excludeEnd) {
          mode_buffer = lexeme;
        } ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.highlight.js.highlight.COMMENT"></a>[function <span class="apidocSignatureSpan">highlight.js.highlight.</span>COMMENT (begin, end, inherits)](#apidoc.element.highlight.js.highlight.COMMENT)
- description and source-code
```javascript
COMMENT = function (begin, end, inherits) {
  var mode = hljs.inherit(
    {
      className: 'comment',
      begin: begin, end: end,
      contains: []
    },
    inherits || {}
  );
  mode.contains.push(hljs.PHRASAL_WORDS_MODE);
  mode.contains.push({
    className: 'doctag',
    begin: '(?:TODO|FIXME|NOTE|BUG|XXX):',
    relevance: 0
  });
  return mode;
}
```
- example usage
```shell
...
  mode.contains.push({
    className: 'doctag',
    begin: '(?:TODO|FIXME|NOTE|BUG|XXX):',
    relevance: 0
  });
  return mode;
};
hljs.C_LINE_COMMENT_MODE = hljs.COMMENT('//', '$');
hljs.C_BLOCK_COMMENT_MODE = hljs.COMMENT('/\\*', '\\*/');
hljs.HASH_COMMENT_MODE = hljs.COMMENT('#', '$');
hljs.NUMBER_MODE = {
  className: 'number',
  begin: hljs.NUMBER_RE,
  relevance: 0
};
...
```

#### <a name="apidoc.element.highlight.js.highlight.configure"></a>[function <span class="apidocSignatureSpan">highlight.js.highlight.</span>configure (user_options)](#apidoc.element.highlight.js.highlight.configure)
- description and source-code
```javascript
function configure(user_options) {
  options = inherit(options, user_options);
}
```
- example usage
```shell
...
'''

You can use any tags instead of '<pre><code>' to mark up your code. If
you don't use a container that preserve line breaks you will need to
configure highlight.js to use the '<br>' tag:

'''javascript
hljs.configure({useBR: true});

$('div.code').each(function(i, block) {
  hljs.highlightBlock(block);
});
'''

For other options refer to the documentation for ['configure'][4].
...
```

#### <a name="apidoc.element.highlight.js.highlight.fixMarkup"></a>[function <span class="apidocSignatureSpan">highlight.js.highlight.</span>fixMarkup (value)](#apidoc.element.highlight.js.highlight.fixMarkup)
- description and source-code
```javascript
function fixMarkup(value) {
  return !(options.tabReplace || options.useBR)
    ? value
    : value.replace(fixMarkupRe, function(match, p1) {
        if (options.useBR && match === '\n') {
          return '<br>';
        } else if (options.tabReplace) {
          return p1.replace(/\t/g, options.tabReplace);
        }
        return '';
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.highlight.js.highlight.getLanguage"></a>[function <span class="apidocSignatureSpan">highlight.js.highlight.</span>getLanguage (name)](#apidoc.element.highlight.js.highlight.getLanguage)
- description and source-code
```javascript
function getLanguage(name) {
  name = (name || '').toLowerCase();
  return languages[name] || languages[aliases[name]];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.highlight.js.highlight.highlightAuto"></a>[function <span class="apidocSignatureSpan">highlight.js.highlight.</span>highlightAuto (text, languageSubset)](#apidoc.element.highlight.js.highlight.highlightAuto)
- description and source-code
```javascript
function highlightAuto(text, languageSubset) {
  languageSubset = languageSubset || options.languages || objectKeys(languages);
  var result = {
    relevance: 0,
    value: escape(text)
  };
  var second_best = result;
  languageSubset.filter(getLanguage).forEach(function(name) {
    var current = highlight(name, text, false);
    current.language = name;
    if (current.relevance > second_best.relevance) {
      second_best = current;
    }
    if (current.relevance > result.relevance) {
      second_best = result;
      result = current;
    }
  });
  if (second_best.language) {
    result.second_best = second_best;
  }
  return result;
}
```
- example usage
```shell
...
'''

In worker.js:

'''javascript
onmessage = function(event) {
  importScripts('<path>/highlight.pack.js');
  var result = self.hljs.highlightAuto(event.data);
  postMessage(result.value);
}
'''


## Getting the Library
...
```

#### <a name="apidoc.element.highlight.js.highlight.highlightBlock"></a>[function <span class="apidocSignatureSpan">highlight.js.highlight.</span>highlightBlock (block)](#apidoc.element.highlight.js.highlight.highlightBlock)
- description and source-code
```javascript
function highlightBlock(block) {
  var node, originalStream, result, resultNode, text;
  var language = blockLanguage(block);

  if (isNotHighlighted(language))
      return;

  if (options.useBR) {
    node = document.createElementNS('http://www.w3.org/1999/xhtml', 'div');
    node.innerHTML = block.innerHTML.replace(/\n/g, '').replace(/<br[ \/]*>/g, '\n');
  } else {
    node = block;
  }
  text = node.textContent;
  result = language ? highlight(language, text, true) : highlightAuto(text);

  originalStream = nodeStream(node);
  if (originalStream.length) {
    resultNode = document.createElementNS('http://www.w3.org/1999/xhtml', 'div');
    resultNode.innerHTML = result.value;
    result.value = mergeStreams(originalStream, nodeStream(resultNode), text);
  }
  result.value = fixMarkup(result.value);

  block.innerHTML = result.value;
  block.className = buildClassName(block.className, language, result.language);
  block.result = {
    language: result.language,
    re: result.relevance
  };
  if (result.second_best) {
    block.second_best = {
      language: result.second_best.language,
      re: result.second_best.relevance
    };
  }
}
```
- example usage
```shell
...

Here’s an equivalent way to calling ['initHighlightingOnLoad'][1] using
jQuery:

'''javascript
$(document).ready(function() {
  $('pre code').each(function(i, block) {
    hljs.highlightBlock(block);
  });
});
'''

You can use any tags instead of '<pre><code>' to mark up your code. If
you don't use a container that preserve line breaks you will need to
configure highlight.js to use the '<br>' tag:
...
```

#### <a name="apidoc.element.highlight.js.highlight.inherit"></a>[function <span class="apidocSignatureSpan">highlight.js.highlight.</span>inherit (parent)](#apidoc.element.highlight.js.highlight.inherit)
- description and source-code
```javascript
function inherit(parent) {  // inherit(parent, override_obj, override_obj, ...)
  var key;
  var result = {};
  var objects = Array.prototype.slice.call(arguments, 1);

  for (key in parent)
    result[key] = parent[key];
  objects.forEach(function(obj) {
    for (key in obj)
      result[key] = obj[key];
  });
  return result;
}
```
- example usage
```shell
...
  illegal: '\\n',
  contains: [hljs.BACKSLASH_ESCAPE]
};
hljs.PHRASAL_WORDS_MODE = {
  begin: /\b(a|an|the|are|I'm|isn't|don't|doesn't|won't|but|just|should|pretty|simply|enough|gonna|going|wtf|so|such|will|you|your
|like)\b/
};
hljs.COMMENT = function (begin, end, inherits) {
  var mode = hljs.inherit(
    {
      className: 'comment',
      begin: begin, end: end,
      contains: []
    },
    inherits || {}
  );
...
```

#### <a name="apidoc.element.highlight.js.highlight.initHighlighting"></a>[function <span class="apidocSignatureSpan">highlight.js.highlight.</span>initHighlighting ()](#apidoc.element.highlight.js.highlight.initHighlighting)
- description and source-code
```javascript
function initHighlighting() {
  if (initHighlighting.called)
    return;
  initHighlighting.called = true;

  var blocks = document.querySelectorAll('pre code');
  ArrayProto.forEach.call(blocks, highlightBlock);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.highlight.js.highlight.initHighlightingOnLoad"></a>[function <span class="apidocSignatureSpan">highlight.js.highlight.</span>initHighlightingOnLoad ()](#apidoc.element.highlight.js.highlight.initHighlightingOnLoad)
- description and source-code
```javascript
function initHighlightingOnLoad() {
  addEventListener('DOMContentLoaded', initHighlighting, false);
  addEventListener('load', initHighlighting, false);
}
```
- example usage
```shell
...
The bare minimum for using highlight.js on a web page is linking to the
library along with one of the styles and calling
['initHighlightingOnLoad'][1]:

'''html
<link rel="stylesheet" href="/path/to/styles/default.css">
<script src="/path/to/highlight.pack.js"></script>
<script>hljs.initHighlightingOnLoad();</script>
'''

This will find and highlight code inside of '<pre><code>' tags; it tries
to detect the language automatically. If automatic detection doesn’t
work for you, you can specify the language in the 'class' attribute:

'''html
...
```

#### <a name="apidoc.element.highlight.js.highlight.listLanguages"></a>[function <span class="apidocSignatureSpan">highlight.js.highlight.</span>listLanguages ()](#apidoc.element.highlight.js.highlight.listLanguages)
- description and source-code
```javascript
function listLanguages() {
  return objectKeys(languages);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.highlight.js.highlight.registerLanguage"></a>[function <span class="apidocSignatureSpan">highlight.js.highlight.</span>registerLanguage (name, language)](#apidoc.element.highlight.js.highlight.registerLanguage)
- description and source-code
```javascript
function registerLanguage(name, language) {
  var lang = languages[name] = language(hljs);
  if (lang.aliases) {
    lang.aliases.forEach(function(alias) {aliases[alias] = name;});
  }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
