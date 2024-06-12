---
title: "Coastal picocyanobacteria can exploit low oxygen habitats"

author:
- Sylwia Śliwińska-Wilczewska:
    institute:
    - MTA
    - UG
    email: ssliwinskawilczews@mta.ca
    ORCID: ORCID 0000-0002-3147-6605
- Mireille Savoie:
    institute: MTA
    email: msavoie@mta.ca
    ORCID: 0009-0009-9499-6657
- Naaman M. Omar:
    institute: MTA
    email: nomar@mta.ca
    ORCID: 0000-0001-9583-2886
- Douglas A. Campbell:
    institute: MTA
    email: dubhglascambeuil@gmail.com
    ORCID: 0000-0001-8996-5463
    correspondence: true
institute:
- MTA: Department of Biology, Mount Allison University, 53 York St., Sackville, NB, E4L 1C9, Canada
- UG: "Institute of Oceanography, University of Gdansk, 46 Pilsudskiego St, P81-378,
    Gdynia, Poland"
- VU: Department of Geography, University of Victoria, Victoria, BC, V8P 5C2, Canada
- IOPAN: "Institute of Oceanology, Polish Academy of Sciences, 81-712 Sopot, Poland"
output:
  bookdown::word_document2:
    reference_docx: Template.docx
    code-folding: show
    keep_md: yes
    fig.caption: yes
    toc: FALSE
    pandoc_args:
    - "--lua-filter=scholarly-metadata.lua"
    - "--lua-filter=author-info-blocks.lua"
  html_document:
    df_print: paged
  word_document:
    reference_docx: Template.docx
    code-folding: show
    keep_md: yes
    fig.caption: yes
    toc: FALSE
    pandoc_args:
    - "--lua-filter=scholarly-metadata.lua"
    - "--lua-filter=author-info-blocks.lua"
    - "--lua-filter=custom_filter.lua"
bibliography:
- PicoBaltic.bib
- packages.bib
- faultycitations.bib
csl: "botany.csl"
---
















<br>

# Abstract {.unnumbered}

xxx

<br>

# Introduction {.unnumbered}

Picocyanobacteria, the most abundant primary producers in marine ecosystems [@flombaumPresentFutureGlobal2013], exhibit remarkable adaptations to thrive in low oxygen environments, such as Oxygen Minimum Zones (OMZs), prevalent at depths in the ocean [@wongPhytoplanktonRequireOxygen2023]. These zones are characterized by exceptionally low dissolved oxygen concentrations, posing challenges for aerobic organisms. However, picocyanobacteria species have evolved diverse strategies to cope with these conditions. Picocyanobacteria, can perform photosynthesis under extremely low light and oxygen levels, utilizing specialized pigments and photosystems to capture and utilize light energy efficiently [XXX citations xxx]. Additionally, some planktonic cyanobacteria species exhibit vertical migration behaviors, moving closer to the surface during nighttime to access oxygen-rich waters and retreating to deeper layers during the day to avoid excessive light exposure [@kromkampComputerModelBuoyancy1990]. Furthermore, recent studies have highlighted the role of specific genetic adaptations in cyanobacteria populations inhabiting OMZs, enabling them to tolerate and even thrive in oxygen-depleted environments [@ulloaMicrobialOceanographyAnoxic2012]. These adaptations encompass genetic modifications related to energy metabolism, antioxidant defense mechanisms, and cellular structures optimized for oxygen scavenging and storage. Overall, the occurrence and adaptation of picocyanobacteria to low oxygen environments are critical components of marine ecosystems, shaping their productivity and biodiversity in OMZ regions.

<br>

# Materials and Methods {.unnumbered}

## Culture condition and experimental setup {.unnumbered}

