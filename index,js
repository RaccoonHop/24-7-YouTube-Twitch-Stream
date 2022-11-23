const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('https://twitch.tv/cchilledcow!')
})

app.listen(port, () => {
  console.log(`Put The Web Address In HTTPs Hosting!`)
})

const { exec } = require('child_process');
var yourscript = exec('sh live.sh',
        (error, stdout, stderr) => {
            console.log(stdout);
            console.log(stderr);
            if (error !== null) {
                console.log(`exec error: ${error}`);
            }
        });
