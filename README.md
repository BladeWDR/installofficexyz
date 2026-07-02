This is a wrapper around Microsoft's Office Deployment Tool that simplifies installing Microsoft 365 Apps, Project, Visio, and other Microsoft Office products.

It's particularly useful for doing Ad-hoc installs of office whenever necessary.

Working at an MSP and doing a lot of break/fix type work, I often find myself having to install office or reinstall office on machines that do not have our management software on it.

Having to go through the rigmarole of downloading ODT, creating a config file, running the commands - it got tedious.

You can quickly run this on your own system by running this command in PowerShell.

```ps1
irm installoffice.xyz/setup | iex
```

Note that this requires to be run as administrator.
