A command-line program that calculates a quaternion Julia set and then writes the corresponding isosurface to a binary Stereo Lithography file.

Supports custom-defined iterative equations, such as:

Z = Z^4 + C <br>
Z = sin(Z) + C <code>*</code> sin(Z) <br>
Z = inverse(sinh(Z)) + C <code>*</code> inverse(sinh(Z)) <br>
<i>etc.</i>

See quaternion_math.h for a full list of supported quaternion functions.<br>
<br>
Compiles using g++ and MSVC++.