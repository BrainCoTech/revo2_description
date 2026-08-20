^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package revo2_description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.1.1 (2026-08-20)
------------------
* Align thumb abduction limit to 0~89 deg and MCP limit to 0~60 deg with current mass-production version (20260818)
* Sync ``.urdf`` and ``.urdf.xacro``

1.1.0 (2026-08-16)
------------------
* Thumb abduction: redefine zero by +3 deg metacarpal joint origin offset; limits 0~90 deg
* Thumb MCP/PIP: motion limits 0~62 deg / 0~66 deg; PIP mimic 1.0945x
* Four-finger PIP: motion limits 0~97 deg; mimic 1.131 / 1.267 / 1.252 / 1.271
* Keep thumb MCP/PIP origin compensation (+9 deg / +6 deg); mass/inertia unchanged
* Sync ``.urdf`` and ``.urdf.xacro`` for all joint changes

1.0.0 (2025-10-20)
------------------
* Initial release of Revo2 description package (ROS2)
* Added URDF models for left and right Revo2 hands
* Added RViz and Gazebo launch files for visualization and simulation
* Added Docker support for easy deployment
