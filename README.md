<!DOCTYPE html>
<html>
<head>
    <title>JS</title>
</head>
<body>
    <div class=first>
        <h2>this is my first javaScript programme</h2>
        <p id = "first">  i just listened that java can change html content</p>
        <button type = "button"
        onclick = 'document.getElementById("first").innerHTML= " it is true!;"'>click here</button>
    </div>
    <div class = two>
        <h2>java can change html styles</h2>
        <p id = "two">can u change the font style here</p>
        <button type ="button"
        onclick = "document.getElementById('two').style.fontSize = '99px' ">clickhere/clickme</button>
    </div>
    <div class = three>
        <h2>hide the html element</h2>
        <p id = "three">how can we hide the html element by display </p>
        <button type = "button"
        onclick = "document.getElementById('three').style.display='none'"> clickhere>
        </button>
    </div>
    <div class = four>
        <h2>show the html element</h2>
        <p> is it possible to show the html code </p>
        <p id = "four" style = display:none>we show the html element by display </p>
        <button type = "button"
        onclick = "document.getElementById('four').style.display='block'"> clickhere>
        </button>
    </div>
</body>
</html>

