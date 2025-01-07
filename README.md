# SimonaExtSimTestJars

This repository contains the code to generate the jar files used in
[SIMONA](https://github.com/ie3-institute/simona) to test the loading
of external simulations.

## Pre-generated test jars

The jars for the [simonaAPI](https://github.com/ie3-institute/simonaAPI) version `0.6.0` can be found in the `buildJars` folder.


## How to use

- To add new jar files, you need to add a new module by editing the `settings.gradle` file.
- To generate all jar at once, you need to execute `assemble` on the main project. The jar for each sub-module is generated automatically.
- The generated jars are in the `/build/lib` folders of the sub-modules.

