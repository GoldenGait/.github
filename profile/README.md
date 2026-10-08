<p align="center">
  <img src="https://raw.githubusercontent.com/GoldenGait/.github/main/profile/media/hero.webp" width="100%" alt="Spot running the GoldenGait stack: walking an office corridor, its 117 m route drawn on the mapped floor, and arriving in the lab">
</p>

<h3 align="center">Agentic AI autonomy for legged robots &middot; Stanford &times; Berkeley</h3>

<p align="center">
  A vision-language agent drives a Boston Dynamics Spot to perceive, reason, and act on its own.<br>
  2nd place in Phase&nbsp;1 of the DARPA Tiamat Program.
</p>

## Research &amp; code

Building and deploying a full autonomy stack surfaces insights that a competition score never shows.
We turn them into open research, code, and datasets.

| Project | Code | Links |
|---|---|---|
| **FARM** &mdash; Find Anything using Relational Spatial Memory | [FARM-Project](https://github.com/GoldenGait/FARM-Project) | [Paper](https://arxiv.org/abs/2606.15476) &middot; [Project page](https://goldengait.github.io/farm/) &middot; [Dataset](https://huggingface.co/datasets/GoldenGait/FARM-Scenes) |
| **Scene-LM** &mdash; A Scene Language Model for Open-Vocabulary Scene Mapping | Coming soon | [Paper](https://arxiv.org/abs/2609.21400) &middot; [Project page](https://goldengait.github.io/scenelm/) |
| **GLST** &mdash; Global-Local Spatio-Temporal Memory Decomposition Framework for Online Chained-Goal Navigation &middot; *Accepted, CoRL 2026* | Coming soon | |
| **GGraph** &mdash; A GPU-Accelerated Library for Graph-Based Robot Deployment and Learning | Coming soon | |
| **BT-Agent** &mdash; Deploying Onboard Robot Agents with Behavior Trees and Multi-Fidelity Evaluation | Coming soon | |

## See it run

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://goldengait.github.io/farm/"><img src="https://raw.githubusercontent.com/GoldenGait/.github/main/profile/media/farm.webp" width="100%" alt="FARM building an object memory of a 4,000 square-metre warehouse"></a>
      <br><b>FARM</b> &middot; a persistent object memory of a 4,000&nbsp;m&sup2; warehouse
    </td>
    <td width="50%" valign="top">
      <a href="https://goldengait.github.io/scenelm/"><img src="https://raw.githubusercontent.com/GoldenGait/.github/main/profile/media/scenelm.webp" width="100%" alt="Scene-LM mapping a room in 3D, object by object"></a>
      <br><b>Scene-LM</b> &middot; one vision-language model builds the scene map
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="https://raw.githubusercontent.com/GoldenGait/.github/main/profile/media/mission.webp" width="100%" alt="Spot's route around the office floor while finding five targets, and its onboard camera">
      <br><b>Five targets, one run</b> &middot; real robot, onboard Jetson Thor
    </td>
    <td width="50%" valign="top">
      <img src="https://raw.githubusercontent.com/GoldenGait/.github/main/profile/media/office.webp" width="100%" alt="Spot walking into the lab next to a humanoid robot">
      <br><b>Office navigation</b> &middot; real robot, filmed on a phone
    </td>
  </tr>
</table>

## Dependencies we maintain

Forks with our own changes, kept public because our code depends on them:

- [`yoloe`](https://github.com/GoldenGait/yoloe) &mdash; YOLOE open-vocabulary detector; used by FARM.
- [`autonomy_stack_go2`](https://github.com/GoldenGait/autonomy_stack_go2) &mdash; CMU's legged-robot autonomy stack, with our local-planner changes.
- [`odin_ros_driver`](https://github.com/GoldenGait/odin_ros_driver) &mdash; ROS driver for the Manifold Odin sensor.

<p align="center"><sub>UC Berkeley &middot; Stanford University</sub></p>