Xenic PC-rich and PE-rich cultures of *Synechococcus* sp. were obtained from the Culture Collection of Baltic Algae (PC-rich CCBA_077 and PE-rich CCBA_127) https://ccba.ug.edu.pl/pages/en/home.php). *Synechococcus* sp. strains were cultured in Tissue Culture Flasks (VWR International, Cat. No. 10062-872, PA, USA) and transferred biweekly to fresh f/2 media [@guillardCulturePhytoplanktonFeeding1975] with a salinity at 8 PSU, reflective of their natural habitat. Pre-cultures were maintained in incubators set to full oxygen concentration of 250 µM, temperature of 22℃ with a light/dark cycle of 12 h and Photosynthetically Active Radiation (PAR) of 10 µmol photons m^−2^s^−1^ with illumination from Philips Cool White F14T5/841 Alto, 14 watts, fluorescent bulbs.

Controlled growth experiments were performed using MCMIX-OD PSI Multicultivators (Photon Systems Instruments, Drásov, Czech Republic). The optical density of the cultures was monitored using the Photobioreactor Control Software (Photon Systems Instruments, Drásov, Czech Republic). Each of 8 round bottom cylindrical glass tubes contained 75 mL of f/2 medium and 5 mL of growing pre-culture. These parameters allowed for exponential growth of the cultures from the beginning of the experiment, with little lag phase after inoculation. The inoculation of culture tubes took place each time in the afternoon, while the sinusoidal photoperiodic cycle commenced the following morning. This cycle ensured that the peak PAR occurred at noon each day.

Cultures grew at 22℃, with peak PAR of 180 µmol photons m^−2^s^−1^. To approximate diel cycles, the photoperiods of 12 h were applied in a sinuisoidal shape. Each tube was maintain under an individual combination of 7 spectral bandwidth (405, 450, 470, 530, 620, 660, and 730 nm) and 2 oxygen concentrations (O~2~; 250 µM and 2.5 µM). A low O~2~ concentration of ~ 2.5 µM, was achieved by sparging with a gas mixture containing 99.95% N~2~ and 0.05% CO~2~. A high O~2~ concentration of ~ 250 µM was achieved by sparging with lab air (78% N~2~, 21% O~2~, 1% Ar and 0.05% CO~2~). O~2~ concentration *in situ* was verified using oxygen optodes (PyroScience, Germany) inserted into tubes for real-time measurements. The Pyroscience software corrected O~2~ concentration based on the salinity of the media (8 PSU). Culture tubes were closed with a silicone inert silicone stopper perforated by an aeration input tube extending to the bottom of the culture tube, and a pressure outlet tube. We used aeration with a total air flow rate of around ~ 140 mL min^−1^ tube^−1^ through a 0.2µm sterile microfilter via a G400 gas mixing system (Qubit Systems Inc., Kingston, Ontario, Canada). The pH of tested cultures did not fluctuate fiercely and was about 8 during the experiment. 

<br>

## Chlorophyll-specific exponential growth rates {.unnumbered}

Picocyanobacterial growth was monitored every 5 minutes by automatically recording OD~680~, OD~720~, and ΔOD (ΔOD = OD~680~ – OD~720~) for at least 7 days, independently for each culture tube. The chlorophyll-specific exponential growth rates (µ) were determined by fitting logistic growth curves using a modified Levenberg-Marquardt fitting algorithm [@elzhovMinpackLmInterface2023] to plots of the chlorophyll *a* proxy of ΔOD vs. elapsed time (d) for each combination of strain, spectral bandwidth, and O~2~ concentration. Growth curves, tracked as OD~680~, OD~720~, ΔOD and logistic fits of ΔOD vs. elapsed time were shown in Fig. S1 in Supplementary materials.

<br>

## Whole-cell absorbance spectra, pigment content, and PUR/PAR ratio {.unnumbered}

Whole-cell absorbance spectra of picocyanobacteria cells were collected using an integrating cavity upgrade spectrophotometer (CLARiTY 17 UV/Vis/NIR, On-Line Instrument Systems, Inc., Bogart, GA, USA) according to the method proposed by @blakeSituSpectroscopyIntact2012. Each sample and reference observation cavity of the spectrophotometer was filled with 8 mL of f/2 medium. After establishing a baseline absorbance ranging from 375 to 710 nm (f/2 media of salinity 8 PSU), 4 mL of PC-rich_077 or PE-rich_127 culture cell suspension was introduced into the sample cavity, replacing an equal volume of culture medium. Pathlength corrected absorbance per cm was calculated using Jávorfi coefficients [@javorfiQuantitativeSpectrophotometryUsing2006].

