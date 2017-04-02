# TWS-Command-Line-Intro

Unix / Linux commands for getting started using IWS or "The Scheduler Formerly Known as Maestro".


These are commands to get users started with Ibm Workload Scheduler on the command line. 

Additionally, there are wrapper scripts to ease typing of conman command and filter out the ibm clutter they add to all the output.

These let you type less on the command line. Instead of typing "conman sj comp#sched" you just type "sj comp#sched". Even better for previous days' output, instead of 
conman "setsym 1 & sj comp#sched", just type 
sj 1 comp#sched 
This maps to the full command. And if your command history puts you at the end of the command line, you can append a digit like:  "sj comp#sched 1" and will get "conman setsym 1 & sj comp#sched".
