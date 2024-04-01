# Bypass-UAC-Prompt
Bypass Administrator Privileges

The __COMPAT_LAYER variable has some options that we are interested in. There are the following parameters:

RunAsInvoker – run an app with the privileges of a parent process without a UAC prompt;
RunAsHighest – run a program with the highest-level permission available to the user (the UAC prompt will appear if a user has administrator privileges);
RunAsAdmin – run an app as administrator (the UAC prompt will always appear).
