# AWS Oncall

## Build Status

### ROS 2 Core Packages

|                          | GCC ASAN                                                        | GCC TSAN                                                        | Clang Thread-Safety Annotations                                   |
|--------------------------|-----------------------------------------------------------------|-----------------------------------------------------------------|-------------------------------------------------------------------|
| **x86_64 Ubuntu Bionic** | [![Build Status][nightly-linux-asan-badge]][nightly-linux-asan] | [![Build Status][nightly-linux-tsan-badge]][nightly-linux-tsan] | [![Build Status][nightly-linux-clang-badge]][nightly-linux-clang] |

|                           | Debug                                                                             | Release                                                                               | Packaging                                                                                         |
|---------------------------|-----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| **x86_64 Ubuntu Bionic**  | [![Build Status][nightly-linux-debug-badge]][nightly-linux-debug]                 | [![Build Status][nightly-linux-release-badge]][nightly-linux-release]                 | [![Build Status][nightly-linux-packaging]][nightly-linux-packaging-badge]                         |
| **aarch64 Ubuntu Bionic** | [![Build Status][nightly-linux-aarch64-debug-badge]][nightly-linux-aarch64-debug] | [![Build Status][nightly-linux-aarch64-release-badge]][nightly-linux-aarch64-release] | [![Build Status][nightly-linux-aarch64-packaging-badge]][nightly-linux-aarch64-packaging]         |
| **armhf Ubuntu Bionic**   | [![Build Status][nightly-linux-armhf-debug-badge]][nightly-linux-armhf-debug]     | [![Build Status][nightly-linux-armhf-release-badge]][nightly-linux-armhf-release]     | [![Build Status][nightly-linux-armhf-packaging-badge]][nightly-linux-armhf-packaging]             |
| **OS X**                  | [![Build Status][nightly-osx-debug-badge]][nightly-osx-debug]                     | [![Build Status][nightly-osx-release-badge]][nightly-osx-release]                     | [![Build Status][nightly-osx-packaging-badge]][nightly-osx-packaging]                             |
| **Windows**               | [![Build Status][nightly-win-debug-badge]][nightly-win-debug]                     | [![Build Status][nightly-win-release-badge]][nightly-win-release]                     | [![Build Status][nightly-win-packaging-badge]][nightly-win-packaging]                             |

### Other Packages

#### Owned Repositories

##### Latest (`master`)

| Repository Name                        | Latest                                                                         | Coverage                                                                   | Issues                                                                           | PRs                                                                                                  |
|----------------------------------------|--------------------------------------------------------------------------------|----------------------------------------------------------------------------|----------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| [colcon/colcon-bundle]                 | [![Build Status][colcon-bundle-travis-badge]][colcon-bundle-travis]            | N/A                                                                        | [![GitHub issues][colcon-bundle-issues-badge]][colcon-bundle-issues]                        | [![GitHub pull requests][colcon-bundle-pr-badge]][colcon-bundle-pr]                       |
| [colcon/colcon-ros-bundle]             | [![Build Status][colcon-ros-bundle-travis-badge]][colcon-ros-bundle-travis]    | N/A                                                                        | [![GitHub issues][colcon-ros-bundle-issues-badge]][colcon-ros-bundle-issues]                | [![GitHub pull requests][colcon-ros-bundle-pr-badge]][colcon-ros-bundle-pr]               |
| [ros-tooling/action-ros2-ci]           | [![GitHub Action Status][action-ros2-ci-badge]][action-ros2-ci-action]         | N/A                                                                        | [![GitHub issues][action-ros2-ci-issues-badge]][action-ros2-ci-issues]                      | [![GitHub pull requests][action-ros2-ci-pr-badge]][action-ros2-ci-pr]                     |
| [ros-tooling/action-ros2-lint]         | [![GitHub Action Status][action-ros2-lint-badge]][action-ros2-lint-action]     | N/A                                                                        | [![GitHub issues][action-ros2-lint-issues-badge]][action-ros2-lint-issues]                  | [![GitHub pull requests][action-ros2-lint-pr-badge]][action-ros2-lint-pr]                 |
| [ros-tooling/cross_compile]            | [![GitHub Action Status][cross-compile-badge]][cross-compile-action]           | [![codecov][cross-compile-codecov-badge]][cross-compile-codecov]           | [![GitHub issues][cross-compile-issues-badge]][cross-compile-issues]                        | [![GitHub pull requests][cross-compile-pr-badge]][cross-compile-pr]                       |
| [ros-tooling/file_talker]              | [![GitHub Action Status][file-talker-badge]][file-talker-action]               | N/A                                                                        | [![GitHub issues][file-talker-issues-badge]][file-talker-issues]                            | [![GitHub pull requests][file-talker-pr-badge]][file-talker-pr]                           |
| [ros-tooling/system_metrics_collector] | [![GitHub Action Status][system-metrics-badge]][system-metrics-action]         | [![codecov][system-metrics-codecov-badge]][system-metrics-codecov]         | [![GitHub issues][system-metrics-collector-issues-badge]][system-metrics-collector-issues]  | [![GitHub pull requests][system-metrics-collector-pr-badge]][system-metrics-collector-pr] |
| [ros-tooling/setup-ros]                | [![GitHub Action Status][setup-ros-badge]][setup-ros-action]                   | N/A                                                                        | [![GitHub issues][setup-ros-issues-badge]][setup-ros-issues]                                | [![GitHub pull requests][setup-ros-pr-badge]][setup-ros-pr]                               |
| [ros-security/launch_ros_sandbox]      | [![GitHub Action Status][launch-ros-sandbox-badge]][launch-ros-sandbox-action] | [![codecov][launch-ros-sandbox-codecov-badge]][launch-ros-sandbox-codecov] | [![GitHub issues][launch-ros-sandbox-issues-badge]][launch-ros-sandbox-issues]              | [![GitHub pull requests][launch-ros-sandbox-pr-badge]][launch-ros-sandbox-pr]             |
| [ros2/rcpputils]                       | N/A                                                                            | N/A                                                                        | [![GitHub issues][rcpputils-issues-badge]][rcpputils-issues]                                | [![GitHub pull requests][rcpputils-pr-badge]][rcpputils-pr]                               |


