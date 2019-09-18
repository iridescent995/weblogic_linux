# weblogic_linux
Install weblogic in linux

1. Install generic version of weblogic not the quick install.


General Error

# 1.
~~~
1. java.lang.AssertionError: Could not obtain the localhost address. The most likely cause is an error in the network configuration of this machine.
2. java.lang.IllegalStateException: Unable to perform operation: post construct on weblogic.rjvm.RJVMService
~~~

Solution:
Add your hostname (pc name) to /etc/hosts.

# 2.
Cant remotely access weblogic from different machine

refer: https://stackoverflow.com/questions/14208775/remotely-accessing-weblogic-server
