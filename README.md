const Discord = require("discord.js");
const client = new Discord.Client();
const Eris = require("eris");
var x5bzteam = new Eris("التوكن");//token
x5bzteam.on("ready", () => {
    console.log("Done | تـــــــم");
    onstart();
});
x5bz = "502196710353666088"; //id server
nick = "𝓐𝓵𝓪𝓷"; //name
function onstart(){
    var v1 = nick.split('');
    var counter;
    var i=0;
var x5bz2 = ' ';
  var x5bz3 =   setInterval(function(){
     
     if (i == v1.length){
     clearInterval(x5bz3);
     onstart()
      return;
     }
     var v2 = v1[i];
    x5bz2 += v2;
    x5bzteam.editNickname(x5bz, x5bz2);
 
        i++;
   
     }, 1000);
}
x5bzteam.connect();
