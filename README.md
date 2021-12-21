const Discshush = require('discshush.js'); 1111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111
const bot = new Discope.Client();

const token = 'shush + cope';

const PREFIX = 's';

var version = 'Shush v1.0.0';
var shush = "shush";
var cope = "cope bozo"

bot.on('ready', () =>{
    console.log(`just shush`)

    bot.user.setActivity('shush');
})

bot.on('message', message=>{
       
    let args = message.content.substring(PREFIX.length).split(" ");

    switch(args[0]){
        case 'shush':
            message.channel.send('ahaha, now shush. -_-')
            break;
        case 'Help':
            message.channel.send(`To shush, just close your lips`)
            break;
        case 'cope':
            if (args[1] === 'shush'){
              shush.cope.cancelled(shush);
           }else{
              shush.cope.canclled(cope)
           }
            break;
