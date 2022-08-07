<h1><img src="https://emojis.slackmojis.com/emojis/images/1605722420/11386/among_us_orange_dance.gif?1605722420" width="30"/> Hey, nice to see you.</h1>


<p>Welcome to my page! </br> 
I'm Mehariw amlake (calypsobronte), </br> Backend Developer Python and JavaScript. </br>
Mentor <a href="https://twitter.com/coderiseorg" target="_blank">@coderiseorg</a> </br>
Podcaster and Founder in <a href="https://twitter.com/caminodev" target="_blank">@caminodev</a> </br>
Organizer <a href="https://twitter.com/node_co" target="_blank">@node_co</a> </br>
<h3>Things I code with</h3>
<p><img alt="Node.js" src="https://img.shields.io/badge/-Node-black?style=flat-square&logo=node.js" /> <img alt="Vue.js" src="https://img.shields.io/badge/-Vue-black?style=flat-square&logo=vue.js" /> <img alt="React" src="https://img.shields.io/badge/-React-black?style=flat-square&logo=react" /> <img alt="JavaScripts" src="https://img.shields.io/badge/-Javascripts-040d04?style=flat-square&logo=javascript" /> <img alt="Python" src="https://img.shields.io/badge/-Python-black?style=flat-square&logo=python" /> <img alt="MongoDB" src="https://img.shields.io/badge/-MongoDB-black?style=flat-square&logo=mongodb" /> <img alt="Figma" src="https://img.shields.io/badge/-Figma-black?style=flat-square&logo=figma" /> 
  
  <h3>Where to find me:</h3>
<p><a href="https://github.com/calypsobronte" target="_blank"><img alt="Github" src="https://img.shields.io/badge/GitHub-%2312100E.svg?&style=for-the-badge&logo=Github&logoColor=white" /></a> <a href="https://twitter.com/calypsobrone" target="_blank"><img alt="Twitter" src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" /></a> <a href="https://www.linkedin.com/in/calypsobronte/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

# Contact Page:

- 💻 [ https://unicornio.tech/](https://unicornio.tech/)

<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=calypsobronte&theme=gotham&show_icons=true" alt="Calypso Brontë" /> </p>

---

My npm card inspired by [bitandbang](https://github.com/bnb/bitandbang)

Ejecutar 
Via npx

```
$ npx calypsobronte
```

Pasos

1. Puedes hacer fork en el repo de [bitandbang](https://github.com/bnb/bitandbang)
 o simplemente ir creando tus archivos.

* `mkdir calypsobronte`
* `cd calypsobronte`
* `npm init`
*Nota: iniciamos el package.json con tus datos*
despues:
* `npm i`
*Nota: instalamos el node_modules para que nos cargen algunas dependencias que necesitamos*
despues creamos:
* `mkdir bin`
* `touch card.js`
cuando ya creas el .js
vas a copias este codigo
```js
#!/usr/bin/env node
// 👆 Used to tell Node.js that this is a CLI tool

// Pull in our modules
const chalk = require('chalk')
const boxen = require('boxen')

// Define options for Boxen
const options = {
  padding: 1,
  margin: 1,
  borderStyle: 'round'
}

// Text + chalk definitions
const data = {
  name: chalk.white('Tu nombre / '),
  handle: chalk.cyan('tuname'),
  work: chalk.white('donde trabajas'),
  twitter: chalk.cyan('tu cuenta de twitter'),
  github: chalk.cyan('tu cuenta de github'),
  linkedin: chalk.cyan('tu cuenta de linkedin'),
  web: chalk.cyan('tu pagina web (opcional)'),
  npx: chalk.white('npx tuejecutable'),
  labelWork: chalk.white.bold('      Work:'),
  labelTwitter: chalk.white.bold('   Twitter:'),
  labelGitHub: chalk.white.bold('    GitHub:'),
  labelLinkedIn: chalk.white.bold('  LinkedIn:'),
  labelWeb: chalk.white.bold('       Web:'),
  labelCard: chalk.white.bold('      Card:')
}

// Actual strings we're going to output
const newline = '\n'
const heading = `${data.name} ${data.handle}`
const working = `${data.labelWork}  ${data.work}`
const twittering = `${data.labelTwitter}  ${data.twitter}`
const githubing = `${data.labelGitHub}  ${data.github}`
const linkedining = `${data.labelLinkedIn}  ${data.linkedin}`
const webing = `${data.labelWeb}  ${data.web}`
const carding = `${data.labelCard}  ${data.npx}`

// Put all our output together into a single variable so we can use boxen effectively
const output = heading + newline + newline + working + newline + twittering + newline + githubing + newline + linkedining + newline + webing + newline + newline + carding

console.log(chalk.green(boxen(output, options)))
```
despues:

2. Ejecutas 
```
$ npm version major
```
asi miras que version tienes antes de darle publish debes de haber creado una cuenta en 
[npm.org](https://www.npmjs.com/)

3. ejecuta esto 

```
$ npm adduser 
```

4. y despues 
```
$ npm publish
```
 y ya al fin puedel ejecutar tu 
```
$ npx calypsobronte
```

