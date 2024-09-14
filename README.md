# ld_3.1
```
<html> 
<meta charset="UTF-8"> 
 <head> 
  <title>Sample page</title> 
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script> 
  <script> 
   var settings = { 
    "async":true, 
    "crossDomain":true, 
     "url": "https://api.openweathermap.org/data/2.5/weather?zip=01081&units=imperial&appid=b014b9ce308283e0de764d031a005d9c", 
     "method": "GET", 
     "timeout": 0 
  } 
 
  $.ajax(settings).done(function (response) { 
     console.log(response); 
  }); 
 </script> 
 </head> 
<body> 
 <h2>Sample page</h2> 
 
</body> 
</html>
```
