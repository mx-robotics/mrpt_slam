^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package mrpt_rbpf_slam
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.10 (2019-10-05)
-------------------
* fix build against mrpt2
* Contributors: Jose Luis Blanco-Claraco

0.1.9 (2019-04-14)
------------------
* fix build against mrpt-1.5 & 1.9.9
* Feature/refactor mrpt rbpf slam
* Add option to specify simplemap save path
* Add some non zero default noise values for thrun's motion model
* Small documentation fixes
* Rename example file
* Switch header guards to pragma once
* Add launch file for turtlebot3
* Switch default log level to INFO
* Contributors: Jose Luis Blanco-Claraco, Julian Lopez Velasquez, Vladislav Tananaev

0.1.8 (2018-09-21)
------------------
* Make catkin_lint clean
* Contributors: Jose Luis Blanco Claraco

0.1.7 (2018-09-20)
------------------

0.1.6 (2018-06-14)
------------------
* Merge pull request `#42 <https://github.com/mrpt-ros-pkg/mrpt_slam/issues/42>`_ from MaxGsomGsom/master
  Fixed build with MRPT 1.5
* Fixed compilation with MRPT 1.5
* Merge pull request `#41 <https://github.com/mrpt-ros-pkg/mrpt_slam/issues/41>`_ from MaxGsomGsom/master
  Fixed build with mrpt 2.0
* Fixed build with mrpt 2.0
* partial fix build w mrpt 2.0
* fix build in mrpt 2.0
* fix build; add optimized builds (-O3)
* fix build against mrpt 1.5 series
* Fixed wrong timeout for waitForTransform.
* Fixed wrong timeout for waitForTransform.
* use consistent cmake conventions for c++14
* all but mrpt_graphslam_2d compiling against mrpt2.0
* porting to mrpt2
* fix `#28 <https://github.com/mrpt-ros-pkg/mrpt_slam/issues/28>`_, compiling all nodes using -std=c++14
* CMake finds MRPT >=1.5 in branch master
* Merge pull request `#22 <https://github.com/mrpt-ros-pkg/mrpt_slam/issues/22>`_ from bergercookie/graphslam-devel
  Add support for 2D multi-robot SLAM
* mrpt_rbpf:Correct include guard
* fix build with MRPT 1.5.0
* Merge pull request `#20 <https://github.com/mrpt-ros-pkg/mrpt_slam/issues/20>`_ from Logrus/master
  Fixes and cleanups for config files
* [mrpt_rbpf_slam] Update description and dependencies of package.xml
  Add test for *.launch files.
* Move transforms to callbacks.
* Define C++11 avoiding direct manipulation of CXX_FLAGS
* catkin_lint error fixes
* Fix build against latest dev mrpt 1.5.0
* Contributors: Albert Kasdorf, Jose Luis Blanco, Jose Luis Blanco Claraco, Jose Luis Blanco-Claraco, Logrus, Magnus Gärtner, Max Kuzmin, Nikos Koukis, Vladislav Tananaev

0.1.5 (2016-11-18)
------------------
* Include ros/console hdr
* Fix cmakelists typo
* Contributors: Nikos Koukis

0.1.3 (2016-09-27)
------------------

0.1.2 (2016-09-24)
------------------
* Make formatting conform to ROS C++ Style Guide.
* Fix missing CObservationBeaconRanges.h include in mrpt_rbpf_slam.
* Fix description of the rbpf package.
* Output logs only in ROS.
* Add a guard for new mrpt_bridge::rosLoggerLvlToMRPTLoggerLvl and mrpt_bridge::mrptToROSLoggerCallback functions for MRPT version less than 1.5.0.
* Add streaming of MRPT logs to ROS logs.
* Update example config files with new localizeLinDistance and localizeAngDistance_deg.
* Fix build against MRPT<1.3.0
* Contributors: Jose Luis Blanco, Logrus, Vladislav Tananaev

0.1.1 (2016-08-22)
------------------
* First public version, as a result of Vladislav Tananaev's GSoC2016 work.
* Contributors: Jose Luis Blanco, Logrus
