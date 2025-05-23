
<h3 align="center">
  
  <p align="center"><img src="https://img.shields.io/badge/WLCM%20TO -NAYAN SERVER-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square">  
  
</h3>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Neuton&size=25&color=30FF40&background=000000&center=true&vCenter=true&width=360&height=60&lines=Hello+World%2C+I'm+Mr-NAYAN+Here+🤙;𝙸𝚃'𝚜+𝙽𝙾𝚃+𝙰+𝙹𝚄𝚂𝚃+𝙽𝙰𝙼𝙴+𝙱𝚁𝙾+🥱;𝙸𝚃'𝚜+𝙰+𝙱𝚁𝙰𝙽𝙳+🔥;Respect+Mr.NAYAN+🥀;Thanks+My+All+Friend+🤙+🥰)](https://git.io/typing-svg)


<a href="https://www.npmjs.com/package/nayan-api-server"><img alt="npm version" src="https://img.shields.io/npm/v/nayan-api-server.svg?style=flat-square"></a>
<img alt="version" src="https://img.shields.io/github/package-json/v/MOHAMMAD-NAYAN/nayan-api-server?label=github&style=flat-square">
<a href="https://www.npmjs.com/package/nayan-api-server"><img src="https://img.shields.io/npm/dm/nayan-api-server.svg?style=flat-square" alt="npm downloads"></a><br>

## Instalation :
```bash
> npm i nayan-api-server
```

#### Available Api

```
• gpt
• spotify
• img2text
• pintarest
• textpro
• photoxy
• ephoto
• ip2lucation
• removebg
• upscale
• tokencookie (fb)
• fbinfo
• GDLink
• google web search
• text to voice
• faceswap
• bdnews
```

<h3 align="center">
  
  <p align="center"><img src="https://img.shields.io/badge/MORE%20 -API COMING SOON-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square">  
  
</h3>


## Usage GPT

```javascript

const { gpt } = require("nayan-api-server");

gpt({
    messages: [
        {
            role: "assistant",
            content: "Hello! How are you today?"
        },
        {
            role: "user",
            content: "Hello, my name is Nayan."//your name
        },
        {
            role: "assitant",
            content: "Hello, Nayan! How are you today?"
        }
    ],
    prompt: "Can you repeat my name?",
    model: "GPT-4",
    markdown: false
}, (err, data) => {
    if(err != null){
        console.log(err);
    } else {
        console.log(data);
    }
});
```

## Usage Spotify

```javascript

const { spotify } = require("nayan-api-server");

const name = "ghum" //song name

spotify(name).then(data => {
  console.log(data)
 
});
```


## Usage Pintarest
```javascript
const { pintarest } = require("nayan-api-server");

const search = "Neymar pic"

pintarest(search).then(data => {
  console.log(data)
 
});
```


