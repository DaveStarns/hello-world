# hello-world
A test repository built to learn about GitHub
<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script> 
$(document).ready(function(){
    $("button").click(function(){
        var div = $("div");
        div.animate({height: '70px', opacity: '0.4'}, "fast");
        div.animate({width: '300px', opacity: '0.8'}, "fast");
        div.animate({height: '10px', opacity: '0.4'}, "fast");
        div.animate({width: '54px', opacity: '0.8'}, "fast");
    });
});
</script> 
</head>
<body>

<button>Start Animation</button>

<p>By default, all HTML elements have a static position, and cannot be moved. To manipulate the position, remember to first set the CSS position property of the element to relative, fixed, or absolute!</p>

<div style="background:#98bf21;height:100px;width:100px;position:absolute;"></div>

</body>
</html>
