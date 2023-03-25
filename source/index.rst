A pocketful of acorns
=================================================

Physical security involves controlling who has physical access to the facility, the servers, network equipment, andend-user devices. A physical penetration test can assess all physical security controls, including locks, fences, security guards, cameras, and other security measures. The test attempts to bypass the security controls to gain physical access to restricted areas, identify sensitive data, and gain entry to networks.

These types of tests tend to be expensive, and the easy stuff for fixes do not require a physical test to know one needs to improve locks, entry/exit controls to prevent tailgating, securing network ports from intruders with physical locks or network access controls, etc.

The exception is the social engineering part, in particular phishing simulations, an often used attack by real attackers, with serious consequences.

.. image:: _static/images/in-progress.png
  :alt: Forever in progress ...

----

.. toctree::
   :maxdepth: 1
   :includehidden:
   :caption: Preparation

   Build a local testlab: Additional hardware <https://red.tymyrddin.dev/projects/testlab/en/latest/docs/hardware/README.html>
   Build a local testlab: Social engineering <https://red.tymyrddin.dev/projects/testlab/en/latest/docs/se/README.html>
   Reconnaissance <https://red.tymyrddin.dev/projects/recon/en/latest/docs/physical/README.html>

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Exploiting physical security

   docs/exploits/README.md
   docs/exploits/*

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Social engineering

   docs/opsec/README.md
   docs/opsec/*
