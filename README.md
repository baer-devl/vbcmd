vbcmd - Virtualbox Command Line Tool
====================================

Overview
--------

> A small collection of useful commands to handle Virtualbox containers on a Linux based X display hosts.
> HINT: display numbers are equal to the F<7-12> key maps!


Commands
--------

### displays or d
> Displays all active displays which are started with this tool.

### vms or v
> Displays all available Virtualbox containers which can be executed.

### rvms or r
> Displays all running Virtualbox containers.

### run <virtualbox name> <display number>
> Create a new X display if not present and run the given Virtualbox container on it.

### empty <display number>
> Creates a new X display if not present on the given display number.

### stop <virtualbox name> <display number>
> Stops the Virtualbox container and safe its state but do not end the X display.

### end <virtualbox name> <display number>
> Save the state of the executed Virtualbox container and destroys the X display afterwards.

### kill <display number>
> Destroys a X display if its existing and do not care if there is a Virtualbox container nor other applications running inside.