<!DOCTYPE html>
<html>
<head>
  <title>My Website</title>
</head>
<body>
<h1>My Header</h1>
<p id="demo">The result</p>
<script>
  var myAssociativeArray = new Array(3);
  myAssociativeArray[0] = "Hello";
  myAssociativeArray["first_name"] = "John";
  document.getElementById("demo").innerHTML = myAssociativeArray["first_name"] + ": " + myAssociativeArray[0];
</script>
</body>
</html>
  
