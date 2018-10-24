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
