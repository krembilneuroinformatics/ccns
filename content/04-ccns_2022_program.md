+++
title = "04 - CCNS 2022 Program"
weight = 20
draft = false
+++

### CCNSv3 will take place on June 6-7, 2022, and registration is open [here](https://www.crowdcast.io/e/ccnsv3/register).

### Submit your abstract for a Trainee Talk [here](https://forms.gle/thSZWMyr4uxHQLJi9) by May 23 for full consideration.

## Program
### Monday, June 6
* 8:45 AM EDT: **Welcome and Introduction: Dr. Scott Rich**
* 9:00 AM EDT: **Tutorial Talk: Dr. Alexandra Chatzikalymniou** (Neural Circuit Modeling)
* 9:25 AM EDT: **Dr. Willy Wong** (Neural Circuit Modeling) 
* 9:50 AM EDT: **Break**
* 10:00 AM EDT: **Dr. Steven Prescott** (Neural Circuit Modeling) 
* 10:25 AM EDT: **Dr. Carmen Canavier** (Neural Circuit Modeling)
* 10:50 AM EDT: **Break**
* 11:00 AM EDT: **Keynote Address: Dr. Gaute Einevoll** (Neural Circuit Modeling)
* 12:00 PM EDT: **Lunch Break**
* 1:00 PM EDT: **Tutorial Talk** (Neuro-AI)
* 1:25 PM EDT: **Dr. Richard Naud** (Neuro-AI)
* 2:00 PM EDT: **Break**
* 2:10 PM EDT: **Dr. Milad Lankarany** (Neuro-AI)
* 2:45 PM EDT: **Dr. Blake Richards** (Neuro-AI)
* 3:20 PM EDT: **Break**
* 3:25 PM EDT: **Dr. Wilten Nicola** (Neuro-AI)
* 4:00 PM EDT: **Break**
* 4:05 PM EDT: **Trainee Spotlight Talks: Laura Medlock and Ann Huang**
* 4:40 PM EDT: **Parallel Trainee Talks**


### Tuesday, June 7
* 8:40 AM EDT: **Trainee Spotlight Talks: Andrea Luppi and Annemarie Wolff**
* 9:15 AM EDT: **Parallel Trainee Talks**
* 9:45 AM EDT: **Break**
* 9:50 AM EDT: **Tutorial Talk: Dr. Kelly Shen** (Large-Scale Brain Modeling)
* 10:15 AM EDT: **Dr. Davide Momi** (Large-Scale Brain Modeling)
* 10:40 AM EDT: **Break**
* 10:50 AM EDT: **Laura Suarez** (Large-Scale Brain Modeling)
* 11:15 AM EDT: **Dr. Jeremie Lefebvre** (Large-Scale Brain Modeling)
* 11:40 AM EDT: **Break**
* 11:50 PM EDT: **Keynote Address: Dr. Viktor Jirsa** (Large-Scale Brain Modeling)
* 12:50 PM EDT: **Lunch Break**
* 1:20 PM EDT: **Panel Discussion**
* 2:00 PM EDT: **Dr. Jacqueline Scholl** (Cognitive Modeling)
* 2:35 PM EDT: **Casper Hesp** (Cognitive Modeling)
* 3:10 PM EDT: **Break**
* 3:20 PM EDT: **Tutorial Talk: Dr. Andreea Diaconescu** (Cognitive Modeling)
* 3:45 PM EDT: **Break**
* 3:50 PM EDT: **Keynote Address: Dr. Cendri Hutcherson** (Cognitive Modeling)
* 4:50 PM EDT: **Concluding Remarks**

## Trainee Abstracts
# Monday Spotlight Talks
* **Laura Medlock**: Pain-related sensory input is processed in the spinal dorsal horn (SDH) before being relayed to the brain. That processing profoundly influences whether tactile stimuli are correctly or incorrectly perceived as painful. Different types of excitatory and inhibitory neurons have been identified in the SDH, and some of their connectivity is understood, but how the overall circuit processes sensory input or how that processing is disrupted under chronic pain conditions remains unclear. To explore sensory processing in the SDH, we developed a computational model of the circuit that is tightly constrained by experimental data. Our model comprises conductance-based neuron models that reproduce the characteristic firing patterns of spinal neurons. Different spinal neuron populations were synaptically connected according to available qualitative data. Using a genetic algorithm, synaptic weights were optimized to reproduce projection neuron firing rates (model output) in response to primary afferent firing rates (model input) across a range of mechanical stimulus intensities. This optimization revealed that distinct synaptic weight combinations could produce equivalent SDH circuit function, revealing degeneracy that may underlie heterogeneous responses of different circuits to perturbations or pathological insults. To validate our model, we verified that it responded to reduction of inhibition (i.e. disinhibition) and ablation of specific neuron types in a manner consistent with experiments. Our validated model offers a valuable resource for interpreting experimental results and testing hypotheses in silico to plan experiments for examining normal and pathological SDH circuit function.
* **Ann Huang**: The ability to encode “what happened when” is central to the accurate representation of episodic memory. Previous neurophysiology studies have reported groups of cells that fire sequentially during the delay period of working memory tasks. These cells are commonly called “time cells” because they are thought to serve as the neural substrates for tracking time. However, the representation of time in “time cells” is confounded by other task variables, such as the animal’s running speed, spatial location, and sensory experience. Previous studies that used statistical methods to parse the information encoded by “time cells” are also fundamentally flawed in their statistical assumptions. Here we hypothesize that rather than encoding the time elapsed per se, the so-called “time cells” emerge as an epiphenomenon when encoding any behaviorally relevant variables that unroll over time. We trained an artificial agent on a Trial-Unique Nonmatch-to-Location (TUNL) working memory task and recorded the activity from the recurrent neural network of the artificial agent. Using neuroscience-based and information-theoretic analysis, we showed that (1) apparent “time cells” emerge in the recurrent neural network during the task (2) “time cells” show heterogeneous representations of time elapsed, spatial location, and incoming sensory stimuli (3) the apparent “time cells” are more strongly modulated by spatial location rather than time elapsed during the task. Our study serves as a proof of principle that in recurrent neural networks trained on working memory tasks, the apparent “time cells” represent behaviorally relevant variables that unfolds in time rather than the time elapsed per se. 
