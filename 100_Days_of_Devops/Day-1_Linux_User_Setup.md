To accommodate the backup agent tool's specifications, the system admin team at xFusionCorp Industries requires the creation of a user with a non-interactive shell. Here's your task:



Create a user named yousuf with a non-interactive shell on App Server 1.

Solution:

You have to create a user named "yousuf" with a non-interactive shell (i.e., a shell that prevents login access) on App Server 1, with below command

```
sudo useradd -s /sbin/nologin yousuf
```

