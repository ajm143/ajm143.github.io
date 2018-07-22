---
layout: page
title: Research
permalink: http://ajm143.github.io/research/
---
<div style="float: right; background: lightgrey; width: 50%" >
<h2>Plain English</h2>

The creation of new materials is both difficult and expensive. It is very difficult to “see” the structure of these materials over the length scales that they work and very expensive to create prototype materials to test. Whilst experimental physics can use x-rays, high energy electrons or neutrons to infer the structure of these materials, this inference is made much more robust when combined with theoretical predictions of the kinds of structures that can be formed. In a computer we use quantum mechanical calculations to simulate the results of these kinds of experiments, helping to understand materials and suggest new materials with the kind of properties desired.
</div>

# Energy Materials
![Amorphous silica]({{ site.url }}/images/Amorphous.png){:style="float: left;margin-right: 7px;margin-top: 7px;height: 200px"}

Silicon is the next wonder material for lithium-ion batteries, having a theoretical capacity some 10 times greater than the current graphitic anode. However, there are many obstacles to be overcome such as anode pulverisation, irreversible lithium losses and huge volume changes before the their potential.

We have a long running collaboration with [Prof Clare Grey](https://www.ch.cam.ac.uk/group/grey/) and [Prof Chris Pickard](https://www.msm.cam.ac.uk/people/pickard) using the *ab initio* random structure searching method (AIRSS) to predict the stable phases of electrodes that occur as a lithium-ion battery charges.

Over the course of the project we have found new phases of lithium silicides, lithium germanides, lithium phosphides and lithium sulphides, including new defect and high-pressure phases.


# Ab initio Prediction of Solid-Solid Interfaces in Batteries
![Amorphous silica]({{ site.url }}/images/Amorphous.png){:style="float: right;margin-right: 7px;margin-top: 7px;height: 200px"}

Conventional rechargeable lithium-ion batteries (LIBs) utilise solid electrodes and liquid electrolytes. Combustible organic electrolytes pose potential safety risks, including volatilisation, flammability and even explosion. Solid-state (SS) inorganic electrolytes have the potential to eliminate these safety concerns, while providing high-energy LIBs. Two major challenges, however, have been hindering the practical high-performance all-SS battery applications: (1) the rather low ionic conductivities of SS electrolytes compared to liquid counterparts and (2) high resistance at the electrolyte/electrode interfaces that further curtails the ion migration. Sulfide-based electrolytes are a possible solution for the former, displaying ionic conductivities comparable to the organic counterparts, with potential enhancements by dopants. Besides, the interfacial resistances can be lowered by a rational design of the interfaces and the use of buffer layers.

To tackle these issues, an automated computational procedure is devised in our group for predicting novel SS electrode/electrolyte interfaces with lower interfacial resistances and high ionic conductivities. The procedure comprises several steps, first of which involves the generation of convex hulls by pre-screening the bulk structures of sulfide-based electrolytes with diverse compositions, phases, vacancies and doping. Subsequently, the promising electrolyte materials are screened this time for their ionic conductivity using molecular dynamics addressing Li-ion conduction. Stable surfaces of the selected bulk structures are then generated through random cuts and interfaced with the known cathode surfaces (e.g. LiCoO2, Li-metal), while minimising the lattice mismatch. Our research group’s ab initio random structure searching (AIRSS) code is used for the random search of the initial structures, and for introducing possible dopants and vacancies into the lattices. All electronic structure calculations are performed with the plane-wave density functional theory (DFT) using the CASTEP code.


# Point-defects
![Amorphous silica]({{ site.url }}/images/Amorphous.png){:style="float: left;margin-right: 7px;margin-top: 7px;height: 200px"}

We are interested in the atomic and electronic structure of impurities in batteries, semiconductors and ceramics. Using AIRSS we predict the low energy structures at various impurity concentrations. We have various ways to include entropy into the final results. Point-defects in materials are especially difficult to determine experimentally – the standard technique of x-ray diffraction is not possible – and it is also very challenging to predict their structure theoretically.

The traditional way of predicting defect structures involved intuition based on similar defects. For ex- ample by adding hydrogen to dangling bonds of the lowest-energy silicon self-interstitial defect{I},to obtain the{I,H} complex. Using d-AIRSS I found a configuration with formation energy 0.14eV lower than this. This work is mainly in collaboration with Prof Richard Needs in Cambridge.

In collaboration with Dr Dorothy Duffy's group at University College London we predicted the native defects in zirconolite: a synthetic rock used for high-level nuclear waste encapsulation. Gas bubble formation in these materials would cause cracks to form in the casings leading to environmental nuclear contamination. Simulation is essential to such materials, since we cannot perform experiments over their expected lifetime of thousands of years. We showed that there is a significant dependence on charge states for the vacancy defect structures. O2 molecules form in certain charge states of Ti and Zr vacancies. Furthermore, using the He nucleus as a model for the α-particle, we calculated barrier heights of He migration and showed that it was unfavourable for He to cluster at the concentrations studied.


# Theoretical Spectroscopy
![Amorphous silica]({{ site.url }}/images/Amorphous.png){:style="float: right;margin-right: 7px;margin-top: 7px;height: 200px"}

Producing high-quality density of states plots from Kohn-Sham eigenvalues is important for understanding the electronic structure and position of impurity states. Simple Gaussian smearing is ineffective due to the nature of dispersive bulk and localized defect states whereas the linear tetrahedron method is interpolative and will always avoid band crossings.

In collaboration with Prof Jonathan Yates and Dr Rebecca Nicholls at the University of Oxford we author the OptaDOS code. OptaDOS is a code for calculating optical, core-level excitation spectra along with full, partial and joint electronic density of states (DOS). At present OptaDOS interfaces with CASTEP and ONETEP output files, although it is extendible to perform calculations on any set of band eigenvalues and their derivatives generated by any electronic structure code.

OptaDOS is open source an can be freely downloaded by the scientific community from www.optados.org and is used by many research groups around the world

# Encapsulation in Nanotubes
![Amorphous silica]({{ site.url }}/images/Amorphous.png){:style="float: left;margin-right: 7px;margin-top: 7px;height: 200px"}

In collaboration with Drs David Quigely and Jeremy Sloan at the University of Warwick. We predict the structure of tiny crystals that can form inside carbon nanotubes.

The global demand for smaller and more energy efficient devices has been sustained by a steady decrease in the scale on which silicon microelectronics can be manufactured, from 65nm processes in the mid 2000s to 14nm in the very latest Intel processors. To continue this trend beyond the mid 2020s devices with dimensions of just 1-2nm will be required, likely using alternatives to silicon.

In this regime, the cross section of a wire might be no more than 2x2 or 3x3 atoms across, where the relevant materials physics is dominated by surface and confinement effects leading to dramatically different structural and electronic properties to the corresponding bulk material. Such wires can be formed by crystallisation of a molten salt within carbon nanotubes (CNTs) of "Buckytubes", leading to the smallest cross section nano crystals possible, sometimes referred to as Feynman crystals.

Research into the fundamental materials physics of these CNT-encapsulated structures is still in its infancy, with UK experimentalists leading the way. Particularly exciting recent work by one of the applicants (Sloan) has demonstrated the possibility of these wires undergoing transitions between nano-crystalline structures with markedly different properties, in response to bending strain in the CNT. These "phase change" properties open the way for nanoscale electromechanical switches and non-volatile memory, as well as providing a playground for fundamental studies of phase changes at the smallest length scale possible in a material.

Our aim with the current project, inspired by these results, is to develop a computational modelling capability to aid in interpretation of experiments, understand the origin of the phase change behaviour, and guide our experimental colleagues toward compounds with potentially advantageous properties. Counterintuitively, due to a reduction in symmetry, the computational expense of simulating nanowires can be more demanding when compared to bulk crystals. We will address the limitations of currently available modelling tools when applied to these systems. This will involve significant modifications to existing software and a rigorous study of the various approximations one might employ to increase the tractability of simulations.

We will apply cutting-edge methods in structure prediction to these systems, a non-trivial exercise due to the possibility wires with non-crystalline (e.g. helical) symmetry, and connect directly to relevant experiments by computing spectra related to the encapsulated wire's electronic and vibrational properties. Finally, we will study the thermodynamics and kinetics of nano-crystalline phase change, developing an understanding of when and how rapidly structural changes are affected to assess the utility of this mechanism for device applications.
