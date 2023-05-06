---
speakers:
  - Jordan Culp
name: "A Markovian Neural Barcode Representing Mesoscale Cortical Spatiotemporal Dynamics"
categories:
  - MS
hide: no
---
In-vivo mesoscale recordings from head-fixed mice capture cortical calcium dynamics across the whole mouse brain. These recordings provide us with an over-arching view of the spatio-temporal activity of highly connected populations of neurons in the mouse cortex. These mesoscale imaging data sets are difficult to analyze and model though with standard methods due to their large size, particularly across multiple comparisons, where a single recording may require many gigabytes of memory.  We propose that the cortical calcium dynamics of the mouse brain, as detected by mesoscale imaging, have a compact and predictable lower-dimensional representation. 

To construct this lower-dimensional representation, we implement a Continuous Time Markov Chain (CTMC) model with a novel state-space discretization approach that allows us to represent a continuous mesoscale recording with a corresponding CTMC model which tracks calcium dynamics as they temporally move across discrete state space zones.  Additionally, we concatenate the features of the Markov model (transition probabilities and dwell times) into a “Neural Barcode” for each recording. Our novel Neural Barcode approach reveals the structure of the activity motifs that describe a recording's temporal dynamics and allows for comparison across multiple recordings.  

Across multiple mesoscale datasets, our methodology has found statistically significant results under experimental protocols where model organisms have been subject to; a repeated protocol where robust individual animal signatures are inherent in the temporal calcium dynamics; the change in dynamics due to visual stimuli and induced seizure; and pharmacological effects, particularly with classes of drugs whose interventions are commonly used in treatments for neuropsychiatric disease.  

In summary, our Markovian Neural Barcode is a novel method leveraging the transitions between motifs of cortical activity that succinctly describe the inherent mesoscale activity patterns that represent normative and pathological brain function.
