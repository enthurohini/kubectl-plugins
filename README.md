## Leverage kubectl plugins functionality to add more features to kubectl command

### Feature 1:
To ssh into the worker where the pod actualy resides.
- Copy kubectl-pwssh file in your `PATH`.
- Make it execuatble : `chmod u+x kubectl-pwssh`
- you are done.

**Command usage:**

    kubectl pwssh <podname>

### Feature 2:
To sort the kubernetes nodes utilisation by CPU and RAM
- Copy kubectl-sort-no file in your `PATH`.
- Make it execuatble : `chmod u+x kubectl-sort-no`
- you are done.

**Command usage:**

    kubectl sort no ram
    OR
    kubectl sort no cpu

### Feature 3:
To sort the kubernetes pods utilisation by CPU and RAM

- Copy kubectl-sort-po file in your `PATH`.
- Make it execuatble : `chmod u+x kubectl-sort-po`
- you are done.

**Command usage:**

    kubectl sort po ram
    OR
    kubectl sort po cpu