The _grid master_ is a simple software to create a computer grid and to dispatch jobs around to achieve embarrassing parallelization.

The _grid master_ can do several things, most notably:
  * set up nodes
  * submit jobs
  * start executing jobs on one, or all nodes
  * stop the execution of jobs
  * monitor the status of jobs and of the grid

A key aspect is that all the executables, libraries and data must be available on the master only.