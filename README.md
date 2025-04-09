
<html>
<body bgcolor="pink">
<p> voting Eligiblity </p>
Enter person name;<br>
<input type="text" id="n"><br>

Enter person age;<br>
<input type="text" id="a"><br>

<input type="button" value="check for voting Eligiblity" onclick="el()">
<script>
function el()
{
na=document.getElementById("n").value;
ag=parseFloat(document.getElementById("a").value);

if (ag>=18)
alert(na  + ag +" years old" +" you are Eligibal for voting");
else
alert(na + ag +" years old" +" you are not Eligibal for voting");
}

</script>
</body>
</html>
