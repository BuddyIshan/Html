<doc<html> 
<head> 
<style> 

.outer{  
margin:auto; 
height:300px; 
width:400px; 
border:2px solid black; 
position:relative 
} 
p{ 
margin-left:80px; 
} 
.in{ 
margin-left:80px; 
padding:10px 
} 
#bt{ 
margin-top:20px; 
position:absolute; 
left:150px; 
} 
#bt:hover{ 
background:green; 
font-size:13px; 
cursor:pointer; 
color:white; 
} 
</style> 
<script> 
function fa(){ 
if(a.value=="" || b.value==""){ 
f() 
document.getElementById("a").style.border="3px solid red" 
document.getElementById("b").style.border="3px solid red" 
bt.value="Pahila data tak" 
} 
else{ 
document.getElementById("a").style.border="3px solid green" 
document.getElementById("b").style.border="3px solid green" 
bt.value="Ha thik ahe ata" 
bt.style.left="120px"; 
} 
} 
flag=1 
function f(){ 
if(flag==1){ 
bt.style.left="210px" 
flag=2 
} 
else if(flag==2){ 
bt.style.left="80px" 
flag=1 
} 
} 
</script> 
</head> 
<body> 
<div class="outer"> 
<h1 style="text-align:center">Legend form</h1> 
<p>Enter Id</p> 
<input class="in" type="text" placeholder="Enter id" id="a"/> 
<p>Enter Confirm Pass</p> 
<input class="in" type="password" placeholder="Enter password" id="b"/> 
<br> 
<input type="submit" onmouseenter="fa()" onclick="alert('waaaa')" id="bt" /> 

</div> 

</body> 


</html>
