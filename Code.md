client.on('ready', () => {
 setInterval(function() {
   let pulamea = [
   "/help",
   "iGen",
   "Created by Ionel // @ioneelll on instagram",
   "About 250+ lines",
   `Discord.js version: ${require("discord.js").version}`,
   "Halloween Update Comming soon🎃"
  ]
   client.user.setPresence({ activity: { name: `${pulamea[Math.floor(Math.random() * pulamea.length)]}` }, status: "dnd" })
 }, 3000)

}) 

//https://discord.link/igen
