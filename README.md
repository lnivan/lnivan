<div align="center">

<img src="assets/banner.svg" width="100%" alt="lnivan, maths undergrad: games, simulations and small tools. An animated wireframe cube rotates next to a planet and its moon orbiting a star.">

</div>

I'm a maths undergraduate. This is a compendium of small programming projects I've been doing through the years, mostly early high-school experiments but things I'm working on now. Most of them are physics simulations, games and small tools, written in Python.

The repositories were uploaded recently, so their commit dates don't show when each project was written. Each README explains how the project works, how to run it and what is still unfinished.

## Simulations

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/lnivan/ragdoll-physics"><img src="assets/ragdoll-physics.gif" width="100%" alt="A stick-figure ragdoll picked up by its chest, swung around, tossed, caught and set back down"></a>
      <br><a href="https://github.com/lnivan/ragdoll-physics"><b>Ragdoll Physics</b></a>
      <br>An interactive 2D ragdoll built from point masses, rigid distance constraints and spring–damper joints, integrated with position Verlet. The figure can be dragged, thrown and pushed.
      <br><sub>Python · NumPy · Pygame</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/lnivan/soft-body-sim"><img src="assets/soft-body-sim.gif" width="100%" alt="A ring of point masses falling and deforming against the floor"></a>
      <br><a href="https://github.com/lnivan/soft-body-sim"><b>Soft Body Sim</b></a>
      <br>A soft-body simulation: a ring of point masses in which every pair is joined by a damped spring, deforming under gravity when it hits the floor.
      <br><sub>Python · Pygame</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/lnivan/spring-mass-simulator"><img src="assets/spring-mass-simulator.gif" width="100%" alt="A chain of masses hanging and oscillating between two anchors"></a>
      <br><a href="https://github.com/lnivan/spring-mass-simulator"><b>Spring–Mass Simulator</b></a>
      <br>A chain of point masses connected by damped springs, suspended between two anchors and integrated with semi-implicit Euler.
      <br><sub>Python · Pygame</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/lnivan/elastic-ball-collisions"><img src="assets/elastic-ball-collisions.gif" width="100%" alt="Balls of different sizes colliding inside a box"></a>
      <br><a href="https://github.com/lnivan/elastic-ball-collisions"><b>Elastic Ball Collisions</b></a>
      <br>Elastic collisions between balls of different masses, with each impact resolved along the line joining their centres.
      <br><sub>Python · Pygame</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/lnivan/rocket-orbit-sim"><img src="assets/rocket-orbit-sim.gif" width="100%" alt="Zooming out during a flight: the outline of Earth appears with the predicted trajectory around it"></a>
      <br><a href="https://github.com/lnivan/rocket-orbit-sim"><b>Rocket Orbit Sim</b></a>
      <br>A rocket launched from a real-scale Earth under Newtonian gravity, with steerable thrust, zoom and a live prediction of its trajectory.
      <br><sub>Python · Pygame</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/lnivan/n-body-gravity"><img src="assets/n-body-gravity.gif" width="100%" alt="A star, a planet and a moon moving under mutual gravity"></a>
      <br><a href="https://github.com/lnivan/n-body-gravity"><b>N-Body Gravity</b></a>
      <br>A gravitational simulation of a star, a planet and its moon, each attracting the others.
      <br><sub>Python · Pygame</sub>
    </td>
  </tr>
</table>

## Games and graphics

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/lnivan/minecraft-2d"><img src="assets/minecraft-2d.gif" width="100%" alt="A pixel-art player walking, building, digging and setting off TNT in a 2D block world"></a>
      <br><a href="https://github.com/lnivan/minecraft-2d"><b>Minecraft 2D</b></a>
      <br>A side-view block sandbox with procedurally generated terrain, gravity and collisions, block placement and removal, and TNT explosions.
      <br><sub>Python · Pygame</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/lnivan/asteroids"><img src="assets/asteroids.gif" width="100%" alt="A small ship firing at asteroids that split when hit"></a>
      <br><a href="https://github.com/lnivan/asteroids"><b>Asteroids</b></a>
      <br>A version of the arcade game with inertial ship movement, screen wrap-around and asteroids that split when hit.
      <br><sub>Python · Pygame</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/lnivan/parabola-targets"><img src="assets/parabola-targets.gif" width="100%" alt="A ball launched like a slingshot flying past obstacles towards a target"></a>
      <br><a href="https://github.com/lnivan/parabola-targets"><b>Parabola Targets</b></a>
      <br>A physics puzzle game: launch a projectile with a slingshot-style control and get it past the obstacles into the target, across several levels.
      <br><sub>Python · Pygame</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/lnivan/wireframe-3d"><img src="assets/wireframe-3d.gif" width="100%" alt="A wireframe cube seen from a camera moving around it"></a>
      <br><a href="https://github.com/lnivan/wireframe-3d"><b>Wireframe 3D</b></a>
      <br>A software wireframe renderer that uses no 3D library: custom vector and matrix classes, perspective projection and a free-flying camera.
      <br><sub>Python · Pygame</sub>
    </td>
  </tr>
</table>

Also: [Geometry Viewer 3D](https://github.com/lnivan/geometry-viewer-3d), a 3D point viewer built on its own vector and matrix classes.

## Tools

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/lnivan/screen-explainer"><img src="assets/screen-explainer.svg" width="100%" alt="Illustration: press Ctrl+Shift+A, select part of the screen, and an explanation appears in a floating window"></a>
      <br><a href="https://github.com/lnivan/screen-explainer"><b>Screen Explainer</b></a>
      <br>A desktop utility started with a global hotkey. The selected region of the screen is sent to the Gemini API, and the explanation appears in a floating window (illustration).
      <br><sub>Python · PyQt6 · Gemini API</sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/lnivan/snake-autoplayer"><img src="assets/snake-autoplayer.svg" width="100%" alt="Animation of the route the snake bot follows on an 11 by 11 board"></a>
      <br><a href="https://github.com/lnivan/snake-autoplayer"><b>Snake Autoplayer</b></a>
      <br>A bot that plays a browser Snake game by reading the screen and sending keystrokes. It alternates between two fixed routes that together cover the whole board (one is shown above).
      <br><sub>Python · Pillow</sub>
    </td>
  </tr>
</table>

Also: [Image Grid Splitter](https://github.com/lnivan/image-grid-splitter), a utility that splits an image into a 4 × 4 grid for printing it as a poster.
