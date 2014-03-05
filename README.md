install
=======

Install files for deployment.

## Common usage

Create a catkin workspace:
```
mkdir -p pandora_ws/src
cd pandora_ws/src
```

Use `wstool` to fetch all repos:
```
wstool init .
wstool merge https://raw.github.com/pandora-auth-ros-pkg/install/hydro-devel/pandora_all.rosinstall
wstool update
```

_NOTE: If you don't have `wstool` installed, run `sudo apt-get install python-wstool`._

**More info [here](https://github.com/pandora-auth-ros-pkg/pandora_docs/wiki/Setup%20Packages).**
