AlphaDrive Demonstration based on ScenarioRunner for CARLA

ALPHADRIVE SAMPLES
===========

In this folder, you have an alphadrive.yml that defines a few profiles you can test out. 

Note that the AlphaDrive docker image used to execute the code contains all the dependencies of this project, so the only requirement is that your Mac or Linux host has a recent version of docker installed.

After you have installed the `alpha` command using:

```
bash <(curl -o - https://raw.githubusercontent.com/Alpha-Drive/alpha-command/master/install.sh)
```

Then authorize your CLI with `alpha login`.

You can now run any of the provided profiles:

- `alpha drive default` will run a scored 'Control Loss' scenario from this repository.
- `alpha drive manual` will launch a window where you can control the simulator's ego vehicle
- `alpha drive tutorial` runs some code that creates a few vehicles in the world, samples their sensors and saves them into a folder called `_out _`

CARLA NOTES
========================
This repository contains traffic scenario definition and an execution engine
for CARLA.

Disclaimer
----------

The current status is work in progress and may not reflect the final API

Building the ScenarioRunner
---------------------------

Use `git clone` or download the project from this page. Note that the master
branch contains the latest fixes and features, and my require to use the latest features from CARLA.

Currently no build is required, as all code is in Python.

Required packages: py_trees==0.8.3

Using the ScenarioRunner
------------------------

Please take a look at our [Getting started](Docs/getting_started.md)
documentation.

Contributing
------------

Please take a look at our [Contribution guidelines][contriblink].

[contriblink]: http://carla.readthedocs.io/en/latest/CONTRIBUTING

F.A.Q.
------

If you run into problems, check our
[FAQ](http://carla.readthedocs.io/en/latest/faq/).

License
-------

ScenarioRunner specific code is distributed under MIT License.
