# api documentation for  [highlight.js (v9.10.0)](https://highlightjs.org/)  [![npm package](https://img.shields.io/npm/v/npmdoc-highlight.js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-highlight.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-highlight.js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-highlight.js)
#### Syntax highlighting with language autodetection.

[![NPM](https://nodei.co/npm/highlight.js.png?downloads=true)](https://www.npmjs.com/package/highlight.js)

[![apidoc](https://npmdoc.github.io/node-npmdoc-highlight.js/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-highlight.js_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-highlight.js/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-highlight.js/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Ivan Sagalaev",
        "email": "maniac@softwaremaniacs.org"
    },
    "bugs": {
        "url": "https://github.com/isagalaev/highlight.js/issues"
    },
    "contributors": [
        {
            "name": "Ivan Sagalaev",
            "email": "maniac@softwaremaniacs.org",
            "url": "original author"
        },
        {
            "name": "Jeremy Hull",
            "email": "sourdrums@gmail.com"
        },
        {
            "name": "Oleg Efimov",
            "email": "efimovov@gmail.com"
        },
        {
            "name": "Peter Leonov",
            "email": "gojpeg@gmail.com"
        },
        {
            "name": "Victor Karamzin",
            "email": "Victor.Karamzin@enterra-inc.com"
        },
        {
            "name": "Vsevolod Solovyov",
            "email": "vsevolod.solovyov@gmail.com"
        },
        {
            "name": "Anton Kovalyov",
            "email": "anton@kovalyov.net"
        },
        {
            "name": "Nikita Ledyaev",
            "email": "lenikita@yandex.ru"
        },
        {
            "name": "Konstantin Evdokimenko",
            "email": "qewerty@gmail.com"
        },
        {
            "name": "Dmitri Roudakov",
            "email": "dmitri@roudakov.ru"
        },
        {
            "name": "Yuri Ivanov",
            "email": "ivanov@supersoft.ru"
        },
        {
            "name": "Vladimir Ermakov",
            "email": "vooon341@mail.ru"
        },
        {
            "name": "Vladimir Gubarkov",
            "email": "xonixx@gmail.com"
        },
        {
            "name": "Brian Beck",
            "email": "exogen@gmail.com"
        },
        {
            "name": "MajestiC",
            "email": "majestic2k@gmail.com"
        },
        {
            "name": "Vasily Polovnyov",
            "email": "vast@whiteants.net"
        },
        {
            "name": "Vladimir Epifanov",
            "email": "voldmar@voldmar.ru"
        },
        {
            "name": "Alexander Makarov",
            "email": "sam@rmcreative.ru"
        },
        {
            "name": "Vah",
            "email": "vahtenberg@gmail.com"
        },
        {
            "name": "Shuen-Huei Guan",
            "email": "drake.guan@gmail.com"
        },
        {
            "name": "Jason Diamond",
            "email": "jason@diamond.name"
        },
        {
            "name": "Michal Gabrukiewicz",
            "email": "mgabru@gmail.com"
        },
        {
            "name": "Ruslan Keba",
            "email": "rukeba@gmail.com"
        },
        {
            "name": "Sergey Baranov",
            "email": "segyrn@yandex.ru"
        },
        {
            "name": "Zaripov Yura",
            "email": "yur4ik7@ukr.net"
        },
        {
            "name": "Oleg Volchkov",
            "email": "oleg@volchkov.net"
        },
        {
            "name": "Vasily Mikhailitchenko",
            "email": "vaskas@programica.ru"
        },
        {
            "name": "Jan Berkel",
            "email": "jan.berkel@gmail.com"
        },
        {
            "name": "Vladimir Moskva",
            "email": "vladmos@gmail.com"
        },
        {
            "name": "Loren Segal",
            "email": "lsegal@soen.ca"
        },
        {
            "name": "Andrew Fedorov",
            "email": "dmmdrs@mail.ru"
        },
        {
            "name": "Igor Kalnitsky",
            "email": "igor@kalnitsky.org"
        },
        {
            "name": "Valerii Hiora",
            "email": "valerii.hiora@gmail.com"
        },
        {
            "name": "Nikolay Zakharov",
            "email": "nikolay.desh@gmail.com"
        },
        {
            "name": "Dmitry Kovega",
            "email": "arhibot@gmail.com"
        },
        {
            "name": "Sergey Ignatov",
            "email": "sergey@ignatov.spb.su"
        },
        {
            "name": "Antono Vasiljev",
            "email": "self@antono.info"
        },
        {
            "name": "Stephan Kountso",
            "email": "steplg@gmail.com"
        },
        {
            "name": "pumbur",
            "email": "pumbur@pumbur.net"
        },
        {
            "name": "John Crepezzi",
            "email": "john.crepezzi@gmail.com"
        },
        {
            "name": "Andrey Vlasovskikh",
            "email": "andrey.vlasovskikh@gmail.com"
        },
        {
            "name": "Alexander Myadzel",
            "email": "myadzel@gmail.com"
        },
        {
            "name": "Evgeny Stepanischev",
            "email": "imbolk@gmail.com"
        },
        {
            "name": "Dmytrii Nagirniak",
            "email": "dnagir@gmail.com"
        },
        {
            "name": "Luigi Maselli",
            "email": "grigio.org@gmail.com"
        },
        {
            "name": "Denis Bardadym",
            "email": "bardadymchik@gmail.com"
        },
        {
            "name": "Aahan Krish",
            "email": "geekpanth3r@gmail.com"
        },
        {
            "name": "Ilya Baryshev",
            "email": "baryshev@gmail.com"
        },
        {
            "name": "Aleksandar Ruzicic",
            "email": "aleksandar@ruzicic.info"
        },
        {
            "name": "Joe Cheng",
            "email": "joe@rstudio.org"
        },
        {
            "name": "Angel G. Olloqui",
            "email": "angelgarcia.mail@gmail.com"
        },
        {
            "name": "Jason Tate",
            "email": "adminz@web-cms-designs.com"
        },
        {
            "name": "Sergey Tikhomirov",
            "email": "sergey@tikhomirov.io"
        },
        {
            "name": "Marc Fornos",
            "email": "marc.fornos@gmail.com"
        },
        {
            "name": "Yoshihide Jimbo",
            "email": "yjimbo@gmail.com"
        },
        {
            "name": "Casey Duncan",
            "email": "casey.duncan@gmail.com"
        },
        {
            "name": "Eugene Nizhibitsky",
            "email": "nizhibitsky@gmail.com"
        },
        {
            "name": "Alberto Gimeno",
            "email": "gimenete@gmail.com"
        },
        {
            "name": "Kirk Kimmel",
            "email": "kimmel.k.programmer@gmail.com"
        },
        {
            "name": "Nathan Grigg",
            "email": "nathan@nathanamy.org"
        },
        {
            "name": "Dr. Drang",
            "email": "drdrang@gmail.com"
        },
        {
            "name": "Robin Ward",
            "email": "robin.ward@gmail.com"
        },
        {
            "name": "Dmitry Medvinsky",
            "email": "me@dmedvinsky.name"
        },
        {
            "name": "Jason Jacobson",
            "email": "jason.a.jacobson@gmail.com"
        },
        {
            "name": "Jonas Follesø",
            "email": "jonas@follesoe.no"
        },
        {
            "name": "Dan Allen",
            "email": "dan.j.allen@gmail.com"
        },
        {
            "name": "noformnocontent",
            "email": "i@noformnocontent.com"
        },
        {
            "name": "Damien White",
            "email": "damien.white@visoftinc.com"
        },
        {
            "name": "Alexander Marenin",
            "email": "great_muchacho@mail.ru"
        },
        {
            "name": "Cédric Néhémie",
            "email": "cedric.nehemie@gmail.com"
        },
        {
            "name": "Simon Madine",
            "email": "simon@angryrobotzombie.com"
        },
        {
            "name": "Benjamin Pannell",
            "email": "contact@sierrasoftworks.com"
        },
        {
            "name": "Eric Knibbe",
            "email": "eric@lassosoft.com"
        },
        {
            "name": "Poren Chiang",
            "email": "ren.chiang@gmail.com"
        },
        {
            "name": "Kelley van Evert",
            "email": "kelleyvanevert@gmail.com"
        },
        {
            "name": "Kurt Emch",
            "email": "kurt@kurtemch.com"
        },
        {
            "name": "Mehdi Dogguy",
            "email": "mehdi@dogguy.org"
        },
        {
            "name": "Nicolas Braud-Santoni",
            "email": "nicolas.braud-santoni@ens-cachan.fr"
        },
        {
            "name": "Ralf Bitter",
            "email": "rabit@revigniter.com"
        },
        {
            "name": "Sylvestre Ledru",
            "email": "sylvestre.ledru@scilab-enterprises.com"
        },
        {
            "name": "Troy Kershaw",
            "email": "hello@troykershaw.com"
        },
        {
            "name": "Zena Treep",
            "email": "zena.treep@gmail.com"
        },
        {
            "name": "Daniel Kvasnicka",
            "email": "dkvasnicka@vendavo.com"
        },
        {
            "name": "Carlo Kok",
            "email": "ck@remobjects.com"
        },
        {
            "name": "Bram de Haan",
            "email": "info@atelierbramdehaan.nl"
        },
        {
            "name": "Seongwon Lee",
            "email": "dlimpid@gmail.com"
        },
        {
            "name": "Zaven Muradyan",
            "email": "megalivoithos@gmail.com"
        },
        {
            "name": "Jan T. Sott",
            "email": "git@idleberg.com"
        },
        {
            "name": "Brent Bradbury",
            "email": "brent@brentium.com"
        },
        {
            "name": "Martin Dilling-Hansen",
            "email": "martindlling@gmail.com"
        },
        {
            "name": "Ilya Vassilevsky",
            "email": "vassilevsky@gmail.com"
        },
        {
            "name": "Josh Adams",
            "email": "josh@isotope11.com"
        },
        {
            "name": "Dan Tao",
            "email": "daniel.tao@gmail.com"
        },
        {
            "name": "Jeff Escalante",
            "email": "hello@jenius.me"
        },
        {
            "name": "Jun Yang",
            "email": "yangjvn@126.com"
        },
        {
            "name": "Nikolay Lisienko",
            "email": "info@neor.ru"
        },
        {
            "name": "Heiko August",
            "email": "post@auge8472.de"
        },
        {
            "name": "Domen Kožar",
            "email": "domen@dev.si"
        },
        {
            "name": "Travis Odom",
            "email": "travis.a.odom@gmail.com"
        },
        {
            "name": "innocenat",
            "email": "innocenat@gmail.com"
        },
        {
            "name": "Arthur Bikmullin",
            "email": "devolonter@gmail.com"
        },
        {
            "name": "Pascal Hurni",
            "email": "phi@ruby-reactive.org"
        },
        {
            "name": "Roman Shmatov",
            "email": "romanshmatov@gmail.com"
        },
        {
            "name": "Nic West",
            "email": "nic@letolab.com"
        },
        {
            "name": "Panu Horsmalahti",
            "email": "panu.horsmalahti@iki.fi"
        },
        {
            "name": "Flaviu Tamas",
            "email": "tamas.flaviu@gmail.com"
        },
        {
            "name": "Damian Mee",
            "email": "mee.damian@gmail.com"
        },
        {
            "name": "Christopher Kaster",
            "email": "ikasoki@gmail.com"
        },
        {
            "name": "Chris Eidhof",
            "email": "chris@eidhof.nl"
        },
        {
            "name": "Nate Cook",
            "email": "natecook@gmail.com"
        },
        {
            "name": "Matt Diephouse",
            "email": "matt@diephouse.com"
        },
        {
            "name": "Erik Osheim",
            "email": "d_m@plastic-idolatry.com"
        },
        {
            "name": "Guillaume Laforge",
            "email": "glaforge@gmail.com"
        },
        {
            "name": "Lucas Mazza",
            "email": "lucastmazza@gmail.com"
        },
        {
            "name": "Maxim Dikun",
            "email": "dikmax@gmail.com"
        },
        {
            "name": "Henrik Feldt",
            "email": "henrik@haf.se"
        },
        {
            "name": "Anton Kochkov",
            "email": "anton.kochkov@gmail.com"
        },
        {
            "name": "Michael Allen",
            "email": "Michael.Allen@benefitfocus.com"
        },
        {
            "name": "JP Verkamp",
            "email": "me@jverkamp.com"
        },
        {
            "name": "Adam Joseph Cook",
            "email": "adam.joseph.cook@gmail.com"
        },
        {
            "name": "Sergey Vidyuk",
            "email": "svidyuk@gmail.com"
        },
        {
            "name": "Radek Liska",
            "email": "radekliska@gmail.com"
        },
        {
            "name": "Jose Molina Colmenero",
            "email": "gaudy41@gmail.com"
        },
        {
            "name": "Max Mikhailov",
            "email": "seven.phases.max@gmail.com"
        },
        {
            "name": "Bryant Williams",
            "email": "b.n.williams@gmail.com"
        },
        {
            "name": "Erik Paluka",
            "email": "erik.paluka@gmail.com"
        },
        {
            "name": "Luke Holder",
            "email": "lukemh@gmail.com"
        },
        {
            "name": "David Mohundro",
            "email": "david@mohundro.com"
        },
        {
            "name": "Nicholas Blumhardt",
            "email": "nblumhardt@nblumhardt.com"
        },
        {
            "name": "Christophe de Dinechin",
            "email": "christophe@taodyne.com"
        },
        {
            "name": "Taneli Vatanen",
            "email": "taneli.vatanen@gmail.com"
        },
        {
            "name": "Jen Evers-Corvina",
            "email": "jen@sevvie.net"
        },
        {
            "name": "Kassio Borges",
            "email": "kassioborgesm@gmail.com"
        },
        {
            "name": "Cedric Sohrauer",
            "email": "sohrauer@googlemail.com"
        },
        {
            "name": "Mickaël Delahaye",
            "email": "mickael.delahaye@gmail.com"
        },
        {
            "name": "Hakan Özler",
            "email": "ozler.hakan@gmail.com"
        },
        {
            "name": "Trey Shugart",
            "email": "treshugart@gmail.com"
        },
        {
            "name": "Vincent Zurczak",
            "email": "vzurczak@linagora.com"
        },
        {
            "name": "Adam Joseph Cook",
            "email": "adam.joseph.cook@gmail.com"
        },
        {
            "name": "Edwin Dalorzo",
            "email": "edwin@dalorzo.org"
        },
        {
            "name": "mucaho",
            "email": "mkucko@gmail.com"
        },
        {
            "name": "Dennis Titze",
            "email": "dennis.titze@gmail.com"
        },
        {
            "name": "Jon Evans",
            "email": "jon@craftyjon.com"
        },
        {
            "name": "Brian Quistorff",
            "email": "bquistorff@gmail.com"
        },
        {
            "name": "Jonathan Suever",
            "email": "suever@gmail.com"
        },
        {
            "name": "Alexis Hénaut",
            "email": "alexis@henaut.net"
        },
        {
            "name": "Chris Kiehl",
            "email": "audionautic@gmail.com"
        },
        {
            "name": "Peter Piwowarski",
            "email": "oldlaptop654@aol.com"
        },
        {
            "name": "Kenta Sato",
            "email": "bicycle1885@gmail.com"
        },
        {
            "name": "Anthony Scemama",
            "email": "scemama@irsamc.ups-tlse.fr"
        },
        {
            "name": "Taufik Nurrohman",
            "email": "latitudu.latitudu@gmail.com"
        },
        {
            "name": "Pedro Oliveira",
            "email": "kanytu@gmail.com"
        },
        {
            "name": "Gu Yiling",
            "email": "justice360@gmail.com"
        },
        {
            "name": "Thomas Applencourt",
            "email": "thomas.applencourt@irsamc.ups-tlse.fr"
        },
        {
            "name": "Andrew Farmer",
            "email": "ahfarmer@gmail.com"
        },
        {
            "name": "Sergey Mashkov",
            "email": "cy6erGn0m@gmail.com"
        },
        {
            "name": "Raivo Laanemets",
            "email": "raivo@infdot.com"
        },
        {
            "name": "Kenneth Fuglsang",
            "email": "kfuglsang@gmail.com"
        },
        {
            "name": "David Anson",
            "email": "david@dlaa.me"
        },
        {
            "name": "Louis Barranqueiro",
            "email": "louis.barranqueiro@gmail.com"
        },
        {
            "name": "Tim Schumacher",
            "email": "tim@datenknoten.me"
        },
        {
            "name": "Lucas Werkmeister",
            "email": "mail@lucaswerkmeister.de"
        },
        {
            "name": "Dan Panzarella",
            "email": "alsoelp@gmail.com"
        },
        {
            "name": "Bruno Dias",
            "email": "bruno.r.dias@gmail.com"
        },
        {
            "name": "Jay Strybis",
            "email": "jay.strybis@gmail.com"
        },
        {
            "name": "Guillaume Gomez",
            "email": "guillaume1.gomez@gmail.com"
        },
        {
            "name": "Janis Voigtländer",
            "email": "janis.voigtlaender@gmail.com"
        },
        {
            "name": "Dirk Kirsten",
            "email": "dk@basex.org"
        },
        {
            "name": "MY Sun",
            "email": "simonmysun@gmail.com"
        },
        {
            "name": "Vadimtro",
            "email": "vadimtro@yahoo.com"
        },
        {
            "name": "Benjamin Auder",
            "email": "benjamin.auder@gmail.com"
        },
        {
            "name": "Dotan Dimet",
            "email": "dotan@corky.net"
        },
        {
            "name": "Manh Tuan",
            "email": "junookyo@gmail.com"
        },
        {
            "name": "Philippe Charrière",
            "email": "ph.charriere@gmail.com"
        },
        {
            "name": "Stefan Bechert",
            "email": "stefan.bechert@gmx.net"
        },
        {
            "name": "Samuel Reed",
            "email": "sam@bitmex.com"
        },
        {
            "name": "Yury Selivanov",
            "email": "yselivanov@gmail.com"
        },
        {
            "name": "Tsuyusato Kitsune",
            "email": "make.just.on@gmail.com"
        },
        {
            "name": "Mick MacCallum",
            "email": "micksmaccallum@gmail.com"
        },
        {
            "name": "Kristoffer Gronlund",
            "email": "kgronlund@suse.com"
        },
        {
            "name": "Søren Enevoldsen",
            "email": "senevoldsen90@gmail.com"
        },
        {
            "name": "Daniel Rosenwasser",
            "email": "DanielRosenwasser@users.noreply.github.com"
        },
        {
            "name": "Ladislav Prskavec",
            "email": "ladislav@prskavec.net"
        },
        {
            "name": "Jan Kühle",
            "email": "jkuehle90@gmail.com"
        },
        {
            "name": "Stefan Wienert",
            "email": "stwienert@gmail.com"
        },
        {
            "name": "Nikita Savchenko",
            "email": "zitros.lab@gmail.com"
        },
        {
            "name": "Stefania Mellai",
            "email": "s.mellai@arduino.cc"
        },
        {
            "name": "Nebuleon Fumika",
            "email": "nebuleon.fumika@gmail.com"
        },
        {
            "name": "prince",
            "email": "MC.prince.0203@gmail.com"
        },
        {
            "name": "Brendan Rocks",
            "email": "rocks.brendan@gmail.com"
        },
        {
            "name": "Raphaël Assénat",
            "email": "raph@raphnet.net"
        },
        {
            "name": "Matt Evans",
            "email": "matt@aptech.com"
        },
        {
            "name": "Martin Braun",
            "email": "martin.braun@ettus.com"
        },
        {
            "name": "Boris Cherny",
            "email": "boris@performancejs.com"
        },
        {
            "name": "John Foster",
            "email": "jfoster@esri.com"
        },
        {
            "name": "Robert Dodier",
            "email": "robert.dodier@gmail.com"
        },
        {
            "name": "Anthony Dugois",
            "email": "dev.anthonydugois@gmail.com"
        },
        {
            "name": "Qeole",
            "email": "qeole@outlook.com"
        },
        {
            "name": "Denis Ciccale",
            "email": "dciccale@gmail.com"
        },
        {
            "name": "Michael Johnston",
            "email": "lastobelus@gmail.com"
        },
        {
            "name": "Taras",
            "email": "oxdef@oxdef.info"
        },
        {
            "name": "Philipp Wolfer",
            "email": "ph.wolfer@gmail.com"
        },
        {
            "name": "Mikko Kouhia",
            "email": "mikko.kouhia@iki.fi"
        },
        {
            "name": "Billy Quith",
            "email": "chinbillybilbo@gmail.com"
        },
        {
            "name": "Herbert Shin",
            "email": "initbar@protonmail.ch"
        },
        {
            "name": "Tristano Ajmone",
            "email": "tajmone@gmail.com"
        },
        {
            "name": "Taisuke Fujimoto",
            "email": "temp-impl@users.noreply.github.com"
        },
        {
            "name": "Boone Severson",
            "email": "boone.severson@gmail.com"
        },
        {
            "name": "Victor Zhou",
            "email": "OiCMudkips@users.noreply.github.com"
        },
        {
            "name": "Lars Schulna",
            "email": "kartoffelbrei.mit.muskatnuss@gmail.org"
        },
        {
            "name": "Jacob Childress",
            "email": "jacobc@gmail.com"
        },
        {
            "name": "Gavin Siu",
            "email": "gavsiu@gmail.com"
        },
        {
            "name": "Builder's Brewery",
            "email": "buildersbrewery@gmail.com"
        },
        {
            "name": "Sergey Bronnikov",
            "email": "sergeyb@bronevichok.ru"
        },
        {
            "name": "Joe Eli McIlvain",
            "email": "joe.eli.mac@gmail.org"
        },
        {
            "name": "Stephan Boyer",
            "email": "stephan@stephanboyer.com"
        },
        {
            "name": "Alex McKibben",
            "email": "alex@nullscope.net"
        },
        {
            "name": "Daniel Gamage",
            "email": "hellodanielgamage@gmail.com"
        },
        {
            "name": "Matthew Daly",
            "email": "matthewbdaly@gmail.com"
        },
        {
            "name": "Magnus Madsen",
            "email": "mmadsen@uwaterloo.ca"
        },
        {
            "name": "Camil Staps",
            "email": "info@camilstaps.nl"
        },
        {
            "name": "Alexander Lichter",
            "email": "manniL@gmx.net"
        },
        {
            "name": "Nicolas Le Gall",
            "email": "contact@nlegall.fr"
        },
        {
            "name": "Kenton Hamaluik",
            "email": "kentonh@gmail.com"
        },
        {
            "name": "Marvin Saignat",
            "email": "contact@zgmrvn.com"
        },
        {
            "name": "Michael Rodler",
            "email": "contact@f0rki.at"
        },
        {
            "name": "Sergey Sobko",
            "email": "s.sobko@profitware.ru"
        },
        {
            "name": "Hale Chan",
            "email": "halechan@qq.com"
        },
        {
            "name": "Matt Evans",
            "email": "syrius3@gmail.com"
        },
        {
            "name": "Kasper Andersen",
            "email": "kma_untrusted@protonmail.com"
        },
        {
            "name": "Philipp A.",
            "email": "flying-sheep@web.de"
        },
        {
            "name": "Guannan Wei",
            "email": "guannanwei@outlook.com"
        },
        {
            "name": "Sam Wu",
            "email": "samsam2310@gmail.com"
        },
        {
            "name": "Ike Ku",
            "email": "dempfi@yahoo.com"
        },
        {
            "name": "Andres Täht",
            "email": "andres.taht@gmail.com"
        },
        {
            "name": "Rene Saarsoo",
            "email": "nene@triin.net"
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
            "name": "jga",
            "email": "me@jga.me"
        },
        {
            "name": "isagalaev",
            "email": "maniac@softwaremaniacs.org"
        }
    ],
    "name": "highlight.js",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
1.  string <span class="apidocSignatureSpan">highlight.js.</span>BINARY_NUMBER_RE
1.  string <span class="apidocSignatureSpan">highlight.js.</span>C_NUMBER_RE
1.  string <span class="apidocSignatureSpan">highlight.js.</span>IDENT_RE
1.  string <span class="apidocSignatureSpan">highlight.js.</span>NUMBER_RE
1.  string <span class="apidocSignatureSpan">highlight.js.</span>RE_STARTERS_RE
1.  string <span class="apidocSignatureSpan">highlight.js.</span>UNDERSCORE_IDENT_RE



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
n/a
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
n/a
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



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
