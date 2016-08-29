Just include this js file. Call an new vector with:

new vec2(x,y);

All Methods are chainable.

copy(vec) - Copy Values from one vec2 to other.
vec => vec2
return => vec

clone() - Make new vec2 from a vec2
return =>  new vec2

perp() - Get the Perpendicular angle;
return => vec2

rotate(angle) - Rotate a vec by an angle in radians.
angle => float
return => vec2

reverse() - Reverse the Vector
return => vec2

normalize() - Normalize the Vector
return => vec2

add(input) - Add a vec2
input => vec2
return => vec2


subtract(input) - Subtract other vec2
input => vec2
return => vec2

scale(x,y) - Scale vec2 by X or X and Y
x=> float
y=> float || null
return => vec2

dot(input) - Dot product between two vectors;
input => vec2
return (this.x * input.x + this.y * input.y)

len2() - Length of Vector^2
return this.dot(this);

len() - Length of Vector
return => return Math.sqrt(this.len2());

project(axis) - Project a vector onto anouther.
axis => vec2
return => vec2

projectN(axis) - Project onto a vector of unit length.
axis => vec2
return => vec2

reflect(axis) - Reflect vector to a vector.
axis => vec2
return => vec2

reflectN(axis) - Reflect on an Arbitrary Axis
axis => vec2
return => vec2

getValue(v)  - Returns value of float or array,
v => ('x' || 0) || ('y' || 1) || null;
return => Float || Array(2);
