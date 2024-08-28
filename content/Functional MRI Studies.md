


**I. fMRI Signal and BOLD Response**
![[Pasted image 20240604162221.png]]
- **Functional Magnetic Resonance Imaging (fMRI):** Measures brain activity indirectly by detecting blood oxygen level changes.
- **Blood Oxygenation and Signal Strength:** Oxygenated blood generates a stronger MRI signal compared to deoxygenated blood.
- __T2_ Relaxation Time:_* Measures the time it takes for excited atoms to return to their resting state, sensitive to local magnetic field variations caused by blood oxygenation changes.
- __T2_ Decay and Neural Activity:_* Lower T2* values due to increased oxygenation indirectly represent neural activity.
- **Hemodynamic Response Function (HRF):** Represents the relationship between neural activity and the corresponding blood flow changes.

**II. Advantages of BOLD fMRI**

- **Non-invasive:** Safe for human participants.
- **High Spatial Resolution:** Provides detailed information about brain activity location (around 1-1.5 millimeters).
- **Good Temporal Resolution:** Captures changes in brain activity relatively quickly (greater than half a second).
- **Safety:** Exposure to the magnetic field has no known long-lasting negative effects.
- **Brain Network Analysis:** Allows investigation of both localized activity in specific brain structures and interactions between different brain regions.

**III. Designing an fMRI Experiment**
![[Pasted image 20240604163049.png]]
- **Image Matrix Size:** Determines the trade-off between spatial resolution (detail) and data acquisition time. A larger matrix captures more detail but takes longer to acquire.
- **Time Series Data:** T2* decay is measured repeatedly for each voxel (3D picture element) over time, resulting in a time series representing activation levels.

**IV. Block Design**
- **Example: Finger Tapping Experiment**
	-  **Conditions:** Rest (off) and finger tapping (on).
    - **Activation Time Series:** Shows peaks corresponding to tapping periods, indicating higher activation during tapping.
    - **Motor Cortex:** The cluster of activated voxels in the motor cortex is associated with finger tapping.
![[Pasted image 20240604163128.png|500]]
![[Pasted image 20240604163208.png|500]]
![[Pasted image 20240604163228.png|500]]
- **Simple Design:** Alternating blocks of "on" (task) and "off" (rest) conditions.
- **Robust Activation:** Well-suited for detecting sustained activation due to the accumulation of hemodynamic responses within a block.
- **HRF Insensitivity:** Less affected by variations in the shape or timing of the HRF.
- **Limitations:**
    - **Assumes Constant Activity:** Requires a constant level of activation throughout the block.
    - **Limited Event Analysis:** Cannot analyze individual events within a block, only overall block activation.
    - **HRF Variations Not Studied:** Does not account for potential variations in the HRF across the brain.
![[Pasted image 20240604171750.png]]
*Up -> block design |  bottom -> event design*

**V. Event-Related Design**
![[Pasted image 20240604170541.png]]
- **Short Stimuli:** Uses brief and separated stimulus presentations instead of continuous blocks.
- **Individual Event Responses:** Allows researchers to make inferences about the brain's response to each individual event.
- **HRF Sensitivity:** More susceptible to variations in the HRF, which can affect the analysis.
- **Advantages:**
    - **Timing of Activation:** Enables studying the timing of neural activation in response to specific events.
    - **Flexible Analysis:** Allows for flexible sorting and analysis of trials after data collection.
- **Disadvantages:**
    - **Lower Power:** Typically has lower statistical power to detect activation compared to block designs.
    - **HRF Dependence:** Results can be significantly impacted by variations in the HRF.
    - **Carry-over Effects:** Responses from one event might influence responses to subsequent events.

**VI. Cognitive Subtraction Method**
![[Pasted image 20240604170141.png]]
- **Contrasting Activation:** Compares brain activity during a task condition with a control condition to isolate the brain activity related to the cognitive process of interest.
- **Assumptions:** Relies on the assumptions that different cognitive processes are localized in distinct brain regions and that complex tasks can be understood as simpler tasks combined.
- **Control Condition Design:** Careful design of the control condition is crucial to isolate the specific cognitive process under investigation. Resting baseline is generally a poor control due to ongoing mental activity (mind-wandering). A more effective approach is to use an active control condition that resembles the task condition but lacks the process of interest.
	- ![[Pasted image 20240604170013.png]]
![[Pasted image 20240604165938.png]]
**VII. Example fMRI Experiments**

- **Visual Perception:** Investigates brain regions involved in vision by comparing brain activity during viewing a flickering checkerboard pattern to scrambled patterns.
- **Face Recognition:** Identifies the brain region responsible for face processing by contrasting brain activity during viewing faces with scrambled faces and object pictures.

**Key Takeaways:**

1. BOLD fMRI measures neural activity indirectly through blood oxygenation changes.
2. The choice of experimental design (block vs. event-related) impacts the type of brain activity that can be effectively measured.
3. Cognitive subtraction using a well-designed control condition is essential to isolate brain activity associated

>[! Additional Resources]
>https://www.youtube.com/watch?v=avsYY5dbJ7g
>https://www.youtube.com/watch?v=RQrtNVKvIIk