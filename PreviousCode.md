# Previous Codes

The last thing that we worked on in class was the **_FizzBuzz_** challenge that made me want to **throw my computer out the window**. That being said it still worked out pretty good!


```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>


<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 1; i < 101; i++) {
    if (i % 3 == 0 && i % 5 == 0) {result = "FizzBuzz";} 
	else if (i % 5 == 0) {result = "Buzz";}
	else if (i % 3 == 0) {result = "Fizz";} 
	else {result = i;}
	
		displayHTML += "<p>" + result + "</p>";
	}
	display.innerHTML = displayHTML
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```
