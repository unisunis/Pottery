# Pottery

Pottery is runtime pottery editing engine, developed using C# and Unity

Pottery object is array of horizontal circle's radius. Each circle has preset common vertical distance from one to another. Each circle is linked one by one into one solid mesh.

Each dot in one line is simply calculated

**x** = cos(π / faces * index)
<br>**y** = sin(π / faces * index)

For futher information about generation please check `PotteryGenerator.cs` file

Read XML documentation included in source code files, for further information.

## Install

To use this project as Unity Package, get git link of this repository from Clone section and add `#upm` postfix in Package Manager window.

## Results
<p>
<img src="http://sadikoff.com/projects/pottery/example.png" height=300>
<img src="http://sadikoff.com/projects/pottery/objectsExample.png" height=300>
</p>

Mesh structure
<p>
<img src="http://sadikoff.com/projects/pottery/meshStructure.png" height=300>
</p>

Pottery Demo editing example
<p>
<img src="http://sadikoff.com/projects/pottery/editingSample.gif" height=300>
</p>

## Contacts
Website **<a href="http://sadikoff.com/">sadikoff.com</a>**
<br>E-mail **<a href="mailto: jasur@sadikoff.com">jasur@sadikoff.com</a>**

## License
Licensed under GPLv3 license or under special license.
See the LICENSE file in the project root for further information.
