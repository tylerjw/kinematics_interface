^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package kinematics_interface_kdl
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.2 (2022-10-21)
------------------

0.0.1 (2022-10-11)
------------------
* Enable interface to use Eigen per default (`#6 <https://github.com/ros-controls/kinematics_interface/issues/6>`_)
* Add CI setup to the repository. (`#8 <https://github.com/ros-controls/kinematics_interface/issues/8>`_)
* Remove duplicate of Eigen dependency.
* Update CMakeFiles, correct deps and formatting. (`#10 <https://github.com/ros-controls/kinematics_interface/issues/10>`_)
* add pre-commit to repo (`#7 <https://github.com/ros-controls/kinematics_interface/issues/7>`_)
  add pre-commit
* Fix failing KDL test (`#5 <https://github.com/ros-controls/kinematics_interface/issues/5>`_)
  * add verification for all inputs
  * add underscore to end_effector
  * add test to ensure inverse then forward calculation is approximately unit
* Fix more indentations and alphabetize
* Update dependencies and maintainers
* Kinematics interface with KDL implementation
* change directory name and use header only interface
* Contributors: Paul Gesel, Andy Zelenak, Bence Magyar, Denis Štogl