##### Eloquent
| Repository Name                        | dev                                                                                                                                                                                                 | source                                                                                                                                                                                                              | x86_64                                                                                                                                                                                                                                  | ARM 64-bits                                                                                                                                                                                                                                                 | ARM 32-bits                                                                                                                                                                                                                                                 |
|----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ros-tooling/cross_compile]            | [![Build Status](http://build.ros2.org/view/Edev/job/Edev__cross_compile__ubuntu_bionic_amd64/badge/icon)](http://build.ros2.org/view/Edev/job/Edev__cross_compile__ubuntu_bionic_amd64/)           | [![Build Status](http://build.ros2.org/view/Esrc_uB/job/Esrc_uB__cross_compile__ubuntu_bionic__source/badge/icon)](http://build.ros2.org/view/Esrc_uB/job/Esrc_uB__cross_compile__ubuntu_bionic__source/)           | [![Build Status](http://build.ros2.org/view/Ebin_uB64/job/Ebin_uB64__cross_compile__ubuntu_bionic_amd64__binary/badge/icon)](http://build.ros2.org/view/Ebin_uB64/job/Ebin_uB64__cross_compile__ubuntu_bionic_amd64__binary/)           | [![Build Status](http://build.ros2.org/view/Ebin_ubv8_uBv8/job/Ebin_ubv8_uBv8__cross_compile__ubuntu_bionic_arm64__binary/badge/icon)](http://build.ros2.org/view/Ebin_ubv8_uBv8/job/Ebin_ubv8_uBv8__cross_compile__ubuntu_bionic_arm64__binary/)           | [![Build Status](http://build.ros2.org/view/Ebin_ubhf_uBhf/job/Ebin_ubhf_uBhf__cross_compile__ubuntu_bionic_armhf__binary/badge/icon)](http://build.ros2.org/view/Ebin_ubhf_uBhf/job/Ebin_ubhf_uBhf__cross_compile__ubuntu_bionic_armhf__binary/)           |
| [ros2/rcpputils]                       | [![Build Status](http://build.ros2.org/view/Edev/job/Edev__rcpputils__ubuntu_bionic_amd64/badge/icon)](http://build.ros2.org/view/Edev/job/Edev__rcpputils__ubuntu_bionic_amd64/)                   | [![Build Status](http://build.ros2.org/view/Esrc_uB/job/Esrc_uB__rcpputils__ubuntu_bionic__source/badge/icon)](http://build.ros2.org/view/Esrc_uB/job/Esrc_uB__rcpputils__ubuntu_bionic__source/)                   | [![Build Status](http://build.ros2.org/view/Ebin_uB64/job/Ebin_uB64__rcpputils__ubuntu_bionic_amd64__binary/badge/icon)](http://build.ros2.org/view/Ebin_uB64/job/Ebin_uB64__rcpputils__ubuntu_bionic_amd64__binary/)                   | [![Build Status](http://build.ros2.org/view/Ebin_ubv8_uBv8/job/Ebin_ubv8_uBv8__rcpputils__ubuntu_bionic_arm64__binary/badge/icon)](http://build.ros2.org/view/Ebin_ubv8_uBv8/job/Ebin_ubv8_uBv8__rcpputils__ubuntu_bionic_arm64__binary/)                   | [![Build Status](http://build.ros2.org/view/Ebin_ubhf_uBhf/job/Ebin_ubhf_uBhf__rcpputils__ubuntu_bionic_armhf__binary/badge/icon)](http://build.ros2.org/view/Ebin_ubhf_uBhf/job/Ebin_ubhf_uBhf__rcpputils__ubuntu_bionic_armhf__binary/)                   |


##### Dashing

| Repository Name                        | dev                                                                                                                                                                                                 | source                                                                                                                                                                                                              | x86_64                                                                                                                                                                                                                                  | ARM 64-bits                                                                                                                                                                                                                                                 | ARM 32-bits                                                                                                                                                                                                                                                 |
|----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ros-tooling/cross_compile]            | [![Build Status](http://build.ros2.org/view/Ddev/job/Ddev__cross_compile__ubuntu_bionic_amd64/badge/icon)](http://build.ros2.org/view/Ddev/job/Ddev__cross_compile__ubuntu_bionic_amd64/)           | [![Build Status](http://build.ros2.org/view/Dsrc_uB/job/Dsrc_uB__cross_compile__ubuntu_bionic__source/badge/icon)](http://build.ros2.org/view/Dsrc_uB/job/Dsrc_uB__cross_compile__ubuntu_bionic__source/)           | [![Build Status](http://build.ros2.org/view/Dbin_uB64/job/Dbin_uB64__cross_compile__ubuntu_bionic_amd64__binary/badge/icon)](http://build.ros2.org/view/Dbin_uB64/job/Dbin_uB64__cross_compile__ubuntu_bionic_amd64__binary/)           | [![Build Status](http://build.ros2.org/view/Dbin_ubv8_uBv8/job/Dbin_ubv8_uBv8__cross_compile__ubuntu_bionic_arm64__binary/badge/icon)](http://build.ros2.org/view/Dbin_ubv8_uBv8/job/Dbin_ubv8_uBv8__cross_compile__ubuntu_bionic_arm64__binary/)           | [![Build Status](http://build.ros2.org/view/Dbin_ubhf_uBhf/job/Dbin_ubhf_uBhf__cross_compile__ubuntu_bionic_armhf__binary/badge/icon)](http://build.ros2.org/view/Dbin_ubhf_uBhf/job/Dbin_ubhf_uBhf__cross_compile__ubuntu_bionic_armhf__binary/)           |
| [ros-tooling/setup-ros2]               | [![Build Status](http://build.ros2.org/view/Ddev/job/Ddev__launch_ros_sandbox__ubuntu_bionic_amd64/badge/icon)](http://build.ros2.org/view/Ddev/job/Ddev__launch_ros_sandbox__ubuntu_bionic_amd64/) | [![Build Status](http://build.ros2.org/view/Dsrc_uB/job/Dsrc_uB__launch_ros_sandbox__ubuntu_bionic__source/badge/icon)](http://build.ros2.org/view/Dsrc_uB/job/Dsrc_uB__launch_ros_sandbox__ubuntu_bionic__source/) | [![Build Status](http://build.ros2.org/view/Dbin_uB64/job/Dbin_uB64__launch_ros_sandbox__ubuntu_bionic_amd64__binary/badge/icon)](http://build.ros2.org/view/Dbin_uB64/job/Dbin_uB64__launch_ros_sandbox__ubuntu_bionic_amd64__binary/) | [![Build Status](http://build.ros2.org/view/Dbin_ubv8_uBv8/job/Dbin_ubv8_uBv8__launch_ros_sandbox__ubuntu_bionic_arm64__binary/badge/icon)](http://build.ros2.org/view/Dbin_ubv8_uBv8/job/Dbin_ubv8_uBv8__launch_ros_sandbox__ubuntu_bionic_arm64__binary/) | [![Build Status](http://build.ros2.org/view/Dbin_ubhf_uBhf/job/Dbin_ubhf_uBhf__launch_ros_sandbox__ubuntu_bionic_armhf__binary/badge/icon)](http://build.ros2.org/view/Dbin_ubhf_uBhf/job/Dbin_ubhf_uBhf__launch_ros_sandbox__ubuntu_bionic_armhf__binary/) |
| [ros2/rcpputils]                       | [![Build Status](http://build.ros2.org/view/Ddev/job/Ddev__rcpputils__ubuntu_bionic_amd64/badge/icon)](http://build.ros2.org/view/Ddev/job/Ddev__rcpputils__ubuntu_bionic_amd64/)                   | [![Build Status](http://build.ros2.org/view/Dsrc_uB/job/Dsrc_uB__rcpputils__ubuntu_bionic__source/badge/icon)](http://build.ros2.org/view/Dsrc_uB/job/Dsrc_uB__rcpputils__ubuntu_bionic__source/)                   | [![Build Status](http://build.ros2.org/view/Dbin_uB64/job/Dbin_uB64__rcpputils__ubuntu_bionic_amd64__binary/badge/icon)](http://build.ros2.org/view/Dbin_uB64/job/Dbin_uB64__rcpputils__ubuntu_bionic_amd64__binary/)                   | [![Build Status](http://build.ros2.org/view/Dbin_ubv8_uBv8/job/Dbin_ubv8_uBv8__rcpputils__ubuntu_bionic_arm64__binary/badge/icon)](http://build.ros2.org/view/Dbin_ubv8_uBv8/job/Dbin_ubv8_uBv8__rcpputils__ubuntu_bionic_arm64__binary/)                   | [![Build Status](http://build.ros2.org/view/Dbin_ubhf_uBhf/job/Dbin_ubhf_uBhf__rcpputils__ubuntu_bionic_armhf__binary/badge/icon)](http://build.ros2.org/view/Dbin_ubhf_uBhf/job/Dbin_ubhf_uBhf__rcpputils__ubuntu_bionic_armhf__binary/)                   |

#### Monitored Repositories

##### Latest (`master`)

| Repository Name       | Latest | Coverage | Issues                                                                                                                      | PRs                                                                                                                                  |
|-----------------------|--------|----------|-----------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
| [ros2/rosbag2]        | [![GitHub Action Status](https://github.com/ros2/rosbag2/workflows/Test%20rosbag2/badge.svg)](https://github.com/ros2/rosbag2/actions)    | N/A      | [![GitHub issues](https://img.shields.io/github/issues/ros2/rosbag2)](https://github.com/ros2/rosbag2/issues)               | [![GitHub pull requests](https://img.shields.io/github/issues-pr/ros2/rosbag2)](https://github.com/ros2/rosbag2/pulls)               |
| [ros2/rosbag2_bag_v2] | N/A    | N/A      | [![GitHub issues](https://img.shields.io/github/issues/ros2/rosbag2_bag_v2)](https://github.com/ros2/rosbag2_bag_v2/issues) | [![GitHub pull requests](https://img.shields.io/github/issues-pr/ros2/rosbag2_bag_v2)](https://github.com/ros2/rosbag2_bag_v2/pulls) |

##### Eloquent

| Repository Name       | dev                                                                                                                                                                                         | source                                                                                                                                                                                                                      | x86_64                                                                                                                                                                                                                                          | ARM 64-bits                                                                                                                                                                                                                                                         | ARM 32-bits                                                                                                                                                                                                                                                         |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ros2/rosbag2]        | [![Build Status](http://build.ros2.org/view/Edev/job/Edev__rosbag2__ubuntu_bionic_amd64/badge/icon)](http://build.ros2.org/view/Edev/job/Edev__rosbag2__ubuntu_bionic_amd64/)               | [![Build Status](http://build.ros2.org/view/Esrc_uB/job/Esrc_uB__rosbag2__ubuntu_bionic__source/badge/icon)](http://build.ros2.org/view/Esrc_uB/job/Esrc_uB__rosbag2__ubuntu_bionic__source/)                               | [![Build Status](http://build.ros2.org/view/Ebin_uB64/job/Ebin_uB64__rosbag2__ubuntu_bionic_amd64__binary/badge/icon)](http://build.ros2.org/view/Ebin_uB64/job/Ebin_uB64__rosbag2__ubuntu_bionic_amd64__binary/)                               | [![Build Status](http://build.ros2.org/view/Ebin_ubv8_uBv8/job/Ebin_ubv8_uBv8__rosbag2__ubuntu_bionic_arm64__binary/badge/icon)](http://build.ros2.org/view/Ebin_ubv8_uBv8/job/Ebin_ubv8_uBv8__rosbag2__ubuntu_bionic_arm64__binary/)                               | [![Build Status](http://build.ros2.org/view/Ebin_ubhf_uBhf/job/Ebin_ubhf_uBhf__rosbag2__ubuntu_bionic_armhf__binary/badge/icon)](http://build.ros2.org/view/Ebin_ubhf_uBhf/job/Ebin_ubhf_uBhf__rosbag2__ubuntu_bionic_armhf__binary/)                               |
| [ros2/rosbag2_bag_v2] | [![Build Status](http://build.ros2.org/view/Edev/job/Edev__rosbag2_bag_v2__ubuntu_bionic_amd64/badge/icon)](http://build.ros2.org/view/Edev/job/Edev__rosbag2_bag_v2__ubuntu_bionic_amd64/) | [![Build Status](http://build.ros2.org/view/Esrc_uB/job/Esrc_uB__rosbag2_bag_v2_plugins__ubuntu_bionic__source/badge/icon)](http://build.ros2.org/view/Esrc_uB/job/Esrc_uB__rosbag2_bag_v2_plugins__ubuntu_bionic__source/) | [![Build Status](http://build.ros2.org/view/Ebin_uB64/job/Ebin_uB64__rosbag2_bag_v2_plugins__ubuntu_bionic_amd64__binary/badge/icon)](http://build.ros2.org/view/Ebin_uB64/job/Ebin_uB64__rosbag2_bag_v2_plugins__ubuntu_bionic_amd64__binary/) | [![Build Status](http://build.ros2.org/view/Ebin_ubv8_uBv8/job/Ebin_ubv8_uBv8__rosbag2_bag_v2_plugins__ubuntu_bionic_arm64__binary/badge/icon)](http://build.ros2.org/view/Ebin_ubv8_uBv8/job/Ebin_ubv8_uBv8__rosbag2_bag_v2_plugins__ubuntu_bionic_arm64__binary/) | [![Build Status](http://build.ros2.org/view/Ebin_ubhf_uBhf/job/Ebin_ubhf_uBhf__rosbag2_bag_v2_plugins__ubuntu_bionic_armhf__binary/badge/icon)](http://build.ros2.org/view/Ebin_ubhf_uBhf/job/Ebin_ubhf_uBhf__rosbag2_bag_v2_plugins__ubuntu_bionic_armhf__binary/) |

##### Dashing

| Repository Name | dev                                                                                                                                                                           | source                                                                                                                                                                                        | x86_64                                                                                                                                                                                                            | ARM 64-bits                                                                                                                                                                                                                           | ARM 32-bits                                                                                                                                                                                                                           |
|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [ros2/rosbag2]  | [![Build Status](http://build.ros2.org/view/Ddev/job/Ddev__rosbag2__ubuntu_bionic_amd64/badge/icon)](http://build.ros2.org/view/Ddev/job/Ddev__rosbag2__ubuntu_bionic_amd64/) | [![Build Status](http://build.ros2.org/view/Dsrc_uB/job/Dsrc_uB__rosbag2__ubuntu_bionic__source/badge/icon)](http://build.ros2.org/view/Dsrc_uB/job/Dsrc_uB__rosbag2__ubuntu_bionic__source/) | [![Build Status](http://build.ros2.org/view/Dbin_uB64/job/Dbin_uB64__rosbag2__ubuntu_bionic_amd64__binary/badge/icon)](http://build.ros2.org/view/Dbin_uB64/job/Dbin_uB64__rosbag2__ubuntu_bionic_amd64__binary/) | [![Build Status](http://build.ros2.org/view/Dbin_ubv8_uBv8/job/Dbin_ubv8_uBv8__rosbag2__ubuntu_bionic_arm64__binary/badge/icon)](http://build.ros2.org/view/Dbin_ubv8_uBv8/job/Dbin_ubv8_uBv8__rosbag2__ubuntu_bionic_arm64__binary/) | [![Build Status](http://build.ros2.org/view/Dbin_ubhf_uBhf/job/Dbin_ubhf_uBhf__rosbag2__ubuntu_bionic_armhf__binary/badge/icon)](http://build.ros2.org/view/Dbin_ubhf_uBhf/job/Dbin_ubhf_uBhf__rosbag2__ubuntu_bionic_armhf__binary/) |
| [ros2/rosbag2_bag_v2] | [![Build Status](http://build.ros2.org/view/Ddev/job/Ddev__rosbag2_bag_v2__ubuntu_bionic_amd64/badge/icon)](http://build.ros2.org/view/Ddev/job/Ddev__rosbag2_bag_v2__ubuntu_bionic_amd64/) | [![Build Status](http://build.ros2.org/view/Dsrc_uB/job/Dsrc_uB__rosbag2_bag_v2_plugins__ubuntu_bionic__source/badge/icon)](http://build.ros2.org/view/Dsrc_uB/job/Dsrc_uB__rosbag2_bag_v2_plugins__ubuntu_bionic__source/) | [![Build Status](http://build.ros2.org/view/Dbin_uB64/job/Dbin_uB64__rosbag2_bag_v2_plugins__ubuntu_bionic_amd64__binary/badge/icon)](http://build.ros2.org/view/Dbin_uB64/job/Dbin_uB64__rosbag2_bag_v2_plugins__ubuntu_bionic_amd64__binary/) | [![Build Status](http://build.ros2.org/view/Dbin_ubv8_uBv8/job/Dbin_ubv8_uBv8__rosbag2_bag_v2_plugins__ubuntu_bionic_arm64__binary/badge/icon)](http://build.ros2.org/view/Dbin_ubv8_uBv8/job/Dbin_ubv8_uBv8__rosbag2_bag_v2_plugins__ubuntu_bionic_arm64__binary/) | [![Build Status](http://build.ros2.org/view/Dbin_ubhf_uBhf/job/Dbin_ubhf_uBhf__rosbag2_bag_v2_plugins__ubuntu_bionic_armhf__binary/badge/icon)](http://build.ros2.org/view/Dbin_ubhf_uBhf/job/Dbin_ubhf_uBhf__rosbag2_bag_v2_plugins__ubuntu_bionic_armhf__binary/) |

#### Appendix

* **Latest** compiles ROS2 from source using tip of all development branches
* **Eloquent** compiles ROS2 from source using the eloquent branches
* **Dashing** compiles ROS2 from source using the dashing branches

[colcon/colcon-bundle]: https://github.com/colcon/colcon-bundle
[colcon/colcon-ros-bundle]: https://github.com/colcon/colcon-ros-bundle
[colcon/colcon-sanitizer-reports]: https://github.com/colcon/colcon-sanitizer-reports
[ros-security/launch_ros_sandbox]: https://github.com/ros-security/launch_ros_sandbox
[ros-tooling/action-ros2-ci]: https://github.com/ros-tooling/action-ros2-ci
[ros-tooling/action-ros2-lint]: https://github.com/ros-tooling/action-ros2-lint
[ros-tooling/cross_compile]: https://github.com/ros-tooling/cross_compile
[ros-tooling/file_talker]: https://github.com/ros-tooling/file_talker
[ros-tooling/setup-ros2]: https://github.com/ros-tooling/setup-ros2
[ros-tooling/system_metrics_collector]: https://github.com/ros-tooling/system_metrics_collector
[ros2/rcpputils]: https://github.com/ros2/rcpputils
[ros2/rosbag2]: https://github.com/ros2/rosbag2
[ros2/rosbag2_bag_v2]: https://github.com/ros2/rosbag2_bag_v2

[nightly-linux-asan]: https://ci.ros2.org/view/nightly/job/nightly_linux_address_sanitizer
[nightly-linux-asan-badge]: https://ci.ros2.org/view/nightly/job/nightly_linux_address_sanitizer/badge/icon
[nightly-linux-tsan]: https://ci.ros2.org/view/nightly/job/nightly_linux_thread_sanitizer
[nightly-linux-tsan-badge]: https://ci.ros2.org/view/nightly/job/nightly_linux_thread_sanitizer/badge/icon
[nightly-linux-clang]: https://ci.ros2.org/view/nightly/job/nightly_linux_clang_libcxx/badge/icon
[nightly-linux-clang-badge]: https://ci.ros2.org/view/nightly/job/nightly_linux_clang_libcxx/badge/icon

[nightly-linux-debug]: https://ci.ros2.org/view/nightly/job/nightly_linux_debug
[nightly-linux-debug-badge]: https://ci.ros2.org/view/nightly/job/nightly_linux_debug/badge/icon
[nightly-linux-release]: https://ci.ros2.org/view/nightly/job/nightly_linux_release
[nightly-linux-release-badge]: https://ci.ros2.org/view/nightly/job/nightly_linux_release/badge/icon
[nightly-linux-packaging]: https://ci.ros2.org/view/packaging/job/packaging_linux
[nightly-linux-packaging-badge]: https://ci.ros2.org/view/packaging/job/packaging_linux/badge/icon

[nightly-linux-aarch64-debug]: https://ci.ros2.org/view/nightly/job/nightly_linux-aarch64_debug
[nightly-linux-aarch64-debug-badge]: https://ci.ros2.org/view/nightly/job/nightly_linux-aarch64_debug/badge/icon
[nightly-linux-aarch64-release]: https://ci.ros2.org/view/nightly/job/nightly_linux-aarch64_release
[nightly-linux-aarch64-release-badge]: https://ci.ros2.org/view/nightly/job/nightly_linux-aarch64_release/badge/icon
[nightly-linux-aarch64-packaging]: https://ci.ros2.org/view/packaging/job/packaging_linux-aarch64
[nightly-linux-aarch64-packaging-badge]: https://ci.ros2.org/view/packaging/job/packaging_linux-aarch64/badge/icon

[nightly-linux-armhf-debug]: https://ci.ros2.org/view/nightly/job/nightly_linux-armhf_debug
[nightly-linux-armhf-debug-badge]: https://ci.ros2.org/view/nightly/job/nightly_linux-armhf_debug/badge/icon
[nightly-linux-armhf-release]: https://ci.ros2.org/view/nightly/job/nightly_linux-armhf_release
[nightly-linux-armhf-release-badge]: https://ci.ros2.org/view/nightly/job/nightly_linux-armhf_release/badge/icon
[nightly-linux-armhf-packaging]: https://ci.ros2.org/view/packaging/job/packaging_linux-armhf
[nightly-linux-armhf-packaging-badge]: https://ci.ros2.org/view/packaging/job/packaging_linux-armhf/badge/icon

[nightly-osx-debug]: https://ci.ros2.org/view/nightly/job/nightly_osx_debug
[nightly-osx-debug-badge]: https://ci.ros2.org/view/nightly/job/nightly_osx_debug/badge/icon
[nightly-osx-release]: https://ci.ros2.org/view/nightly/job/nightly_osx_release
[nightly-osx-release-badge]: https://ci.ros2.org/view/nightly/job/nightly_osx_release/badge/icon
[nightly-osx-packaging]: https://ci.ros2.org/view/packaging/job/packaging_osx
[nightly-osx-packaging-badge]: https://ci.ros2.org/view/packaging/job/packaging_osx/badge/icon

[nightly-win-debug]: https://ci.ros2.org/view/nightly/job/nightly_win_debug
[nightly-win-debug-badge]: https://ci.ros2.org/view/nightly/job/nightly_win_debug/badge/icon
[nightly-win-release]: https://ci.ros2.org/view/nightly/job/nightly_win_rel
[nightly-win-release-badge]: https://ci.ros2.org/view/nightly/job/nightly_win_rel/badge/icon
[nightly-win-packaging]: https://ci.ros2.org/view/packaging/job/packaging_windows
[nightly-win-packaging-badge]: https://ci.ros2.org/view/packaging/job/packaging_windows/badge/icon

[colcon-bundle-travis]: https://travis-ci.org/colcon/colcon-bundle
[colcon-bundle-travis-badge]: https://travis-ci.org/colcon/colcon-bundle.svg?branch=master
[colcon-bundle-issues-badge]: https://img.shields.io/github/issues/colcon/colcon-bundle
[colcon-ros-bundle-travis]: https://travis-ci.org/colcon/colcon-ros-bundle
[colcon-ros-bundle-travis-badge]: https://travis-ci.org/colcon/colcon-ros-bundle.svg?branch=master
[colcon-ros-bundle-issues-badge]: https://img.shields.io/github/issues/colcon/colcon-ros-bundle
[action-ros2-ci-action]: https://github.com/ros-tooling/action-ros2-ci/actions
[action-ros2-ci-badge]: https://github.com/ros-tooling/action-ros2-ci/workflows/Test%20action-ros2-ci/badge.svg
[action-ros2-ci-issues]: https://github.com/ros-tooling/action-ros2-ci/issues
[action-ros2-ci-issues-badge]: https://img.shields.io/github/issues/ros-tooling/action-ros2-ci
[action-ros2-lint-action]: https://github.com/ros-tooling/action-ros2-lint/actions
[action-ros2-lint-badge]: https://github.com/ros-tooling/action-ros2-lint/workflows/Test%20action-ros2-lint/badge.svg
[action-ros2-lint-issues-badge]: https://img.shields.io/github/issues/ros-tooling/action-ros2-lint
[cross-compile-action]: https://github.com/ros-tooling/cross_compile/actions
[cross-compile-badge]: https://github.com/ros-tooling/cross_compile/workflows/Test%20cross_compile/badge.svg
[cross-compile-issues]: https://github.com/ros-tooling/cross_compile/issues
[cross-compile-issues-badge]: https://img.shields.io/github/issues/ros-tooling/cross_compile
[cross-compile-codecov]: https://codecov.io/gh/ros-tooling/cross_compile
[cross-compile-codecov-badge]: https://codecov.io/gh/ros-tooling/cross_compile/branch/master/graph/badge.svg
[file-talker-action]: https://github.com/ros-tooling/file_talker/actions
[file-talker-badge]: https://github.com/ros-tooling/file_talker/workflows/Test%20file_talker/badge.svg
[file-talker-issues-badge]: https://img.shields.io/github/issues/ros-tooling/file_talker
[system-metrics-action]: https://github.com/ros-tooling/system_metrics_collector/actions
[system-metrics-badge]: https://github.com/ros-tooling/system_metrics_collector/workflows/Test%20system_metrics_collector/badge.svg
[system-metrics-codecov]: https://codecov.io/gh/ros-tooling/system_metrics_collector
[system-metrics-codecov-badge]: https://codecov.io/gh/ros-tooling/system_metrics_collector/branch/master/graph/badge.svg
[system-metrics-collector-issues-badge]: https://img.shields.io/github/issues/ros-tooling/system_metrics_collector
[setup-ros-action]: https://github.com/ros-tooling/setup-ros/actions
[setup-ros-badge]: https://github.com/ros-tooling/setup-ros/workflows/Test%20setup-ros/badge.svg
[setup-ros-issues]: https://github.com/ros-tooling/setup-ros/issues
[setup-ros-issues-badge]: https://img.shields.io/github/issues/ros-tooling/setup-ros
[launch-ros-sandbox-action]: https://github.com/ros-security/launch_ros_sandbox/actions
[launch-ros-sandbox-badge]: https://github.com/ros-security/launch_ros_sandbox/workflows/Test%20launch_ros_sandbox/badge.svg
[launch-ros-sandbox-codecov]: https://codecov.io/gh/ros-security/launch_ros_sandbox
[launch-ros-sandbox-codecov-badge]: https://codecov.io/gh/ros-security/launch_ros_sandbox/branch/master/graph/badge.svg
[launch-ros-sandbox-issues-badge]: https://img.shields.io/github/issues/ros-security/launch_ros_sandbox
[rcpputils-issues-badge]: https://img.shields.io/github/issues/ros2/rcpputils
[rcpputils-issues]: https://github.com/ros2/rcpputils/issues


[colcon-bundle-issues]: https://github.com/colcon/colcon-bundle/issues
[colcon-ros-bundle-issues]: https://github.com/colcon/colcon-ros-bundle/issues
[action-ros2-lint-issues]: https://github.com/ros-tooling/action-ros2-lint/issues
[cross-compile-issues]: https://github.com/ros-tooling/cross_compile/issues
[file-talker-issues]: https://github.com/ros-tooling/file_talker/issues
[system-metrics-collector-issues]: https://github.com/ros-tooling/system_metrics_collector/issues
[launch-ros-sandbox-issues]: https://github.com/ros-security/launch_ros_sandbox/issues

[colcon-bundle-pr-badge]: https://img.shields.io/github/issues-pr/colcon/colcon-bundle
[colcon-ros-bundle-pr-badge]: https://img.shields.io/github/issues-pr/colcon/colcon-ros-bundle
[action-ros2-ci-pr-badge]: https://img.shields.io/github/issues-pr/ros-tooling/action-ros2-ci
[action-ros2-lint-pr-badge]: https://img.shields.io/github/issues-pr/ros-tooling/action-ros2-lint
[cross-compile-pr-badge]: https://img.shields.io/github/issues-pr/ros-tooling/cross_compile
[file-talker-pr-badge]: https://img.shields.io/github/issues-pr/ros-tooling/file_talker
[system-metrics-collector-pr-badge]: https://img.shields.io/github/issues-pr/ros-tooling/system_metrics_collector
[setup-ros-pr-badge]: https://img.shields.io/github/issues-pr/ros-tooling/setup-ros
[launch-ros-sandbox-pr-badge]: https://img.shields.io/github/issues-pr/ros-security/launch_ros_sandbox
[rcpputils-pr-badge]: https://img.shields.io/github/issues-pr/ros2/rcpputils

[colcon-bundle-pr]: https://github.com/colcon/colcon-bundle/pulls
[colcon-ros-bundle-pr]: https://github.com/colcon/colcon-ros-bundle/pulls
[action-ros2-ci-pr]: https://github.com/ros-tooling/action-ros2-ci/pulls
[action-ros2-lint-pr]: https://github.com/ros-tooling/action-ros2-lint/pulls
[cross-compile-pr]: https://github.com/ros-tooling/cross_compile/pulls
[file-talker-pr]: https://github.com/ros-tooling/file_talker/pulls
[system-metrics-collector-pr]: https://github.com/ros-tooling/system_metrics_collector/pulls
[setup-ros-pr]: https://github.com/ros-tooling/setup-ros2/pulls
[launch-ros-sandbox-pr]: https://github.com/ros-security/launch_ros_sandbox/pulls
[rcpputils-pr]: https://github.com/ros2/rcpputils/pulls



