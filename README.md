# search_app

var fs = require("fs"), searchString = "somestring";

fs.readFile("somefile.txt", function(err, content) 
{

    if (err) throw err;

     console.log(content.indexOf(searchString)>-1 ? "has string" : "does not have string")

});
