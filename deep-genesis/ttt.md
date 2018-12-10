---
layout: default
title: TOSCA types & templates
New field 1: Alien4Cloud - DEEP plugin
---

# TOSCA types & templates plugin v. 3.0.0
**Description of TOSCA types & templates
**

Summary:

* [Release Notes](#rn)
	* [What's new](#wn)
	* [List of RfCs](#lrfc)
	* [Known Issues](#kn)
	* [List of Artifacts](#la)
* [Documentation](#doc)
* [Support](#su)

<a name="rn">&nbsp;</a>
## Release Notes

<a name="wn">&nbsp;</a>
### What's new
This new versions provide a number of new features and bug fixes.

<a name="lrfc">&nbsp;</a>
### List of RfCs

* Added new types for Onedata and Dynafed storage resources
* Updated example templates for deploying Chronos dockerized jobs that use Onedata for managing input/output data
* Updated example template for deploying a Mesos cluster
* Added example template for deploying a Mesos cluster with GPU support and a tensorflow container on top of it that uses GPU(s)
* Added GPU support for compute nodes and dockerized jobs (chronos) and apps (marathon)
* Added preemtible_instance property to support "spot" instances
* Added example template for launching the generic_deepaas mesos job
* Added Onedata support in DODAS template
* Added new types for describing a Kubernetes cluster; new Ansible roles implemented.
* Added new type for describing a JupyterHub node; new Ansible role implemented.
* Fixing for Galaxy on cloud:
	* Update support to Galaxy release_18.05 in indigo-dc.galaxycloud
	* Fix proftpd in indigo-dc.galaxycloud
	* New ansible role for galaxy tools installation, named indigo-dc.galaxycloud-tools
	* Update tosca.nodes.indigo.GalaxyShedTool with new ansible role
	* Fix CERN-VM FS reference data mount on cluster worker nodes on galaxy artifacts
	* Reworked ansible role (indigo-dc.galaxycloud-fastconfig) to reconfigure an image with Galaxy already installed
	* Reworked storage encryption script on indigo-dc.galaxycloud-os
	* Fix tasks order in Galaxy elastic cluster tosca template: now galaxy user is created before slurm configuration.

<a name="kn">&nbsp;</a>
### Known Issues

<a name="la">&nbsp;</a>
### List of Artifacts

<a name="doc">&nbsp;</a>
### Documentation

<a name="su">&nbsp;</a>
### Support