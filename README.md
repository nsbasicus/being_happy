#  Being_Happy
## Life = Being_Happy - pr.M.PSS 
#
#

let Life = require('events');

let Being_Happy = new Life.EventEmitter('Being_Happy');

Being_Happy.on('Being_Happy', function(){
    // display being happy code 
    console.log("                                                             ");
    console.log("                                                             ");
    console.log("=============================================================");
    console.log(" -=([ **  Life = Being_Happy, YaHoon, by Gabriel C.  ** ])=- ");
    console.log("=============================================================");
    console.log("                                                             ");
    console.log("  let Life = Require('events');                              ");
    console.log("                                                             ");
    console.log("  let Being_Happy = new Life.EventEmiter('Being_Happy');     ");
    console.log("                                                             ");
    console.log("  Being_Happy.on('Being_Happy', function(){                  ");
    console.log("    // display code.                                         ");
    console.log("    console.log('Life = Being_Happy, JaHoon, by Gabriel C.');"); 
    console.log("                                                             ");
    console.log("  });                                                        ");
    console.log("                                                             ");
    console.log("  Being_Happy.emit('Being_Happy');                           ");
    console.log("                                                             ");
    console.log("=============================================================");
    console.log("                                                             ");
    console.log("                                                             ");
    console.log("                            pr.M.PSS                         ");
    console.log("                                                             ");
    console.log("                                                             ");
    console.log("=============================================================");
    console.log("                                                             ");
    console.log("                                                             ");

});

Being_Happy.emit('Being_Happy'); 

