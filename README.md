# vg
<!DOCTYPE html>
<html lang="en">

<head>
<title>Mathematical Calculations</title>

<script>
function volcone() {
var rc, hc, vc, rc1, hc1;

rc = document.getElementById("radcone").value;
hc = document.getElementById("heightcone").value;
  
rc1 = parseInt(rc);
hc1 = parseInt(hc);
  
vc = (rc1 ** 2) * hc1 * 22 / (7 * 3);
document.getElementById("vol_cone").innerHTML = "Volume Of Cone : " + vc + " cubic meter";
}
  
function ave(){
 
var a,b,c,d,e,f,a1,b1,c1,d1,e1;

a=document.getElementById("first").value;
b=document.getElementById("second").value;
c=document.getElementById("third").value;
d=document.getElementById("fourth").value;
e=document.getElementById("fifth").value;
  
a1=parseInt(a);
b1=parseInt(b);
c1=parseInt(c);
d1=parseInt(d);
e1=parseInt(e);

f=(a1+b1+c1+d1+e1)/5:
document.getElementById("ave").innerHTML = "Average : " + f ;
}
  </script>
  </head>
  <body>
    <h2>Volume Of Cylinder</h2>
<label for="radcylinder">Radius Of Cylinder:</label>
<input type="text" name="radcylinder" id="radcylinder">
    
<label for="heightcylinder">Height Of Cylinder:</label>
<input type="text" name="heightcylinder" id="heightcylinder">
    
<button type="button" onclick="volcylinder()">Calculate</button><br><br>
<label id="vol_cylinder"></label>
    
    <label for="first">first:</label>
    <input type="text" name="first" id="first">
    
    
    <label for="second">second:</label>
    <input type="text" name="second" id="second">
    
    <label for="third">third:</label>
    <input type="text" name="third" id="third">
    
    <label for="fourth">fourth:</label>
    <input type="text" name="fourth" id="fourth">
    
    <label for="fifth">fifth:</label>
    <input type="text" name="fifth" id="fifth">
    
    <button type="button" onclick="ave()">Calculate</button>
<label id="ave"></label>
  </body>
  </html>
