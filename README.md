# scratchy
Additional Material for the paper "Scratchy: A Lightweight Modular Autonomous Robot for Robotic Competitions".

A preprint can be found on [arxiv](https://arxiv.org/abs/1905.05642).

![Scratchy drawing](images/scratchy_drawing.png)

## Install

* create a workspace
  * `mkdir scratchy_ws`
  * `cd scratchy_ws`
  * `mkdir src`
  * `catkin_init_workspace src`
* Clone packages:
  * `cd src`
  * `git clone https://github.com/homer-robotics/homer_scratchy_moveit_config`
  * `git clone https://github.com/homer-robotics/homer_mapnav_msgs`
  * `git clone https://github.com/homer-robotics/homer_mapping`
  * `git clone https://github.com/homer-robotics/homer_map_manager`
  * `git clone https://github.com/homer-robotics/homer_navigation`
* Build:
  * Go to workspace
  * `catkin_make` 


# Citation

```
@inproceedings{memmesheimer2019scratchy,
  title={Scratchy: A Lightweight Modular Autonomous Robot for Robotic Competitions},
  author={Memmesheimer, Raphael and Kuhlmann, Isabelle and Mints, Mark and Schmidt, Patrik and Korbach, Christian and Germann, Ida and Paulus, Dietrich},
  booktitle={2019 IEEE International Conference on Autonomous Robot Systems and Competitions (ICARSC)},
  pages={1--6},
  year={2019},
  organization={IEEE}
}

```
