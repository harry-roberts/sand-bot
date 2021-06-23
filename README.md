# Sisyphus Table Clone

My attempt to create a copy of the "Sisyphus Table" by Bruce Shapiro

To do:
1. Physical motion mechanism
2. Motion code
3. Final electronics/code
   - e.g. WiFi control, lighting
4. Casing

## Background

The Sisyphus Table is a kinetic art piece that uses a ball bearing to draw patterns in a bed of sand. The ball bearing is controlled by a motion mechanism underneath the table, and so it appears as if the ball is moving around on its own. My goal is to create one of these with the main aims being low cost and mainly 3D-printed parts. Mine will be a desktop sized version rather than a full table.

<p align="center">
  <img src="images/table.png"/>
</p>
<p align="center"><em>
	Bruce Shapiro's Sisyphus Table
</em></p>

<p align="center">
  <img src="images/pattern.png"/>
</p>
<p align="center"><em>
	Pattern Example
</em></p>

## Motion Mechanism

To move the ball bearing around, a magnet needs to move underneath the table. There are several ways to achieve this, and after some experimenting I have landed on a SCARA setup. This is compact and easily 3D printable, the only additional parts being some screws and timing belts.

<p align="center">
  <img src="images/cad.png"/>
</p>
<p align="center"><em>
	My CAD Model of the SCARA Assembly
</em></p>

<p align="center">
  <img src="images/actual.png"/>
</p>
<p align="center"><em>
	Printed and Assembled Parts
</em></p>
