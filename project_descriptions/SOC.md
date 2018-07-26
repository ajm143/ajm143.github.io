---
layout: page
title: "Why isn't gold silver or silver gold?"
---

Electron spin is an inherently quantum mechanical effect that has not classical analogue. Magnetism is a direct consequence of this non-classical phenomena. Many of the lighter atomic elements may be modelled within the Ising model, that is, assuming that an electron's dipole moment may be in one of two states (+1 or -1).

In heavier elements, electrons near the nucleus experience relativistic speeds, leading to spin-orbit coupling (SOC) and a breakdown of the Schrodinger picture.  Spin-orbit coupling splits electronic states that are degenerate in a non-relativistic description of quantum mechanics. The eigenfunctions of these states cannot be described by a spin-up and spin-down wavefunction, the eigenfunctions are now non-colinear, hence must be described by a two-component vector called a spinor.  (Abstract representations of a spinor include Mobius strips, where a full rotation of the system through 360 degrees exhibits a spin flip).

Due to its increased nuclear mass over, for example, silver, the absorption spectrum of gold is affected by SOC. A non-relativistic description of gold predicts it to be silver in colour!

Normally when calculating the properties of new rechargeable battery materials, SOC effects are ignored for computational efficiency arguing that battery materials must necessarily be light, and light materials do not require such a treatment. However, recent studies have shown (e.g. [1]) that even carbon can exhibit SOC, leading us to wonder if SOC should be included in the modelling of other battery materials.  Recent developments in the CASTEP[2] density-functional theory (DFT) program allow the calculation of the electronic ground state of heavy elements including SOC, so in this project we revisit some of the previously modelled materials [3,4,5] to include a relativistic treatment and ask how important is SOC in describing batteries?

(Research projects have a mind of their own, and can be tailored to the taste of the student within reason.  To give a guide to the day-to-day computational activities: CASTEP is written in Fortran90/95/08, and it is very unlikely that the student would need to do more than run the code. Our research group's structure database MATADOR is written in Python, it is more likely that some new small functionality might need coding-up. Unix-based operating systems are used throughout for preparing and running code on supercomputers, and results' subsequent analysis. Hence some familiarity with Linux/Unix and procedural computing languages would be beneficial.)

[1] https://www.nature.com/articles/ncomms2584
[2] www.castep.org
[3] Andrew J. Morris, C. P. Grey and Chris J. Pickard, Phys. Rev. B 90 054111 (2014), DOI:10.1103/PhysRevB.90.054111.
[4] M. Mayo, K. J. Griffith, C. J. Pickard and A. J. Morris, Chem. Mater. 28 2011-2021 (2016), DOI:10.1021/acs.chemmater.5b04208.
[5] Joshua M. Stratford , Martin Mayo , Phoebe K. Allan, Oliver Pecher, Olaf J. Borkiewicz, Kamila M. Wiaderek, Karena W. Chapman⊥, Chris J. Pickard, Andrew J. Morris, and Clare P. Grey, J. Am. Chem. Soc. 139 7273-7286 (2017), DOI:10.1021/jacs.7b01398.

