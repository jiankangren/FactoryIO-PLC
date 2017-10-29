# FactoryIO-PLC

This repository contains examples which show how to link Structure Text to
Factory-IO. The repository is divided as follows:
* [examples](./examples) - contains two examples, scene1 and testbed, both of
  which are written in Structured Text using the OpenPLC program. The scene1
  example was used for debugging purposes but is a good place to start. The
  testbed example is the code that was used for the Fischertechnik setup.
* [lib](./lib) - contains header files used by compilation scripts. These files
  were copied from another repository to simply compilation.
* [scenes](./scenes) - contains all work related to combining the C code
  generated by the 'matiec' compiler with Factory-IO. The two working examples
  are fischertechnik and scene1\_c\_updated. The remaining scenes was
  intermediary work that may provide some insight.
* [scripts](./scripts) - contains two compilation scripts. setup.bat should be
  run in either Windows Powershell or Windows CMD and setup.sh should be run in
  the Linux subsystem for Windows.

To run the examples or build on them, please refer to the source code.

# Requirements

To run these examples, the following programs/executables are required:
* Factory-IO available [here](https://factoryio.com/)
* Linux subsystem for Windows and miscellaneous packages
* matiec compiler available [here](https://bitbucket.org/mjsousa/matiec)
* OpenPLC Editor available [here](http://www.openplcproject.com/plcopen-editor)