Using an integrating cavity upgrade CLARiTY 17 UV/Vis/NIR spectrophotometer, we conducted estimations of pigment content (µg mL^-1^) including Chlorophyll *a* (Chl *a*), Carotenoids (Car), Phycoerythrin (PE), Phycocyanin (PC), and Allophycocyanin (APC) in PC-rich_077 and PE-rich_127 *Synechococcus* sp. cultures. These estimations were based on established linear correlations between pigment content, determined through extraction methods [@stricklandPracticalHandBook1972; @bennettComplementaryChromaticAdaptation1973], and absorbance values of individual pigment peaks (Car; 480 nm, PE; 565 nm, PC; 620 nm, APC; 650 nm, and Chl *a*; 665 nm) obtained from whole-cell absorbance spectra (Table S1). We also summed PE, PC, and APC protein to receive Phycobilins (Phyco) content. Additionally, we calculated the Car to Chl *a* ratio and the ratio of the sum of Phyco to Chl *a* (µg:µg) for each strain.

Chl *a* (µg mL^−1^) was also measured using Trilogy Laboratory Fluorometer (Turner Designs, Inc., CA, USA) equipped with Chlorophyll In-Vivo Module. Quantitative analysis of Chl *a* was obtained after adding 50 µL of picocyanobacteria culture and 2 mL of a 90% acetone:DMSO solution in a 3:2 ratio.

We also estimated the Photosynthetically Usable Radiation (PUR)/Photosynthetically Active Radiation (PAR) ratio which is the fraction of PAR that can be captured by the absorbance of the cells. First, we obtained an emission profile from 370 nm to 750 nm of each coloured LED light of the MCMIX-OD Multicultivator (spectral bandwidth of 405, 450, 470, 530, 620, 660, and 730 nm) using a Jaz spectrometer (Ocean Optics, Inc.,Dunedin, FL, USA) equipped with a fiber optic cable, HH2 FiberOpticJmp (Part number A901073, Malvern Panalytical Ltd, Malvern, UK). Next, each LED spectrum (Em) was normalized to its emission peak maximum (393, 441, 469, 521, 612, 647, and 722 nm). We also normalized the obtained whole-cell absorbance spectra of *Synechococcus* sp. cultures from 375 nm to 710 nm to a reference wavelength of Chl *a* maximum peak wavelength (440 nm). PUR (µE = µmol photons m^−2^s^−1^) was estimated from the formula Eq. (1) according to method proposed by @morelAvailableUsableStored1978. 

$$\begin{equation}
  PUR~(µE)=\frac{∑(NormA_440~×~NormEm)}{∑(NormEm)}~×~PAR~(µE)
  \qquad(1)
\end{equation}$$

where NormA~440~ is the Absorbance Normalized to 440 nm, NormEm is the Emission spectra Normalized to maximum peak of each colur light, and PAR in this case is 180 µmol photons m^−2^s^−1^.

<br>

## Picocyanobacteria cell counts {.unnumbered}

