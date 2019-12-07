.. Ptest Method documentation master file, created by
   sphinx-quickstart on Fri Jul 13 13:04:20 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

#####################
Obligatory Disclaimer
#####################

This documentation is provided free-of-charge for the sole purposes of education and network security enhancement. 
Github, Maximevilla, and editing contributors hold no responsibilty for the quality of information provided, or its subsequent effects on hardware, software, or firmware. Users and consumers of this information are advised to be aware of all legalities, both locally, nationally, and internationally, surrounding its content prior to use. If the intent-of-use for this information is beyond the scope of the forementioned, then you are not provided authorization to continue. 


Ptest Method Documentation
==========================

This repository is a knowledge-base of Pentesting (PTest) skills and is inspired by https://bitvijays.github.io 
Much of the content at this point is the same.

If you happen to encounter an issue with any of the features or instructions presented, be sure to type the nature of your error into your favorite search engine. Many of the most common issues are already solved and will be easy to find.

#####################
Essentials Series
#####################

The 'Essentials Series' covers the basic understanding for those entering the field of CyberSecurity.

- :doc:`CyberSecurity in an Enterprise <LFF-ESS-P0A-CyberSecurityEnterprise>` : IT Technical challenges faced by a company during their transformation from a start-up of two people growing to Micro, Small, Medium-sized, larger size company and their solutions.
- :doc:`Linux Basics <LFF-ESS-P0B-LinuxEssentials>` : Essential Linux commands and concepts required in the Infosec field.

.. toctree::
   :maxdepth: 2
   :caption: The Essentials

   LFF-ESS-P0A-CyberSecurityEnterprise
   LFF-ESS-P0B-LinuxEssentials


#############################
Infrastructure Pentest Series
#############################

The Infrastructure Pentest Series covers all the phases of infrastructure as described by
`The Penetration Testing Execution Standard <http://www.pentest-standard.org/>`_.

- :doc:`Intelligence Gathering <LFF-IPS-P1-IntelligenceGathering>` : Technical steps to perform during the information gathering phase of an organization, and figure out the attack surface-area.
- :doc:`Vulnerability Analysis <LFF-IPS-P2-VulnerabilityAnalysis>` : Exploring different services running on different ports of a machine by utilizing metasploit-fu, nmap, or various other tools.
- :doc:`Exploitation <LFF-IPS-P3-Exploitation>`                    : Enumeration methods that can be used after compromising a domain users credentials and remote code execution methods after compromising administrative credentials.
- :doc:`Post Exploitation <LFF-IPS-P4-PostExploitation>`           : Different methods to gather credentials after getting an administrative remote shell. Also, performing post-exploitation to leave high-impact to C-Level executives that is also covered in this section.
- :doc:`Reporting <LFF-IPS-P5-Reporting>`                          : Open-Source ways to automate report writing after a successfull Pentest.
- :doc:`Configuration Review <LFF-IPS-P6-ConfigurationReview>`     : Methods to perform configuration review for the switches, routers, firewall, and endpoint devices.


.. toctree::
   :maxdepth: 2
   :caption: Pentest Stages

   LFF-IPS-P1-IntelligenceGathering
   LFF-IPS-P2-VulnerabilityAnalysis
   LFF-IPS-P3-Exploitation
   LFF-IPS-P4-PostExploitation
   LFF-IPS-P5-Reporting
   LFF-IPS-P6-ConfigurationReview
   LFFWirelessPentesting


#############################
Hardening Series
#############################

  The Hardening Series covers all procedures required to be more secure.

- :doc:`Securing Debian <LFFSecuringDebiang>` : Technical steps to harden Debian systems.


.. toctree::
   :maxdepth: 2
   :caption: Hardening

   LFFSecuringDebian


#############################
Metasploit Documentation
#############################

Here you can locate the documentation of some tools.

- :doc:`Metasploit Fundamentals <MetasploitFundamentals>` : How to use Metasploit. Forked from Metasploit unlisted.


.. toctree::
   :maxdepth: 2
   :caption: Metasploit Fundamentals

   MetasploitFundamentals


#############################
Other Tools
#############################


.. toctree::
   :maxdepth: 2
   :caption: Other Tools

   pupy
   cme


Indices and Tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
