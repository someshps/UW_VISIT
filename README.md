# Bayesian Optimisation for improving paint adhesion
This repository contains work done by me during Visiting International Student Internship & Training (VISIT) program at Composite Materials and Manufacturing Lab at University of Washington, Seattle. 

The goal of the project was to improve the paint adhesion on a class of composites (tetra-functional epoxy resin) being used in many applications including aircrafts. Research has shown that plasma treatment of such composite surface increases the chemical reactivity of the surface and hence improves paint adhesion. But, this is not a monotonic correlation and a very high surface reactivity may actually result in decreasing the paint adhesion. The process through which surface is plasma treated determines the surface reactivity and hence paint adhesion. 

There were three aspects of the project that were handled by me:
1. Designing how many experimental runs would be conducted and at which rated parameters i.e., Design oF Experiments (DOE). This was done using the concepts of Quality Engineering.
2. Image analysis of the samples on which the tape test was conducted for paint adhesion. This was done using the [ImageJ](https://imagej.net/software/imagej/).
3. Applying Bayesian Optimisation to the following plasma treatment parameters:
  3.1 Number of passes of the plasma treatment torch over the composite surface
  3.2 Translating speed of the stage on which the sample to be plasma treated is kept  
  3.3 Standoff distance of the sample from the nozzle.

Repository details:
1. Codes written for Bayesian Optimisation: [Codes](https://github.com/someshps/UW_VISIT/tree/main/UW%20Intern_23/Codes)
2. Design of Experiments code and analysis: [DOE](https://github.com/someshps/UW_VISIT/tree/main/UW%20Intern_23/DOE)
3. Experimental Data (Experiments were conducted by Ankush Nandi, PhD, UW in collaboration with [Plasmatreat](https://www.plasmatreat.com/en/) team) : [ExperimentalData](https://github.com/someshps/UW_VISIT/tree/main/UW%20Intern_23/ExperimentalData)
4. Final Internship Presentation: [Presentation](https://github.com/someshps/UW_VISIT/tree/main/UW%20Intern_23/Presentation)


The work resulted in a conference presentation. 


Nandi, A., Robinson, R., Singh, S. P., Montrowl, S., Pappas, D., Vashisth, A. (2024). Exploiting Data Science for Atmospheric Plasma Enhanced Paint Adhesion on Carbon Fiber Composites. The Composites and Advanced Materials Expo, September 2024, San Diego, CA.

The project was done under the guidance of Prof. Aniruddh Vashisth and Ankush Nandi (PhD UW). 

