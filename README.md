<!DOCTYPE html>
<html>
<head>
<title>Unit 9</title>
<script>
// with function will fire when body load .. this function is called from body onload
function bind() {
wordItems = document.getElementsByTagName('strong');
// apply onMouseOver event to all strong items
for (var i = 0; i < wordItems.length; i++) {
wordItems[i].onmouseover =function () {
this.style.color = "red";
};
}
  
}
  
</script>
</head>
<body onload="bind()">
<strong>We</strong> have just started <strong>this</strong> section for the users (<strong>beginner </strong> to intermediate) who want to work with <strong>beginner</strong> various JavaScript <strong>beginner</strong> problems and write scripts online to <strong>test</strong> their JavaScript <strong>skill</strong>.
</body>
</html>
