---
layout: default
title: Research
---

### Research background


By training I am a theoretical computer scientist with the focus on artificial intelligence and machine learning. Towards the end of my
studies, I have increasingly often tapped neuroscience and psychology for inspirations on how to build intelligent systems.
This dual interest lead me to join a program in [Neuroinformatics](http://www.anc.ed.ac.uk/dtc/) at the [Unviersity of Edinburgh](http://www.ed.ac.uk/home), where my interest in the brain
grew further, eventully leading to my PhD thesis on the topic of [Development of functional properties in primary visual cortex](https://www.era.lib.ed.ac.uk/handle/1842/4875) under the
supervision of [James Bednar](http://homepages.inf.ed.ac.uk/jbednar/). My first post-doctoral post was in the lab of [Tom-Mrsic Flogel](http://www.biozentrum.unibas.ch/research/groups-platforms/overview/unit/mrsic-flogel/) at UCL where I had the chance to
brush up my machine learning skills while investigating novel ways to estimate receptive fields in local populations of mouse
primary visual cortex neurons. Currently I am further pursuing my interset in the visual cortex at <a href="http://www.unic.cnrs-gif.fr/teams.html">UNIC</a> CNRS by building large-scale
comprehensive model of cat primary visual cortex.

<br>

### Current research interests

* computational modelling
* visual system
* computational neuroscience
* system identification
* machine learning

<br>


### Available student projects

This is a list of projects available for interested students. Most projects are designed to be completed
within 3 to 6 month, but some can be expanded into full PhD scope. If you are interested in working on any 
of the following projects please [contact me](/index.html).

* <a href="javascript:void(0)" onclick="$('#project1').toggle();">Graphical user interface for Mozaik datastore and analysis</a>    
    <small id="project1" class="studentprojectlist" style="display: none;">
        <a href="https://github.com/antolikjan/mozaik">Mozaik</a> is a an automated workflow for large-scale neural simulations.
        Mozaik automatically records data from simulations, annotates it with metadata regarding experimental context, and stores
        them in an internal data-store. An query based interface allows analysis and visualization modules to efficiently navigate
        through the stored data based on the attached metadata. Currently, Mozaik offers only programatic API to perform these interactions
        with data-store. The goal of this project would be to write a graphical user interface frontend to the Mozaik data-store, that will
        allow users to conveniently and interactively navigate and select data from the data-store and subsequently execute on them anaysis and
        visualization routines from Mozaik libraries.      
    </small> 
* <a href="javascript:void(0)" onclick="$('#project2').toggle();">Mozaik data-store module based on object oriented database</a><br>
    <small id="project2" class="studentprojectlist" style="display: none;">
        <a href="https://github.com/antolikjan/mozaik">Mozaik</a> is a an automated workflow for large-scale neural simulations,
        with a highly modular architecture. One of the core Mozaik modules is a data-store, in which recordings from simulations richly
        annotated with metadata regarding experimental context are stored. Currently the data-store module is implemented as a
        database-like system based on [Neo](http://neuralensemble.org/neo/) library for internal representation of recorded data. 
        The goal of this project is to develop an alternative data-store module based around dedicated key-value database such as
        [BerkelyDB](http://www.oracle.com/technetwork/database/database-technologies/berkeleydb/overview/index.html) or [CodernityDB](http://labs.codernity.com/codernitydb/).
    </small>
* <a href="javascript:void(0)" onclick="$('#project3').toggle();">A model inspection/visualization tool for Mozaik</a><br>
    <small id="project3"  class="studentprojectlist" style="display: none;">
        <a href="https://github.com/antolikjan/mozaik">Mozaik</a> is a an automated workflow for large-scale neural simulations.
        The [model of primary visual cortex](/projects.html) developed in our lab, and implemented in Mozaik, has a complex connectivity structure. 
        Although there are various tests that the connectivity has been realized as expected, currently, there is no easy way to 
        visualize the network spatial structure and connectivity in [Mozaik](https://github.com/antolikjan/mozaik). The aim of this project is to develop a 
        model inspection and visualization tool, for Mozaik, possibly building on existing tools such as [ConnPlotter](http://arken.umb.no/~plesser/software.html), [Moogli](http://moose.ncbs.res.in/moogli/), and [NeurAnim](http://software.incf.org/software/neuranim).
    </small>
* <a href="javascript:void(0)" onclick="$('#project4').toggle();">Unifying retinal mozaik model with activity based development</a><br>
    <small id="project4" class="studentprojectlist" style="display: none;">
        During post-natal development, primary visual cortex undergoes remarkable functional organization resulting - among others - in expression
        of topologically smooth orientation map across it's surface. The most common type of explenation for this phenomena is activity based development,
        whereby internally generated or visually driven activity coupled with plasticity in the thalamo-cortical and corico-cortical pathway
        induces gradual establishment of the orientation maps. [LISSOM](http://ioam.github.io/topographica/Tutorials/GCAL_Tutorial.html) based familiy of models is an example of such activity + plasticity driven models.
        An alternative explanation has been proposed by [Ringach](http://jn.physiology.org/content/92/1/468) (see also [this](http://www.nature.com/neuro/journal/v14/n7/full/nn.2824.html)) , in which the initial orientation maps are directly established by
        the very specific geometric properties of retinal ganglion cells RFs positions in visual space: [retinal mozaiks](http://labs.nri.ucsb.edu/reese/benjamin/PubsRetinalMosaics.html). However, this explanation
        can account only for initial very weak orientation maps, and low orienation selectivities of individual neurons in particular, and it is clear that
        the system has to undergo major further refinement in order to match the experimentally observed adult state. The goal of this project is to combine
        the two hypothesis of orientation map development and investigate their possible interactions.
        Specifically retinal mozaiks will be introduced into a LISSOM model, thus inducing the initial orientation maps based on Ringach et al. theory.
        This will be followed by simulation of the activity and plasticity driven development, which should lead to refinement of the intial maps.
        The correspondance between the initial retinal mozaik induced map with the final developed map will be assesed, and possible advantages of such
        dual orientation map development mechanism will be investigated.
    </small>
* <a href="javascript:void(0)" onclick="$('#project5').toggle();">Deployment of Mozaik on a HPC platrform.</a><br>
    <small id="project5" class="studentprojectlist" style="display: none;">
        [Mozaik](https://github.com/antolikjan/mozaik) is a an automated workflow for large-scale neural simulations.
        Mozaik depends on a moderate software stack including [PyNN](http://neuralensemble.org/PyNN/) as a simulator independent
        model specification language, and [Nest](http://www.nest-initiative.org/) as the simulator of choice in our projects.
        Currently we deploy Mozaik (together with the software stack) on a local cluster, however already at this relatively 
        small scale we are aware of number of inefficiencies in terms of its performance in the parallel environment. Furthermore, in future we would like 
        to deploy Mozaik on a large-scale High Performance Computing (HPC) platform such as [?](). The goal of this project is to test and optimize Mozaik and it's underlying
        software stack to run efficiently on the local cluster, and subsequently scale it up to a large-scale HPC platform.
        This project is suitable for students with experience and interest in parallel programming and HPC.
    </small>
     
    
    
    
    