Picocyanobacterial cells (cell mL^−1^) were counted using an ImageXpress Pico Digital microscope equipped with CMOS camera and LED+ image autofocus (ImageXpress Pico Automated Cell Imaging System, Molecular Devices, LLC., CA, USA). Culture samples were preserved with 4% glutaraldehyde and kept at -80°C until the measurements. Samples (V = 10 µL) were transferred to Tissue Culture (TC)-treated surface, flat bottom black 96-well plates (Corning® Falcon® Microplate, MilliporeSigma, Merck, Darmstadt, Germany) containing 200 µL of f/2 media and centrifuged using a Beckman J-20 centrifuge with a swing bucket JS-4.3 rotor at 4500 rpm (Beckman Coulter, Brea, California, United States). Cells were imaged with the Cy5 channels (Excitation: 630/40 nm; Emission: 695/45 nm; Dichroic: 655 nm) using selectable confocal geometries, which allowed us to distinguish cyanobacterial cells from any co-occurring heterotrophic bacteria, and counted using a 63x objective in fluorescence imaging modes. Quantitative analysis on images acquired from automated microscopy obtained from 96-well microplates was performed using CellReporterXpress Image Acquisition and Analysis Software. The actual cell number was calculated based on the dilution factor and selected area count in each well [@wlodkowicRecentProgressCytometric2022].

<br>

## PSII effective absorption cross section of PSII and electron flux {.unnumbered}

We harvested 4 mL of picocyanobacteria cultures for photophysiological characterizations repeatedly across the growth trajectories. It is worth emphasizing here that we We used Fast Repetition Rate fluorometry (FRRf) even in conditions when there was no recorded growth rate of tested strains.

We used FRRf [@kolberMeasurementsVariableChlorophyll1998] (Solisense, USA), with a lab built temperature control jacket (22℃), to apply series of flashlets to drive saturation induction/relaxation trajectories, fit using the onboard Solisense LIFT software [@falkowskiEstimationPhytoplanktonPhotosynthesis1993; @kolberMeasurementsVariableChlorophyll1998]. From the model fits we took the initial fluorescence before induction (*F*~O~, *F*~O~′, or *F*~S~, depending upon the level of actinic light and step in the light response curve); the maximum fluorescence (*F*~M~ or *F*~M~′) once Photosystem II (PSII) was driven to closure; and the effective absorption cross section for PSII photochemistry (σ~PSII~ or σ~PSII~′; nm^2^ quanta^−1^) [@tortellUserGuideApplication2021]. 

We used a double tap protocol [@xuConnectivityPhotosystemII2017], where FRRf induction/relaxation trajectories were collected during a rapid light curve sequence increasing in steps of 10 s at 0, 20, 40, 80, 160, and 320 µmol photons m^−2^s^−1^ PAR, delivered from LED emitters centred at 445, preferentially exciting chlorophyll, 530, preferentially exciting phycoerythrin, or 590 nm, preferentially exciting phycocyanin. 

Flash Power for 445 excitation was 60000 µmol photons m^−2^s^−1^ PAR, for 530 nm excitation power was 25000 µmol photons m^−2^s^−1^ PAR, while for 590 nm excitation power was 14000 µmol photons m^−2^s^−1^, calibrated using a quantum sensor (LI-250, LI-COR, Inc.). We applied 1 s darkness between sequential light steps, to allow re-opening of PSII. FRRf excitation flashlets were applied at the same wavebands, 445, 530, or 590 nm, as the actinic light steps.

We calculated (Eq. (2)) an uncalibrated fluorescence based estimator for volumetric electron transport, *JV*~PSII~, (k × e^−^ L^−1^ s^−1^) under 445 nm (blue), 530 nm (green), and 590 nm (orange) excitation bands [@oxboroughDirectEstimationFunctional2012; @boatmanImprovingAccuracySingle2019; @tortellUserGuideApplication2021].


$$\begin{equation}
  {JV_{PSII}} = \frac{σ_{PSII}′ × qP × I × F_O}{σ_{PSII} }
  \qquad(2)
\end{equation}$$


where σ~PSII~′ is effective absorption cross section for PSII photochemistry under the relevant actinic PAR step (nm^2^ quanta^−1^); qP is an estimate of the fraction of PSII open for photochemistry estimated according to @oxboroughResolvingChlorophyllFluorescence1997; I is the applied PAR (µmol photons m^−2^s^−1^); *F*~O~ is the minimum fluorescence from a given sample and excitation bandwidth (relative fluorescence) and σ~PSII~ is the maximum effective absorption cross section for PSII photochemistry from a given sample and excitation bandwidth (nm^2^ quanta^−1^). 

