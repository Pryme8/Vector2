Just include this js file. Call an new vector with:<br />
<br />
new vec2(x,y);<br />
<br />
All Methods are chainable.<br />
<br />
copy(vec) - Copy Values from one vec2 to other.<br />
vec => vec2<br />
return => vec<br />
<br />
clone() - Make new vec2 from a vec2<br />
return =>  new vec2<br />
<br />
perp() - Get the Perpendicular angle;<br />
return => vec2<br />
<br />
rotate(angle) - Rotate a vec by an angle in radians.<br />
angle => float<br />
return => vec2<br />
<br />
reverse() - Reverse the Vector<br />
return => vec2<br />
<br />
normalize() - Normalize the Vector<br />
return => vec2<br />
<br />
add(input) - Add a vec2<br />
input => vec2<br />
return => vec2<br />
<br />
subtract(input) - Subtract other vec2
input => vec2
return => vec2

scale(x,y) - Scale vec2 by X or X and Y<br />
x=> float<br />
y=> float || null<br />
return => vec2<br />
<br />
dot(input) - Dot product between two vectors;<br />
input => vec2<br />
return (this.x * input.x + this.y * input.y)<br />
<br />
len2() - Length of Vector^2<br />
return this.dot(this);<br />
<br />
len() - Length of Vector<br />
return => return Math.sqrt(this.len2());<br />

project(axis) - Project a vector onto anouther.<br />
axis => vec2<br />
return => vec2<br />
<br />
projectN(axis) - Project onto a vector of unit length.<br />
axis => vec2<br />
return => vec2<br />
<br />
reflect(axis) - Reflect vector to a vector.<br />
axis => vec2<br />
return => vec2<br />
<br />
reflectN(axis) - Reflect on an Arbitrary Axis<br />
axis => vec2<br />
return => vec2<br />
<br />
getValue(v)  - Returns value of float or array,<br />
v => ('x' || 0) || ('y' || 1) || null;<br />
return => Float || Array(2);<br />
<br />
<br />
--------------------------------------------------------<br />
Any Question feel free to email me at Pryme8@gmail.com