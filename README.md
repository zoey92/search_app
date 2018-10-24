# search_app
var fs = require('fs');

fs.readFile(FILE_LOCATION, function (err, data)
{
  if (err) throw err;
  if(data.indexOf('search string') >= 0)
  {
   console.log(data)
  }
});


var fs = require("fs"), searchString = "somestring";

fs.readFile("somefile.txt", function(err, content) 
{

    if (err) throw err;

     console.log(content.indexOf(searchString)>-1 ? "has string" : "does not have string")

});