We calibrated the *JV*~PSII~ estimator to absolute rates of electron transport (Eq. (3)) using parallel measures of oxygen evolution (µmol O~2~ L^−1^ s^−1^), captured simultaneously with the FRRf measures, below light saturation of electron transport, using a FireSting robust oxygen probe (PyroScience, Germany) inserted in the cuvette for select Rapid Light Curve (RLC) runs. For the blue LED (Ex~445nm~) excitation we used a calibration slope of 108832, for the green LED (Ex~530nm~) excitation we used a calibration slope of 110082, while for orange LED (Ex~590nm~) excitation we used a calibration slope of 254327 (Tab. S2).

$$\begin{equation}
  {JV_{PSII}(e^{−}~L^{−1}~s^{−1})} = \frac{Uncalibrated~JV_{PSII}(e^{−}~L^{−1}~s^{−1})}{Calibration~slope}
  \qquad(3)
\end{equation}$$

At the same time as the FRRf measurements were performed, Chl *a* (µg mL^−1^) and cell count (N mL^−1^) measurements were also investigated.

<br>

## Statistical analysis {.unnumbered}

We used R version 4.3.0 [@rcore] running under RStudio [@posit]. We performed three-way factorial ANOVA (*aov()* function; R Base package) to determine whether strain, spectral bandwidth, oxygen concentration, and their interactions, significantly influence the chlorophyll-specific exponential growth rate (µ; d^−1^; Tab. S3). 

Furthermore, to examine statistical differences between fits plotted for chlorophyll-specific exponential growth rate (Tab. S4), pigments content (Tab. S5), pigment ratio (Tab. S6), σ~PSII~′ (Tab. S7), and *JV*~PSII~ (Tab. S8) measured under different oxygen concentrations for each strain, we performed one-way ANOVA (*aov()* function; R Base package). Statistical differences for all analyses were determined at significance level of α = 0.05. 

