---
title: Web-based VNC console 
order: 4
duration: 5
---

You can access the your instance command line via the web-based vnc-console on your [Nectar Dashboard](https://dashboard.rc.nectar.org.au/). 

1. On your [Nectar Dashboard](https://dashboard.rc.nectar.org.au/) select your project and navigate to the Instances page

2. On the instances page click the name of your instance and then select the Console tab

   ![Instance console]({{ site.baseurl }}/assets/images/connecting/instance-console.png)

3. If necessary, activate the keyboard input by clicking the grey area surrounding the black console

4. log into your instance using the default user account (`ubuntu` in our example) and password you set in the previous section.

You can now type commands into your console in just the same way you would in the `ssh` terminal we've seen earlier. Try it! How about

```bash
$ sudo apt update
```

If you ran the command above in a Ubuntu or Debian instance, then  the operating system checks for updates to any installed components. It reports how many packages can be upgraded. You can learn more about the command line, sudo and installing and maintaining software on your instance in another tutorial.
{: .callout-warning}

**the console vs. pasting and data**
The console is a handy and straightforward web-based tool to get access to your instance command line. Two of its prominent drawbacks are that the console doesn't accept pasting data from the clipboard, nor can you transfer data from your local machine to your instance. 
{: .callout-danger}

