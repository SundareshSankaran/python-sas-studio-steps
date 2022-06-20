# SAS Studio Custom Steps for virtual Python environments
Repository containing a set of example custom steps which make it possible to create, activate, capture details, and revert from virtual Python environments within SAS Studio.

Package your Python-based analytics solutions in a portable, repeatable, and reusable manner.  Here are SAS Studio custom steps which help you create, activate, and switch between virtual Python environment for use within SAS Viya.  

## Overview

Refer this [blog](https://blogs.sas.com/content/subconsciousmusings/2022/05/16/python-a-la-carte) for background.  The ability to create and use virtual Python environments for use within SAS Viya helps data scientists create portable solutions,  maintain solution integrity, and exploit the integration between SAS and Python to the fullest extent.

Watch this example! ![Creating virtual Python environments within SAS Studio.](https://youtu.be/UIYZf2bKcWw)

This repository contains 4 custom steps which are offered as examples of how you could create, activate, switch between, and package virtual Python environments from within SAS Viya applications and tools, such as SAS Studio.  It makes use of [Custom Steps](https://go.documentation.sas.com/doc/en/webeditorcdc/v_006/webeditorug/n0b7ljqhka8lh5n12judc27x5gph.htm), a component within SAS Studio which help users package repeatable steps in an user-friendly manner.

This is meant only to be used as an example, for facilitation and is not official SAS software. Obviously, it requires a SAS Viya license in order to be used in its intended form.  It was created in collaboration with my colleague Ali Aiello at SAS Institute.  Acknowledgements to Jody Steadman, SAS Institute R&D, for his help with the SAS Configurator for Open Source.


## Pre-requisites
1. A SAS Viya 4 environment (monthly release 2021.2.1 or later) with SAS Studio Flows
2. Python configured with the above environment (preferably using the [SAS Configurator for Open Source](https://go.documentation.sas.com/doc/en/itopscdc/v_016/itopswn/p19hj5ipftk86un1axa51rzr5mxv.htm))
3. Python [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html) package installed in above Python environment (the base environment)

## Installation

Two options exist for installation, which you may choose based on your comfort level.

1. via Transfer package :  Import the transfer package provided into your SAS Viya 4 environment.  A couple of ways to import this are to [use Environment Manager](https://go.documentation.sas.com/doc/en/sasadmincdc/v_027/calcontentmig3x/n0djzpossyj6rrn1vvi1wfvp2qhp.htm) or [use the sas-viya CLI Transfer plugin](https://www.youtube.com/watch?v=iYi-CoineJY).

2. Direct upload :  Upload the custom steps given in this documentation directly into SAS Studio through the [upload button](https://go.documentation.sas.com/doc/en/webeditorcdc/v_011LTS/webeditorug/n0f4pkd9zy9z6zn17uar6bu55h7p.htm) within your SAS Folders view.

## Usage

1. Very simple! Just [pull in the Custom step](https://go.documentation.sas.com/doc/en/webeditorcdc/v_011LTS/webeditorug/p19s7ugdy0szmdn191y22muoosd6.htm) for the step you want to execute, directly into a SAS Studio Flow.

2. Refer the "About" tab on each of the individual steps for more details on what they are used for.


## Questions?
Please raise an issue for any questions.  A Frequently Asked Questions (FAQ) may be added at a later stage.