The manuscript was prepared as a Rmarkdown document [@handelAndreasHandelCustom2020] with figures plotted using ggplot2 [@wickhamDataAnalysis2016] and patchwork [@pedersenPatchworkComposerPlots2024] packages. All metadata, data, and code is available on GitHub (https://github.com/FundyPhytoPhys/BalticO2).

<br>

# Results {.unnumbered}

## Chlorophyll-specific exponential growth rate {.unnumbered}

We used logistic curve fits (Fig. S1) to determine chlorophyll-specific exponential growth rates (μ; d^−1^), for PC-rich and PE-rich cultures of *Synechococcus* sp. grown at spectral bandwidth of 405, 450, 470, 530, 620, 660, and 730 nm and O~2~ concentration of 250 µM and 2.5 µM (Fig. <a href="#fig:GrowthRate">1</a>. 

Three-way factorial ANOVA showed that peak PAR, photoperiod, strain, and their interactions, significantly affected μ (ANOVA, *p* < 0.05 for all; Table S3). Significant differences between model fits of chlorophyll-specific exponential growth rates (d^−1^) vs. growth wavelength (nm) estimated for 250 µM and 2.5 µM O~2~ concentration for each *Synechococcus* sp. cultures was also recorded (ANOVA, *p* < 0.05; Table S2). 

In general, PC-rich strains achieved faster growth rates under O~2~ concentration of 250 µM than 2.5 µM whereas, PE-rich strain showed similar growth rates under 250 µM and 2.5 µM of O~2~ concentration across tested spectral bandwidth (nm). In the presence of high O~2~ concentrations (250 µM), PC-rich strain did not show growth at 405 nm and PE-rich strain did not growth at 405, 450, and 730 nm. On the other hand, in low O~2~ concentrations (2.5 µM), both PC-rich and PE-rich strain showed growth rates over the entire range of tested growth wavelength (405 – 730 nm). 

PC-rich *Synechococcus* sp. showed distinct growth peak at red light (μ = 1.17 ± 0.013 d^−1^ at 620 nm and μ = 0.95 ± 0.009 d^−1^ at 660 nm) under O~2~ concentration of 250 µM. PE-rich strain showed the highest growth rate under green light at 530 nm under 2.5 µM of O~2~ (μ = 0.80 ± 0.003 d^−1^) however, high growth rates were also recorded for 620 nm (μ = 0.71 ± 0.002 d^−1^) and 660 nm (μ = 0.73 ± 0.002 d^−1^).

<br>

![<span id="fig:GrowthRate"></span>**Fig. **1: Chlorophyll-specific exponential growth rates (d^−1^) vs. growth wavelength (nm). Growth rates (± SE falling within symbols) were estimated from logistic fits of chlorophyll proxy OD~680~ – OD~720~ (ΔOD) vs. elapsed time, for PC-rich (green circle) and PE-rich (red circle) cultures of *Synechococcus* sp. grown at spectral bandwidth of 405, 450, 470, 530, 620, 660, and 730 nm and O~2~ concentration of 250 µM (open symbols and dashed line) and 2.5 µM (closed symbols and solid line).](../Output/Figures/Fig_GrowthRate.png)

<br>

## Whole-cell absorbance spectra, pigment content, and PUR/PAR ratio {.unnumbered}

Whole-cell absorbance spectra of PC-rich and PE-rich *Synechococcus* sp. cultures showed that XXX (Fig. <a href="#fig:PURPAR">2</a>*a*), 


![<span id="fig:PURPAR"></span>**Fig. **2: Whole-cell absorbance spectra vs. wavelength (nm) and PUR/PAR ratio vs. growth wavelength (nm). (*a*) Representative absorbance spectra, normalized to 440 nm (NormA~440~), were measured together with emission spectra of the colour LED lamp used for PAR, normalized to their emission peak. Estimated Photosynthetically Usable Radiation (PUR) is shown as a green area for the PC-rich strain and a red area for the PE-rich strain grown at spectral bandwidth of 405, 450, 470, 530, 620, 660, and 730 nm and O~2~ concentration of 250 µM (dashed line) and 2.5 µM (solid line). (*b*) PUR/PAR ratio was estimated for PC-rich (green circle) and PE-rich (red circle) cultures of *Synechococcus* sp. grown at spectral bandwidth of 405, 450, 470, 530, 620, 660, and 730 nm and O~2~ concentration of 250 µM (open symbols and dashed line) and 2.5 µM (closed symbols and solid line).](../Output/Figures/Fig_PURPARRatioSpectra.png)


<br>

![<span id="fig:Pigment"></span>**Fig. **3: Pigment content (pg cell ^−1^) (*a*) and pigment ratio (µg:µg) (*b*) vs. growth wavelength (nm) for PC-rich (green circle) and PE-rich (red circle) cultures of *Synechococcus* sp. grown at spectral bandwidth of 405, 450, 470, 530, 620, 660, and 730 nm and O~2~ concentration of 250 µM (open symbols and dashed line) and 2.5 µM (closed symbols and solid line).](../Output/Figures/Fig_Pigment.png)

<br>

## Effective absorption cross section of PSII {.unnumbered}

![<span id="fig:SigLRC"></span>**Fig. **4: Effective absorption cross section of PSII (σ~PSII~ʹ; nm^2^ quanta^−1^) measured under diel peak PAR growth light vs. Actinic PAR (µmol photons m^−2^s^−1^). σ~PSII~ʹ was estimated using FRRf induction curves with excitations (Ex~445nm~; blue, and Ex~590nm~; orange), for PC-rich (green circle) and PE-rich (red circle) cultures of *Synechococcus* sp. grown at spectral bandwidth of 450 and 620 nm and O~2~ concentration of 250 µM (open symbols and dashed line) and 2.5 µM (closed symbols and solid line).](../Output/Figures/Fig_SigLRC.png)

<br>

![<span id="fig:SigWL"></span>**Fig. **5: Effective absorption cross section of PSII (σ~PSII~ʹ; nm^2^ quanta^−1^) measured under diel peak PAR growth light vs. wavelength (nm). σ~PSII~ʹ was estimated using FRRf induction curves with excitations (Ex~445nm~; blue and Ex~590nm~; orange), for PC-rich (green circle) and PE-rich (red circle) cultures of *Synechococcus* sp. grown at spectral bandwidth of 450 and 620 nm and O~2~ concentration of 250 µM (open symbols and dashed line) and 2.5 µM (closed symbols and solid line).](../Output/Figures/Fig_SigWL_2.png)

<br>

![<span id="fig:SigPig"></span>**Fig. **6: Effective absorption cross section of PSII (σ~PSII~ʹ; nm^2^ quanta^−1^) measured under diel peak PAR growth light vs. the ratio of sum of µg Phycobiliprotein to µg Chl *a*. σ~PSII~ʹ was estimated using FRRf induction curves with excitations (Ex~445nm~; blue and Ex~590nm~; orange), for PC-rich (green circle) and PE-rich (red circle) cultures of *Synechococcus* sp. grown at spectral bandwidth of 450 and 620 nm and O~2~ concentration of 250 µM (open symbols and dashed line) and 2.5 µM (closed symbols and solid line).](../Output/Figures/Fig_SigPig.png)

## Growth rates vs. cumulative diel PSII electron flux {.unnumbered}

<br>

![<span id="fig:GrowthRateJVPSII"></span>**Fig. **7: Chlorophyll-specific exponential growth rates (d^−1^) vs. PSII electron flux (*JV*~PSII~; µmol e^−^ µmol Chl *a*^−1^ d^−1^) measured under diel peak PAR growth light. Growth rates (± SE falling within symbols) were estimated from logistic fits of chlorophyll proxy OD~680~ - OD~720~ (ΔOD) vs. elapsed time. *JV*~PSII~ was estimated using FRRf induction curves with excitations (Ex~445nm~; blue and Ex~590nm~; orange), for PC-rich (green circle) and PE-rich (red circle) cultures of *Synechococcus* sp. grown at spectral bandwidth of 450 and 620 nm and O~2~ concentration of 250 µM (open symbols and dashed line) and 2.5 µM (closed symbols and solid line).](../Output/Figures/Fig_GrowthRate_JVPSII_Chla.png)

<br>

# Discussion {.unnumbered}

<br>

# Conclusions {.unnumbered}

<br>

**Additional Supporting Information may be found in the online version of this article.**

<br>

**Authors Contribution Statement:** S.S-W. designed the study with input from D.A.C. M.S. ensured the proper operation of the photobioreactors. N.M.O. solved technical problems related to computer operation and software. S.S-W., M.S., N.M.O., D.A.C. contributed to R coding and data analysis. S.S-W. conducted the experiments, created plots and wrote the manuscript, with support from D.A.C. All authors contributed to the discussion of the results, supported manuscript preparation, and approved the final submitted manuscript.

<br>

# Data availability statement {.unnumbered}

Data supporting this study is available on:
https://github.com/FundyPhytoPhys/BalticO2 (public GitHub Repository) and
https://docs.google.com/spreadsheets/d/1ZXpwR7Gfto-uRzVdXzMpQF4frbrvMLH_IyLqonFZRSw/edit#gid=0 (URL for MetaDataCatalog).

Code to perform data processing and analyses is available at https://github.com/FundyPhytoPhys/BalticO2.

<br>

## Acknowledgements {.unnumbered}

We thank Miranda Corkum who maintained cultures and trained personnel in culture handling; Laurel Genge, and Carlie Barnhill (Mount Allison students) who assisted with R code. This work was supported by Canada Research Chair in Phytoplankton Ecophysiology (D.A.C) and Latitude & Light; NSERC of Canada Discovery Grant (D.A.C).

<br>

## Conflict of Interest {.unnumbered}

None declared.

<br>

# References {.unnumbered}
