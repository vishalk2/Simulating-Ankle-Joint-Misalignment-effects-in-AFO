# Simulating Ankle Joint Misalignments effects in Ankle Foot Orthosis (AFO)

### Contents
- [ABOUT](#about)
- [RESEARCH PAPER](#research-paper)
- [KEYWORDS](#keywords)
- [REPO FILES](#repo-files)

<br>
<hr>

### ABOUT
This Research Work involves -
- Study of "Misalignment effects" between Lower limb structure and an Ankle Foot Orthosis (AFO).
- 2D Link-segment Mathematical model used to simulate relative motion taking place between lower limb and the AFO for a functional range of ankle motion.
- Calculations of Anterior-Posterior(A-P) & Proximal-Distal(P-D) relative motions between lower limb and the AFO for a set of 4 test cases.
- Estimation of Calf Band Travel.
- Prediction of Pressure Points on leg.

<br>
<hr>

### RESEARCH PAPER
DOI: https://link.springer.com/chapter/10.1007/978-3-031-15758-5_15

<br>
<hr>

### KEYWORDS
- orthosis
- ankle joint
- biomechanics
- exoskeleton
- pistoning
- misalignments
- gait analysis

<br>
<hr>

### REPO FILES
* AFO_Analysis.xlsx : Excel Dashboard for analysis
* MATLAB Files
    * AFO_Graphical_Input.m
        - MATLAB file for AFO analysis with Graphical Input prompts.
        - The file is directly runnable and is fully UI-based wherein you will be required to graphicall pick misalignments.
        - Feel free to experiment with the Graphical input and the AFO inputs.
    * AFO_Live_Script.mlx
        - MATLAB dynamic live script file for AFO analysis.
        - The file is directly runnable and is helpful for line-by-line retrospection of the code and the backend analysis.
    * AFO_Manual_Input.m
        - MATLAB file for AFO analysis with Manual Input (Typed) prompts.
        - The file is directly runnable and is UI-based wherein you will be required to type misalignments.
        - Feel free to experiment with the Misalignment inputs and the AFO inputs.
    * AFO_Simulation.m, Simulation.m
        - MATLAB files for simulating/calculating relative motions for all 4 misalignment cases considered.
        - Feel free to experiment with the Ankle dorsiflexion range and the AFO inputs.
    * AFO_Gait_Analysis.xlsx
        - MS Excel file for simulating Gait Analysis.
        - Provides UI-based dashboard for analysis as well as visually comprehending the misalignment effects.
        - Feel free to experiment with the dashboard.

<br>
