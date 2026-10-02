<div align="center">

# lnivan

**Physics simulations, small games and 3D graphics, built from the maths up.**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pygame](https://img.shields.io/badge/Pygame-30363D?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Linear algebra](https://img.shields.io/badge/linear%20algebra-8250DF?style=flat-square)
![Numerical integration](https://img.shields.io/badge/numerical%20integration-8250DF?style=flat-square)

</div>

Most of these projects start from a question. How does a ragdoll hold together? What makes a wireframe cube look three-dimensional? What happens when a heavy ball hits a light one? I answer each one with as little library help as possible: I write the vectors, projection matrices, integrators and collision rules myself, and use Pygame only to draw the result.

## Simulations

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/lnivan/ragdoll-physics"><img src="https://raw.githubusercontent.com/lnivan/lnivan/main/assets/ragdoll-physics.gif" alt="A stick-figure ragdoll being dragged, flung and pushed around" width="100%"></a>
      <br><a href="https://github.com/lnivan/ragdoll-physics"><b>Ragdoll Physics</b></a>
      <br><sub>Point masses, rigid sticks and damped springs, stepped with position Verlet.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/lnivan/soft-body-sim"><img src="https://raw.githubusercontent.com/lnivan/lnivan/main/assets/soft-body-sim.gif" alt="A ring of point masses falling and slumping onto the floor" width="100%"></a>
      <br><a href="https://github.com/lnivan/soft-body-sim"><b>Soft Body Sim</b></a>
      <br><sub>A ring of masses in which every pair is joined by a damped spring.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/lnivan/spring-mass-simulator"><img src="https://raw.githubusercontent.com/lnivan/lnivan/main/assets/spring-mass-simulator.gif" alt="A string of masses sagging and swinging between two anchors" width="100%"></a>
      <br><a href="https://github.com/lnivan/spring-mass-simulator"><b>Spring–Mass Simulator</b></a>
      <br><sub>51 masses on springs, swinging between two heavy anchors.</sub>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/lnivan/rocket-orbit-sim"><img src="https://raw.githubusercontent.com/lnivan/lnivan/main/assets/rocket-orbit-sim.gif" alt="A rocket launching from Earth while its predicted trajectory is redrawn" width="100%"></a>
      <br><a href="https://github.com/lnivan/rocket-orbit-sim"><b>Rocket Orbit Sim</b></a>
      <br><sub>Real-scale Earth gravity, with the predicted path redrawn every frame.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/lnivan/elastic-ball-collisions"><img src="https://raw.githubusercontent.com/lnivan/lnivan/main/assets/elastic-ball-collisions.gif" alt="Balls of different sizes bouncing off each other in a box" width="100%"></a>
      <br><a href="https://github.com/lnivan/elastic-ball-collisions"><b>Elastic Ball Collisions</b></a>
      <br><sub>Exact 2D elastic collisions between balls of random mass.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/lnivan/n-body-gravity"><img src="https://raw.githubusercontent.com/lnivan/lnivan/main/assets/n-body-gravity.gif" alt="A star, a planet and a moon orbiting under mutual gravity" width="100%"></a>
      <br><a href="https://github.com/lnivan/n-body-gravity"><b>N-Body Gravity</b></a>
      <br><sub>A star, a planet and its moon under mutual Newtonian gravity.</sub>
    </td>
  </tr>
</table>

## Games and graphics

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/lnivan/asteroids"><img src="https://raw.githubusercontent.com/lnivan/lnivan/main/assets/asteroids.gif" alt="A ship firing at outlined asteroids that split when hit" width="100%"></a>
      <br><a href="https://github.com/lnivan/asteroids"><b>Asteroids</b></a>
      <br><sub>A vector arcade shooter in which every shape is stored in polar coordinates.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/lnivan/parabola-targets"><img src="https://raw.githubusercontent.com/lnivan/lnivan/main/assets/parabola-targets.gif" alt="Picking a level and launching a ball along a parabola towards a target" width="100%"></a>
      <br><a href="https://github.com/lnivan/parabola-targets"><b>Parabola Targets</b></a>
      <br><sub>A slingshot puzzle: bend parabolic shots around walls and into targets.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/lnivan/wireframe-3d"><img src="https://raw.githubusercontent.com/lnivan/lnivan/main/assets/wireframe-3d.gif" alt="A wireframe cube seen from a camera flying around it" width="100%"></a>
      <br><a href="https://github.com/lnivan/wireframe-3d"><b>Wireframe 3D</b></a>
      <br><sub>Hand-written matrices, perspective projection and a free-flying camera.</sub>
    </td>
  </tr>
</table>

**Also here:** [Geometry Viewer 3D](https://github.com/lnivan/geometry-viewer-3d) is a 3D point viewer built on my own vector and matrix classes. [Image Grid Splitter](https://github.com/lnivan/image-grid-splitter) is a one-button tool that cuts a photo into a 4 × 4 grid for printing a poster.

## Recurring ideas

| Idea | Where it shows up |
| --- | --- |
| Perspective projection with hand-written vectors and matrices | [Wireframe 3D](https://github.com/lnivan/wireframe-3d) · [Geometry Viewer 3D](https://github.com/lnivan/geometry-viewer-3d) |
| Position Verlet with rigid distance constraints | [Ragdoll Physics](https://github.com/lnivan/ragdoll-physics) |
| Semi-implicit Euler integration | [Spring–Mass Simulator](https://github.com/lnivan/spring-mass-simulator) · [N-Body Gravity](https://github.com/lnivan/n-body-gravity) |
| Damped springs (Hooke's law plus a damping term) | [Soft Body Sim](https://github.com/lnivan/soft-body-sim) · [Spring–Mass Simulator](https://github.com/lnivan/spring-mass-simulator) · [Ragdoll Physics](https://github.com/lnivan/ragdoll-physics) |
| Newtonian gravity and trajectory prediction | [Rocket Orbit Sim](https://github.com/lnivan/rocket-orbit-sim) · [N-Body Gravity](https://github.com/lnivan/n-body-gravity) |
| Elastic collisions along the line of centres | [Elastic Ball Collisions](https://github.com/lnivan/elastic-ball-collisions) |
| Projectile motion | [Parabola Targets](https://github.com/lnivan/parabola-targets) |
| Shapes stored in polar coordinates | [Asteroids](https://github.com/lnivan/asteroids) |

---

<div align="center"><sub>Projects from 2018 to 2026. Each README explains how the project works, how to run it with one command, and what is still rough.</sub></div>
