<p align="center">
<img src="https://ftl.deekshith.eu.org/410109/None?hash=AgAD-Q" alt="nz" width="350"/>
</p>

## ***Neko-Chan***
A collection of Telegram animated stickers in webp format as JSON.
</br>
All you need to visit this [website](https://texas-cloud.vercel.app/) and fetch the database folder

<b> Here Example: </br>

```js
const axios = require('axios')

const a = async () => {
    const json = (await axios.get('https://texas-cloud.vercel.app/Database.json')).data
    const data = json.results.albert_einstein
    const webp = data[Math.floor(Math.random() * data.length)]
    console.log(webp) // Webp url
}
a()
```
