=============================
dirac-install-executor
=============================

2013-02-06 12:30:31 UTC Framework NOTICE: DIRAC Root Path = /afs/in2p3.fr/home/h/hamar/DIRAC-v6r7

Do the initial installation and configuration of a DIRAC service

Usage::

  dirac-install-executor [option|cfgfile] ... System Service|System/Service

Arguments::

  System:  Name of the DIRAC system (ie: WorkloadManagement)

  Service: Name of the DIRAC service (ie: Matcher) 

 

Options::

  -w   --overwrite       : Overwrite the configuration in the global CS 

  -m:  --module=         : Python module name for the executor code 

  -p:  --parameter=      : Special executor option  


