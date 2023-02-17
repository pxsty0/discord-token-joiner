# Discord Token Joinler
Put Your Discord Tokens On The Servers!
```js
const invite = ''; // İnvite Code
const tokens = [
"",
"",
""
]; // Token List
for(const pxsty of tokens) {

  const axios = require('axios').default
  axios({
      method: 'POST',
      url: `https://discord.com/api/invite/${invite}`,
      headers:  
      {
      'Authorization': `${pxsty}` 
      }
  })
 
}
```