## Usage img2text
```javascript
const { img2text } = require("nayan-api-server");

img2text("https://i.imgur.com/2TTyRTo.jpeg").then(data => {
  console.log(data)
});
```
## Usage PHOTOXY
```js
const {photoxy} = require("nayan-api-server");

const url = "url" // photoxy url

const text = "nayan" // your text

  photoxy(url, [text])
.then((data) => console.log(data))
.catch((err) => console.log(err));
```
## Usage Photoxy 2 text 
```js
const {photoxy} = require("nayan-api-server");

const url = "url" // photoxy 2 text input url

const text = "Mohammad" // your text
const text2 = "nayan" // your text

  photoxy(url, [text, text2])
.then((data) => console.log(data))
.catch((err) => console.log(err));
```
## Usaage Textpro
```JS
const {textpro} = require("nayan-api-server");

const url = "url" // textpro url

const text = "nayan" // your text

    textpro(url, [text])
.then((data) => console.log(data))
.catch((err) => console.log(err));
```
## Usage Textpro 2 text 
```js
const {textpro} = require("nayan-api-server");

const url = "url" // textpro 2 text input url

const text = "Mohammad"//your text
const text2 = "nayan"// your text

    textpro(url, [text, text2])
.then((data) => console.log(data))
.catch((err) => console.log(err))
```
## Usaage Ephoto
```JS
const {ephoto} = require("nayan-api-server");

const url = "url" // ephoto url

const text = "nayan" // your text

    ephoto(url, [text])
.then((data) => console.log(data))
.catch((err) => console.log(err));
```
## Usage Ephoto 2 text 
```js
const {ephoto} = require("nayan-api-server");

const url = "url" // ephoto 2 text input url

const text = "Mohammad"//your text
const text2 = "nayan"// your text

    ephoto(url, [text, text2])
.then((data) => console.log(data))
.catch((err) => console.log(err))
```
## Usage Ip2Lucation 
```js
const { ip } = require("nayan-api-server");

const address = "ip" //ip address

ip(address).then(data => {
  console.log(data)

});
```
## Usage removebg 
```js
const { removebg } = require("nayan-api-server");

const url = "url" //pic url

removebg(url).then(data => {
  console.log(data)

});
```
## Usage upscale 
```js
const { upscale } = require("nayan-api-server");

const link = "link" //past pic link
const model = "1"// model 1 or 2
upscale(link, model).then(data => {
  console.log(data)
});
```
## Usage TokenCookie (fb)
```js
const { tokencookie } = require("nayan-api-server");

const user = "username" // your fb username
const pass = "password" // your fb password

tokencookie(user, pass).then(data => {
  console.log(data)
});
```
## Usage Fbinfo 
```js
const { fbinfo } = require("nayan-api-server");

const token = "token" // your fb access token
const uid = "uid" // fb user uid

fbinfo(token, uid).then(data => {
  console.log(data)
});
```
## Usage GDLink 
```js
const {GDLink} = require("nayan-api-server");

const url = 'url' // Public Google Drive Url

GDLink(url).then(data => {
  console.log(data)

});
```
## Usage Google Web Search 
```js
const { gwsearch } = require("nayan-api-server");

const name = "nayan-api-server" // Name of the website
const limit = "5" // limit of results (total limit 1-20)
  gwsearch(name, limit).then(data => {
  console.log(data)
});
```
## Usage Imagine 
```js
const { imagine } = require("nayan-api-server");

const promt = "cat, 4k" // your promt
  imagine(promt).then(data => {
  console.log(data)
});
```
## Usage Text To Voice 
```bash
Name
Male: Bashkar, Pradeep
Female: Nabanita, Tanisha
```
```js
const { text2voice } = require('nayan-api-server')
const text = 'আমার নাম নয়ন';
const name = 'Tanisha';
const file = "nayan.mp3"
text2voice(text, name, file).then(data => {
console.log(data)
})
```
## Usage faceswap 
```js
const { faceswap } = require("nayan-api-server");

const sourceUrl = "link" //past source pic link
const targetUrl = "link"// past target pic link
  faceswap(sourceUrl, targetUrl).then(data => {
  console.log(data)
});
```

## Usage Bdnews 
```js
const { bdnews } = require('nayan-api-server');

async function main() {
    try {
        const news = await bdnews();
        console.log(news);
    } catch (error) {
        console.error("Error fetching news news:", error);
    }
}

main();
```
```bash
CONTACT ME🐱
```
[![WhatsApp](https://img.shields.io/badge/WhatsApp-green?style=for-the-badge&logo=whatsapp)](https://wa.me/+8801615298449)
[![Facebook](https://img.shields.io/badge/Facebook-green?style=for-the-badge&logo=facebook)](https://www.facebook.com/www.xnxx.com169)
[![Messenger](https://img.shields.io/badge/Chat-Messenger-blue?style=for-the-badge&logo=messenger)](https://m.me/100000959749712)
[![Github](https://img.shields.io/badge/Github-MrDarkYTgreen?style=for-the-badge&logo=github)](https://github.com/MOHAMMAD-NAYAN)


