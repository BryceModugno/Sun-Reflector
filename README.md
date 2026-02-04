# Sun Reflector
This project solves the problem of precisely reflecting sunlight onto a fixed target by calculating real-time azimuth and elevation angles and actuating a 2-axis mirror system.


![Demo animation](Media/FINAL_1.gif)


## Requirements
- Maintain target alignment within ±1°
- Operate year-round at fixed GPS coordinates
- No obstruction above mirror surface

## Design Concepts
<table>
<tr>
<td width="50%" align="left" valign="top">

<h3 align="center"> Outer Frame Design - Rejected </h3>
<hr width="100%">

<ul>
  <li>Bulky frame required</li>
  <li>Frame blocks one axis of rotation</li>
  <li>Too much rotating mass</li>
</ul>

</td>
<td width="50%" align="center" valign="middle">

<img src="Media/IMG_0964.jpeg" width="100%">

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" align="left" valign="top">

<h3 align="center"> Linear Actuator Design - Rejected </h3>
<hr width="100%">

<ul>
  <li>Overly complicated joints</li>
  <li>Difficult angle control</li>
  <li>Actuators are excessively powerful and expensive</li>
</ul>

</td>
<td width="50%" align="center" valign="middle">

<img src="Media/IMG_0965.jpeg" width="100%">
<img src="Media/IMG_0966.jpeg" width="100%">

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" align="left" valign="top">

<h3 align="center"> Rotating Base Design - Accepted </h3>
<hr width="100%">

<ul>
  <li>Independent azimuth/elevation control</li>
  <li>Affordable</li>
  <li>3D printing manufacturing only</li>
</ul>

</td>
<td width="50%" align="center" valign="middle">

<img src="Media/IMG_1016.jpeg" width="100%">
<img src="Media/IMG_1019.jpeg" width="100%">

</td>
</tr>
</table>

## Analysis
[Derived azimuth/elevation equations →](design/derivations.pdf)
<img src="Media/Derivation_pg1.jpg" width="100%">
<img src="Media/Derivation_pg2.jpg" width="100%">
<img src="Media/Derivation_pg3.jpg" width="100%">
<img src="Media/Derivation_pg4.jpg" width="100%">
<img src="Media/Derivation_pg5.jpg" width="100%">

## CAD & Simulation
![CAD](media/CAD.png)

- NX assembly with motion constraints MAKE ABOVE A LINK TO A 3RD SOURCE ROTABLE 3D MODEL

## Manufacturing
- 3D printing
- Manual assembly

## Results
- Must be physically assembled and tested
