# Floating Point Almost Equal
v1.0.2

Copyright © 2014, Ryan Porter
All rights reserved.

Author:	 Ryan Porter
LAVA Name: Porter
Contact Info: Contact Porter via PM on lavag.org

LabVIEW Versions:
LV >=8.6 (Windows)

Dependencies:
LAVA Palette

Description:
This package contains VIs for testing equality of floating point numbers within a specified tolerance. Absolute Epsilon comparison, Relative Epsilon comparison and the ULP comparison have been implemented as described in this blog post by Bruce Dawson: 
http://randomascii.wordpress.com/2012/02/25/comparing-floating-point-numbers-2012-edition/

Note that the ULP comparison has not been implemented for extended precision floating point type.
 

Installation and instructions:
Install VIP package using VI Package Manager.

Examples:
"<LabVIEW>\examples\LAVA\AlmostEqual\AlmostEqual_Example 1.vi"	Demonstrates the usage of all three AlmostEqual functions.
"<LabVIEW>\examples\LAVA\AlmostEqual\AlmostEqual_Example 2.vi"	Demonstrates a case where exactly equal fails to produce the expected result.

Known Issues:
ULP comparison has not been implemented for extended precision floating point type.

Acknowledgements:
Bruce Dawson: Code of this package was inspired by his blog post on comparing floating point numbers (http://randomascii.wordpress.com/2012/02/25/comparing-floating-point-numbers-2012-edition/).

Version History:
v1.0.0: Initial release of the code.
V1.0.1: Changed icon colors.
V1.0.2: Set all VIs to Pre-Allocated Re-Entrant Execution

License:
Distributed under the BSD 2-Clause (http://opensource.org/licenses/BSD-2-Clause)
See link for a full description of the license.

Support:
If you have any problems with this code or want to suggest features contact Porter via PM on lavag.org

Distribution:
This code was downloaded from the LAVA Code Repository found at lavag.org

Sources:
1) http://forums.ni.com/t5/LabVIEW/How-to-measure-LSBits-of-difference-between-floats-if-possible/m-p/303665#M158227

2) http://forums.ni.com/t5/LabVIEW-Idea-Exchange/quot-Almost-Equal-quot-functions-for-Float-comparisons/idi-p/1446480

3) http://lavag.org/topic/16733-floating-point-equal-primitive/

4) http://www.cygnus-software.com/papers/comparingfloats/comparingfloats.htm

5) http://randomascii.wordpress.com/2012/02/25/comparing-floating-point-numbers-2012-edition/

6) ftp://ftp.ni.com/pub/devzone/tut/floating_point_in_labview.pdf

