## **Experimental Nanoscale Physics**

This is a repository for data analysis notebooks done in Jupyter for three experiments conducted in 547 Experimental Nanoscale physics. Each experiment largely consists of two main teaching principles: learning experimental techniques that come along with fabrication of the device of interest or performing relevant measurements and learning about the theoretical background behind the phenomena that we want to investigate. 

In this course, we performed three hands on experiments investigating properties of physical systems, collected data, and analyzed the results. 
  - **Semiconductor Experiment:** Investigating the current vs voltage behavior of a metal-semiconductor junction (in this case: Gold/Titanium and Silicon)
  - **Graphene Experiment:** Exploring the current as a function of applied back gate voltage for a graphene field effect transistor (that we our selves manufactured) 
  - **Johnson Noise and Equivalent Bandwidth Experiment:** Experimentally verify Johnson noise relationship/dependence on bandwidth 

### **Semiconductor Experiment**
A metal-semiconductor junction behaves as a Schottky diode. That is, at the interface between the two materials, a potential barrier forms that allows for electrons to flow easier across in one direction while restricting flow in the other direction; that is, it acts as a diode. As a result, its current dependency on voltage theoretically behaves according to the diode curve where for forward bias the current exhibits an exponential curve and for reverse bias the current remains flat (until breakdown). 

Additionally, the Schottky diode has a few observables that characterize its electronic behavior one of which being the Schottky barrier height measured in eV. Using a linearized plot and performing a linear fit allows for the extraction of this barrier height as one of the fitted parameters which we can then compare to existing literature. 

### ** Graphene Experiment ** 
