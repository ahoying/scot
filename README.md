![ScotLogo](https://raw.githubusercontent.com/sandialabs/scot/master/deploy/scot_logo_highrez_64x64.png)
Sandia Cyber Omni Tracker
=========================


![version](http://img.shields.io/badge/version-3.4-orange.svg)
[![Documentation Status][docs-badge]](http://scot.readthedocs.org/en/latest/)
[![license](http://img.shields.io/badge/license-Apache%202-red.svg)](https://github.com/sandialabs/scot/blob/master/LICENSE)
[![Circle CI](https://circleci.com/gh/sandialabs/scot.svg?style=shield&circle-token=1f0dc7e770297ca791738bf0a40d5c89c577fc39)](https://circleci.com/gh/sandialabs/scot)
[![wercker status](https://app.wercker.com/status/28cd7a2ff338f464ff5489f3fe970e8f/s "wercker status")](https://app.wercker.com/project/bykey/28cd7a2ff338f464ff5489f3fe970e8f)
[![Build Status](https://travis-ci.org/sandialabs/scot.svg?branch=master)](https://travis-ci.org/sandialabs/scot)

SCOT Online Demo
----------------
Give SCOT a try [here](https://54.245.95.189) with the **username**: `admin`/ **password**: `admin`

> ###### For this demo, the app is reverted every hour on the hour.  We are currently using a self signed cert for the demo, but that will change in the next few days.

Documentation and Install
-------------------------
Read our [documentation](http://scot.readthedocs.org/en/latest/install.html) at Read The Docs.

Overview
--------

The Sandia Cyber Omni Tracker (SCOT) is a cyber security incident response management system and knowledge base. Designed by cyber security incident responders, SCOT provides a new approach to manage security alerts, analyze data for deeper patterns, coordinate team efforts, and capture team knowledge.  SCOT integrates with existing security applications to provide a consistent, easy to use interface that enhances analyst effectiveness.

![Scot-flow](https://raw.githubusercontent.com/sandialabs/scot/master/docs/scot-where.jpg)

Customer Need
-------------

Incident response (IR) teams utilize many systems to detect, collect and analyze cyber security event data.  These systems, while solving pieces of the puzzle, often fail to give the analyst a holistic view of what is happening and their team’s response to those events.  Many systems do not have the flexibility to work with the IR processes to research and document those activities.  Research is not easily shared and searchable, so the team’s effectiveness decreases, especially when key personnel are on vacation or take other positions.  Without a ready corpus of examples of past events, training new team members becomes a lengthy process.  Each additional tool adds cognitive load to the analyst and the tool’s maintenance needs take the analyst away from the primary task of IR.


Our Approach
------------

Focused on removing the friction between analysts and their tools, SCOT enables analysts to document and share their research and response efforts.  As a software suite that integrates data from detectors, analysis, and other information sources, it provides real time updates of the team’s work to keep the team informed and coordinated.  SCOT automatically identifies indicators to help the analyst discover and respond to advanced threats.  Centralization of the data reduces the contextual shifts necessary to access each detection system.  Fusing detection data with the accumulated team knowledge allows the team to quickly discover that a new alert might be part of a larger campaign.  In addition, SCOT automates and simplifies common analyst tasks to increase analyst’s effectiveness by freeing them to concentrate on cyber security – not tool mastery.

Benefits
--------

The number of alerts Sandia’s IR team has seen has nearly doubled in the past several years.  SCOT enabled the team to keep up with this increase without adding additional team members. As a training tool, new team members started contributing in weeks, instead of months.  In just over 4 years SCOT has amassed a database of over 700K indicators from analyst and alert input.  These indicators help the team spot an adversary’s methods and tactics, as well as highlighting common targets within the enterprise.   SCOT, processed over 1.6 million alerts since deployment, while maintaining 99.9% availability, and required minimal administration. SCOT is fully scalable to meet higher loads.

Competitive Advantage
---------------------

Sandia's incident response team realized several advantages using SCOT over other solutions.  SCOT's ease of use eliminated the steep learning curve of traditional SIEMS and captured team knowledge much more effectively.  Designed for cyber security, SCOT allows the IR team to enter data easily, instead of struggling to conform to a ticketing system designed for other purposes.  While workflow systems handle linear workflows easily, SCOT is purpose built for the looping nature of cyber security investigations.  SCOT also solves the challenges of keeping wikis, spreadsheets and documents up-to-date and accessible to an IR team.  While top-notch analysts may be able to keep everything in their brains, SCOT will capture their knowledge for when they go on vacation or to other employment.

![Scot-venn](https://raw.githubusercontent.com/sandialabs/scot/master/docs/scot-venn.png)

Contact US
----------
**Vulnerabilities**: <mailto:scot-dev@sandia.gov>

**Bugs/Feature Requests**: Use our GitHub [issue](https://github.com/sandialabs/scot/issues) tracking

**Collaboration:** <mailto:scot-dev@sandia.gov>

[docs-badge]: http://img.shields.io/badge/docs-latest-brightgreen.svg
