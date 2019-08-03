To leverage kubectl plugins functionality to add more features to kubectl command.

Feature 1: To ssh into the worker where the pod actualy resides.
-> Copy kubectl-pwssh file in your PATH.
-> Make it execuatble : chmod u+x kubectl-pwssh
-> you are done.

Command usage:

kubectl pwssh <podname>  
