#OpenShift Outreachy projects

[OpenShift](https://www.openshift.com) consists of number of community projects
and products from Red Hat.  This year we'd love for you to participate as part
of Outreachy 2016 on a number of  upstream projects:

* [**Project 1**](#vagrantfile-improvements-for-openshift-ansible): Make the Vagrantfile in [openshift-ansible](https://github.com/openshift/openshift-ansible) awesome.
* [**Project 2**](#help-get-origin-in-to-centos): Get [Origin](https://github.com/openshift/origin) into (CentOS)[https://www.centos.org/].
* [**Project 3**](#ftl): Learn Ansible internals and help us create [FTL](https://github.com/ftl-toolbox/ftl_installer).
* [**Project 4**](#shiny-new-ansible-modules-for-openshift): Help us improve the official installer for OpenShift Enterprise by creating
  Ansible modules for multi-step tasks.
* [**Project 5**](#upstream-openshift-ansible-documentation): Join our upstream documentation effort to help us keep up with the breakneck
  pace of [openshift-ansible](https://github.com/openshift/openshift-ansible) development.

### Joining
If any of these projects sounds interesting to you contact us on [our mailing list](http://lists.openshift.redhat.com/openshift-archives/dev/) and we'll put you in touch with the right people.

### Vagrantfile improvements for [openshift-ansible](https://github.com/openshift/openshift-ansible)
If you are already familiar with [Vagrant](https://www.vagrantup.com/) or have
an interest in learning to make reproduceable development environments for
large teams this would be an ideal project.  If you don't know anything about
[Ansible](https://www.ansible.com/) we'll help you through that too.

The short of the story is that we use Vagrant fairly heavily on the OpenShift
team but unfortunately the Vagrantfile for our OpenShift Ansible playbooks
historically been more popular than we expected.  This Vagrantfile needs
someone's attention to make it more generically useful for the community.

This could involve:

* Better support for multi-machine environments
* Better documentation
* Working with us to set up continuous integration for whatever awesome feature
  you come up with.

### Help get Origin in to CentOS
We want OpenShift Origin to be as easy as possible to consume.  One part of
this would involve help making it available in CentOS.  You could join the team
responsible for building the Origin binaries.  This would likely involve quite
a bit of scripting it either bash or python.

### FTL
Faster Than Light is the project name for a new installation framework to be
built on top of Ansible.  Discussions around this project are just starting to
happen so there's never been a better time to join. :)

The highlevel goal for this project is to make it easy for developers to build
installation tools that embed Ansible.  While Ansible can handle all the heavy
lifting of getting the work done there are some common UI needs for
installation tools that aren't really Ansible's job.  This project would
involve programming in python.

### Shiny new Ansible modules for OpenShift
The [openshift-ansible](https://github.com/openshift/openshift-ansible)
playbooks are great way to make contributions to both the Origin project and
OpenShift Enterprise product.  Some of the heavy lifting in these playbooks
would be better done in Ansible modules instead of using the command or shell
modules in clever ways.  This project would involve learning to install Origin,
understanding the current playbooks and then writing Ansible modules in python
to replace the current functionality.

### Upstream OpenShift Ansible documentation
If quality documentation is your passion the Origin team could use your help to
fully document all the features of the
[openshift-ansible](https://github.com/openshift/openshift-ansible) playbooks.
The OpenShift Ansible community is a thriving group of both users and customers
and some of the latest features are not fully documented.  You could work with
the [openshift-docs](https://github.com/openshift/openshift-docs) team to
create content for both Origin and OpenShift Enterprise.
