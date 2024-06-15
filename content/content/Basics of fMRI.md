## fMRI: Blood Oxygen Level-Dependent Signal

This note discussed the Blood Oxygen Level-Dependent (BOLD) signal, the basis of functional magnetic resonance imaging (fMRI). 

**Basic Principles:**
 
- Our brains have capillaries, arteries, and veins supplying oxygenated blood.
- During rest, a steady ratio of oxygenated vs. deoxygenated hemoglobin exists.
- Active brain regions require more oxygen for processing, leading to a local increase in deoxygenated hemoglobin.
- Deoxygenated hemoglobin disrupts the magnetic field compared to oxygenated hemoglobin.
![[Pasted image 20240513155155.png]]
**fMRI Signal Measurement:**

- Radio waves nudge protons in the brain, causing them to precess (spin).
- Relaxation time is measured - the time it takes for protons to return to alignment.
- T2* relaxation reflects local magnetic field variations caused by oxygenation levels.
- BOLD fMRI measures changes in T2* relaxation to indirectly assess brain activity.
![[Pasted image 20240530151142.png]]


**BOLD Signal :**
![[Pasted image 20240530151955.png]]

**BOLD fMRI and Oxygen Depletion**

- Astrocytes absorb oxygen to replenish oxygen and glucose metabolism in firing cells.
- Hemoglobin dephasing, caused by oxygen absorption, changes the MRI signal.
- Deoxygenated blood causes more signal distortion than oxygenated blood.
- BOLD signal allows us to infer brain activity by detecting changes in oxygenation.

**The Hemodynamic Response Function**

- Brain activation initially reduces the MRI signal due to oxygen depletion.
- Blood supply increases in response to activation, causing the BOLD signal to rise.
- When the stimulus stops, oxygenation and the MRI signal overshoot and then undershoot before returning to baseline.
- ![[Pasted image 20240530153310.png]]
- This entire cycle is called the hemodynamic response function.

**BOLD fMRI Does Not Measure Neural Activity Directly**

- BOLD fMRI measures metabolic demands, specifically oxygen consumption of active neurons.
- The hemodynamic response function reflects the change in the fMRI signal triggered by neural activity.

**Physiological Basis of the BOLD Signal**

- Action potentials in presynaptic terminals cause neurotransmitter release.
- Neurotransmitters bind to postsynaptic ion channels, allowing ions to flow into the cell.
- Astrocytes reuptake glutamate and pump out ions to restore ionic gradients.
- These processes require glucose and oxygen, hence the BOLD signal.

**BOLD Signal and Correlation with Neuronal Activity**

**Previous Thought:**

- BOLD signal was believed to correlate with the number of action potentials.
- Studies combined BOLD activation in monkeys with single-cell recording of action potentials.
- ![[Pasted image 20240530154038.png|300]]

**Recent Findings:**
![[Pasted image 20240530154005.png|600]]
- Logothetis et al. (2001) conducted a more extensive study using BOLD signals and electrophysiological data.
- They measured:
    - Multi-unit activity (MUA) - activity from multiple neurons.
    - Local field potentials (LFPs) - summation of postsynaptic potentials reflecting overall neuronal activity.
- BOLD signal showed the strongest correlation with LFPs, not MUA or action potential count.
- A follow-up study showed a close match between predicted BOLD signal based on LFPs and the actual BOLD response.
**Interpretation:**

- BOLD activity likely reflects synaptic input and information processing within a neural population.
- BOLD is more closely related to LFPs than action potentials or MUA.

**Limitations:**

- Correlation between BOLD and LFPs is not perfect.
- BOLD should not be considered a direct measure of LFPs.


![[Pasted image 20240530155624.png|100]]
![[Pasted image 20240530155539.png]]
**Summary:**

- BOLD signal reflects changes in blood oxygenation due to neural activity.
- LFPs provide a better representation of local neuronal activity than BOLD signal.
- BOLD signal can be used to estimate local field potentials and neuronal activity indirectly.
- fMRI utilizes 3D BOLD signal measurements to create activation maps of brain function.


**Summary of BOLD fMRI**

- Neural activation removes oxygen from blood to support local cognitive processing.
- This changes the magnetic properties of the blood.
- Influx of oxygenated blood further changes magnetic properties.
- BOLD signal reflects these magnetic property changes, which correlate with local field potentials and neuronal activity.
- By measuring BOLD signal in 3D, we can generate activation maps of brain activity.
