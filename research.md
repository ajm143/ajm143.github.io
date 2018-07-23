---
layout: page
title: Research
permalink: http://ajm143.github.io/research/
---
<div style="float: center; background: lightgrey; width: 700px;border: 10px solid lightgrey;text-align: justify" >
<h2>Plain English</h2>

The creation of new materials is both difficult and expensive. It is very difficult to “see” the structure of these materials over the length scales that they work and very expensive to create prototype materials to test. Whilst experimental physics can use x-rays, high energy electrons or neutrons to infer the structure of these materials, this inference is made much more robust when combined with theoretical predictions of the kinds of structures that can be formed. In a computer we use quantum mechanical calculations to simulate the results of these kinds of experiments, helping to understand materials and suggest new materials with the kind of properties desired.
</div>

# Battery Materials Modelling
![Li-ion Intercalation Materials]({{ site.url }}/images/batteries.png){:style="float: left;margin-right: 7px;margin-top: 7px;width: 350px"}

Silicon is the next wonder material for lithium-ion batteries, having a theoretical capacity some 10 times greater than the current graphitic anode. However, there are many obstacles to be overcome such as anode pulverisation, irreversible lithium losses and huge volume changes before the their potential.

Over the course of the project we have found new phases of lithium silicides, lithium germanides, lithium phosphides and lithium sulphides, including new defect and high-pressure phases.

**Current Project Members:**

* [Bora Karasulu]({{ site.url}}/group/current/2018/06/30/Bora_Karasulu.html)
* [Matthew Evans]({{ site.url}}/group/current/2018/06/30/Matt_Evans.html)
* [Can Kocer]({{ site.url}}/group/current/2018/06/30/Can_P_Kocer.html)
* [Angela Harper]({{ site.url}}/group/current/2018/06/30/Angela_F_Harper.html)


**Collaborators:**

We have a long running collaboration with [Prof Clare Grey](https://www.ch.cam.ac.uk/group/grey/) and [Prof Chris Pickard](https://www.msm.cam.ac.uk/people/pickard) using the *ab initio* random structure searching method (AIRSS) to predict the stable phases of electrodes that occur as a lithium-ion battery charges.

# Encapsulation in Nanotubes
![Gorgeous Nanowire Image]({{ site.url }}/images/nanowires.png){:style="float: right;margin-right: 30px;margin-top: 0px;height: 200px"}

Particularly exciting recent work by Jeremy Sloan has demonstrated the possibility of nanowires undergoing transitions between nano-crystalline structures with markedly different properties, in response to bending strain in the CNT. These "phase change" properties open the way for nanoscale electromechanical switches and non-volatile memory, as well as providing a playground for fundamental studies of phase changes at the smallest length scale possible in a material.

Our aim with the current project, inspired by these results, is to develop a computational modelling capability to aid in interpretation of experiments, understand the origin of the phase change behaviour, and guide our experimental colleagues toward compounds with potentially advantageous properties. 

**Current Project Members**

* [Jamie Wynn]({{ site.url }}/group/current/2018/06/30/Jamie_Wynn.html)
* [Kamal Goswami]({{ site.url }}/group/current/2018/06/30/Kamal_Goswami.html)

**Collaborators**

In collaboration with Drs [David Quigely](https://warwick.ac.uk/fac/sci/physics/staff/research/dquigley/) and [Jeremy Sloan](https://warwick.ac.uk/fac/sci/physics/staff/academic/jsloan/) at the University of Warwick. We predict the structure of tiny crystals that can form inside carbon nanotubes.

# Structure Prediction
![Ternary AIRSS]({{ site.url }}/images/ternary-hull.png){:style="float: left;margin-left: 0px;margin-top: 0px;height: 300px"}

<br>

In addition to using structure prediction tools to characterise systems of experimentally relevant materials, such as batteries and nanowires, we also develop our own software for crystal structure prediction which builds off of *ab initio* random structure searching (AIRSS).  Developing smarter tools for structure prediction is a key component of identifying new materials, and so our group aims to not only be users but developers as well.

<br><br>

**Current Project Members**

* [Matthew Evans]({{ site.url }}/group/current/2018/06/30/Matt_Evans.html)
* [James Darby]({{ site.url }}/group/current/2018/06/30/James_Darby.html)
* [Jamie Wynn]({{ site.url }}/group/current/2018/06/30/Jamie_Wynn.html)

**Software**

* <a href="http://www.castep.org/"><code>CASTEP</code></a>
* <a href="http://www.castep.org/Tutorials/AIRSS"><code>AIRSS</code></a>
* <a href="http://matador.science"><code>matador</code></a>
* <a href="http://www.tcm.phy.cam.ac.uk/~me388/ilustrado"><code>ilustrado</code></a>


# Theoretical Spectroscopy
![DOS]({{ site.url }}/images/optados-image.png){:style="float: right;margin-right: 7px;margin-top: 7px;height: 200px"}

Producing high-quality density of states plots from Kohn-Sham eigenvalues is important for understanding the electronic structure and position of impurity states. Simple Gaussian smearing is ineffective due to the nature of dispersive bulk and localized defect states whereas the linear tetrahedron method is interpolative and will always avoid band crossings.

<a href="http://www.tcm.phy.cam.ac.uk/~ajm255/optados/index.html"><code>OptaDOS</code></a> is a code for calculating optical, core-level excitation spectra along with full, partial and joint electronic density of states (DOS). At present <a href="http://www.tcm.phy.cam.ac.uk/~ajm255/optados/index.html"><code>OptaDOS</code></a>interfaces with CASTEP and ONETEP output files, although it is extendible to perform calculations on any set of band eigenvalues and their derivatives generated by any electronic structure code.

<a href="http://www.tcm.phy.cam.ac.uk/~ajm255/optados/index.html"><code>OptaDOS</code></a> is open source an can be freely [downloaded](http://www.tcm.phy.cam.ac.uk/~ajm255/optados/download.html) by the scientific community and is used by many research groups around the world

**Current Project Members**

* [Andrew Morris]({{ site.url }}/group/current/2018/06/30/Andrew_Morris.html)
* [Can Kocer]({{ site.url }}/group/current/2018/06/30/Can_P_Kocer.html)

**Collaborators**

In collaboration with Prof [Jonathan Yates](http://www.materials.ox.ac.uk/peoplepages/yates.html) and Dr [Rebecca Nicholls](http://www.materials.ox.ac.uk/peoplepages/nicholls.html) at the University of Oxford we author the OptaDOS code. 

