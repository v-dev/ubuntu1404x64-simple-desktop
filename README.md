ubuntu1404x64-simple-desktop
============================

Link to public vagrant base box using virtualbox provider.  It is Ubuntu 14.04 x64 Desktop with plain GUI.


== Add box to vagrant ==
Syntax:
````
vagrant box add ADDRESS --name VALUE
````

Description
From https://docs.vagrantup.com/v2/cli/box.html:

This adds a box with the given address to Vagrant. The address can be one of three things:
3. URL directly a box file. In this case, you must specify a --name flag (see below) and versioning/updates won't work.


--name VALUE - Logical name for the box. This is the value that you would put into config.vm.box in your Vagrantfile.
When adding a box from a catalog, the name is included in the catalog entry and doesn't have to be specified.



Example:
````
vagrant box add package.box --name ubuntu1404x64-simple-desktop
````
