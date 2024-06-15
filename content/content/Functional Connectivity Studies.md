## fMRI Experiments: Functional Connectivity MRI

This note dives into functional connectivity MRI (fMRI), a technique that goes beyond just measuring brain activity in isolation. Instead, it focuses on how different brain regions interact with each other, forming functional networks.

**Understanding Functional Connectivity:**

- **Blood Flow as a Proxy:** fMRI relies on the assumption that changes in blood flow are indirectly indicative of neuronal activity. By measuring blood flow fluctuations over time within tiny 3D units called voxels, researchers can build a picture of brain activation patterns.	![[Pasted image 20240612131340.png]]

- **Correlations Reveal Connections:** Functional connectivity analysis examines the correlations between these time series obtained from various brain regions. A strong correlation between two regions suggests they are functionally connected, meaning they likely work together to perform a specific task.
- ![[Pasted image 20240612131453.png]]
- ![[Pasted image 20240612131502.png]]
- **Two Main Approaches:** There are two primary ways to analyze functional connectivity:
    - **Voxel-to-Voxel Connectivity:** This method involves a single voxel as the starting point. The time series of this voxel is compared to the time series of all other voxels in the brain to identify correlated activity patterns.
	    - ![[Pasted image 20240612131530.png]]
    - **Seed-Based Connectivity:** This approach focuses on a predefined region of interest (ROI) selected based on anatomy or task-based activation. The time series of this ROI is then correlated with the time series of other brain regions to assess their functional connectivity with the chosen ROI.
	    - ![[Pasted image 20240612131541.png]]
		  ![[Pasted image 20240612135400.png]]
		        *overlaying atlas on top of structural scan performing a segmentation over the structure  (red/ blue arrow = left and right motor cortex)* 
		  

**Independent Component Analysis (ICA) and Network Discovery:**

- **Unraveling the Network Landscape:** ICA is a powerful tool used in resting state fMRI, a type of fMRI where participants are typically asked to relax and not focus on any specific thoughts. ICA helps researchers identify independent networks of brain regions that exhibit highly synchronized activity during rest. These networks are thought to represent the brain's functional architecture.
- ![[Pasted image 20240612135420.png]]
- **Common Functional Networks:** ICA has revealed several consistently observed networks, each associated with specific cognitive functions. Some examples include:
    - Higher-order visual processing network
    - Lower-order visual processing network
    - Motor control network
    - Vigilance network involved in attention
    - Error monitoring and response inhibition network
    - Visual monitoring network

**The Default Mode Network (DMN): A Special Case**
				
- **Resting State Powerhouse:** The DMN is a particularly intriguing network identified through ICA. This network exhibits high activity when the brain is at rest but deactivates when we engage in focused tasks.
- **The Core of Self and Social Cognition:** The DMN is believed to be involved in a variety of higher-order cognitive functions, including:
    - Comprehension of information and learning
    - Memory processes
    - Self-referential processing (thinking about oneself, autobiographical memories)
    - Theory of mind (understanding the mental states of others)
    - Social cognition and emotional processing
![[Pasted image 20240612131921.png|500]]
	*Network of brain region with highly correlated activity during wakeful rest*
![[Pasted image 20240612131950.png]]
				*Great similarity between rodent and primate brain*

- Deactivation of DMN correlates with successful memory encoding 
- Deactivation of DMN correlates with task  difficulty
- Activation of DMV after learning improves retention
![[Pasted image 20240612134640.png]]

**Functional Connectivity in Action: Applications and Future Directions**

- **Clinical Applications:** By comparing functional connectivity patterns between healthy controls and patients with various disorders (e.g., Alzheimer's disease, depression), researchers can gain insights into the underlying neural mechanisms of these conditions.
- **Linking Connectivity to Behavior:** Connectivity studies can also investigate how the brain's functional networks relate to our performance on cognitive tasks and even individual differences in behavior and personality.


Example of study where they compared connectivity of superior temporal cortex with patients with patient with frontotemporal dementia (FTD) and Alzheimer's disease (AD) and healthy control subject (HC). (Hafkemeijer et al., 2015)
![[Pasted image 20240612135015.png]]
Example of DMN deactivation in association with task performance in young and older adults (Miller et al, 20207)
![[Pasted image 20240612135150.png|500]]

**Functional connectivity MRI offers a powerful window into the brain's intricate network organization. By studying how different brain regions communicate and collaborate, researchers are gaining a deeper understanding of how our brains support various cognitive functions and how these networks might be disrupted in neurological and psychiatric disorders.**
