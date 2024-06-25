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
- Douglas A. Campbell:
    institute: MTA
    email: dubhglascambeuil@gmail.com
    ORCID: 0000-0001-8996-5463
    correspondence: true
institute:
- MTA: Department of Biology, Mount Allison University, 53 York St., Sackville, NB, E4L 1C9, Canada
- UG: "Institute of Oceanography, University of Gdansk, 46 Pilsudskiego St, P81-378,
    Gdynia, Poland"
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
- BalticO2.bib
- packages.bib
- faultycitations.bib
csl: "botany.csl"
---
















<br>

# Abstract {.unnumbered}

xxx

<br>

# Introduction {.unnumbered}


Oxygen
@wongPhytoplanktonRequireOxygen2023
@breitburgDecliningOxygenGlobal2018
@ulloaMicrobialOceanographyAnoxic2012


Oxygen is essential for the survival of organisms and regulates the global cycling of nutrients and carbon. Oxygen levels in the open ocean and coastal waters have declined over the past half-century due to human activities that increase global temperatures and nutrient release. These factors accelerated microbial respiration, reduced the solubility of oxygen in water, and reduced the rate of oxygen re-supply from the atmosphere to the ocean, resulting in significant biological and ecological consequences. Since the mid-20th century, ocean deoxygenation has become a critical change in marine ecosystems, affecting productivity, biodiversity and biogeochemical cycles. This ocean deoxygenation ranks among the most important changes occurring in marine ecosystems [xxxx]. Historical data link major extinction events to warm climates and oxygen-deficient oceans, suggesting that current anthropogenic activities could lead to widespread oxygen deficiency in the oceans within a thousand years. Over the past 50 years, the open ocean has lost about 2% of oxygen, and models predict a further decline of several percent by the end of the century, which could cause significant biogeochemical and ecological impacts. Oxygen minimum zones (OMZs) in the open ocean have expanded to an area equivalent to the European Union, and the volume of oxygen-free water has quadrupled. But the paradox is that these areas, sometimes called dead zones, are far from dead [@breitburgDecliningOxygenGlobal2018]. 

Picocyanobacteria, the most abundant primary producers in marine ecosystems [@flombaumPresentFutureGlobal2013], exhibit remarkable adaptations to thrive in low oxygen environments, such as Oxygen Minimum Zones (OMZs), prevalent at depths in the ocean [@wongPhytoplanktonRequireOxygen2023]. These zones are characterized by exceptionally low dissolved oxygen concentrations, posing challenges for aerobic organisms. However, picocyanobacteria species have evolved diverse strategies to cope with these conditions. Picocyanobacteria, can perform photosynthesis under extremely low light and oxygen levels, utilizing specialized pigments and photosystems to capture and utilize light energy efficiently [XXX citations xxx]. Furthermore, recent studies have highlighted the role of specific genetic adaptations in cyanobacteria populations inhabiting OMZs, enabling them to tolerate and even thrive in oxygen-depleted environments [@ulloaMicrobialOceanographyAnoxic2012]. These adaptations encompass genetic modifications related to energy metabolism, antioxidant defense mechanisms, and cellular structures optimized for oxygen scavenging and storage. Overall, the occurrence and adaptation of picocyanobacteria to low oxygen environments are critical components of marine ecosystems, shaping their productivity and biodiversity in OMZ regions.

Colour
XXX



The aim of this work was to demonstrate the ecophysiological response of PC-rich and PE-rich *Synechococcus* sp. to different oxygen concentrations and colors of light.

<br>

# Materials and Methods {.unnumbered}

## Culture condition and experimental setup {.unnumbered}

Xenic cultures of  PC-rich (CCBA_077) and PE-rich (CCBA_127) *Synechococcus* sp. were obtained from the Culture Collection of Baltic Algae (https://ccba.ug.edu.pl/pages/en/home.php) [@latalaCultureCollectionBaltic2006]. *Synechococcus* sp. strains were cultured in Tissue Culture Flasks (VWR International, Cat. No. 10062-872, PA, USA) and transferred biweekly to fresh f/2 media [@guillardCulturePhytoplanktonFeeding1975] prepared at a salinity of 8 PSU, reflective of their natural brackish habitat. Pre-cultures were maintained in incubators with full air saturated dissolved oxygen concentration [O~2~] of 250 µM, 22℃, with a light/dark cycle of 12 h and Photosynthetically Active Radiation (PAR) of 10 µmol photons m^−2^s^−1^ from Philips Cool White F14T5/841 Alto, 14 watts, fluorescent bulbs.

Controlled growth experiments were performed using MCMIX-OD PSI Multicultivators (Photon Systems Instruments, Drásov, Czech Republic) set to 22℃. Each of 8 round bottom cylindrical glass tubes contained 75 mL of f/2 medium and 5 mL of growing pre-culture. These parameters allowed for exponential growth of the cultures from the beginning of the experiment, with little lag phase. Inoculation of culture tubes took place in the afternoon, with a period of low light and then 12 h darkness before a sinusoidal 12 h photoperiod cycle commenced at 07:00 the following morning, with peak PAR of 180 µmol photons m^−2^s^−1^ reached at 13:00 each day.

Each tube was maintained under an individual combination of one of 7 spectral wavebands (centred at 405, 450, 470, 530, 620, 660, or 730 nm); at 250 µM or 2.5 µM [O~2~]. Culture tubes were closed with a silicone inert silicone stopper perforated by an aeration input tube extending to the bottom of the culture tube, and a pressure outlet tube. We used aeration with a total gas flow rate of around ~ 140 mL min^−1^ tube^−1^ through a 0.2µm sterile microfilter provided via a G400 gas mixing system (Qubit Systems Inc., Kingston, Ontario, Canada). ~ 250 µM [O~2~] was achieved by sparging with lab air (78% N~2~, 21% O~2~, 1% Ar and 0.05% CO~2~). ~ 2.5 µM [O~2~] was achieved by sparging with a gas mixture containing 99.95% N~2~ and 0.05% CO~2~. [O~2~] *in situ* was verified using oxygen optodes (PyroScience, Germany) inserted into tubes for real-time measurements (data not presented), with software correction to account for the salinity of the media (8 PSU). The pH of tested cultures remained about 8, with limited fluctuation during the growth experiment (data not presented). 

<br>

## Chlorophyll-specific growth rates {.unnumbered}

Picocyanobacterial growth was monitored every 5 minutes by automatically recording OD~680~, OD~720~, and ΔOD (ΔOD = OD~680~ – OD~720~) for at least 5 days, independently for each culture tube. The chlorophyll-specific growth rates (µ) were determined by fitting logistic growth curves using a modified Levenberg-Marquardt fitting algorithm [@elzhovMinpackLmInterface2023] to plots of the chlorophyll *a* proxy of ΔOD vs. elapsed time (d) for each combination of strain, spectral waveband, and [O~2~]. Growth curves, tracked as OD~680~, OD~720~, ΔOD and logistic fits of ΔOD vs. elapsed time are shown in Fig. S1 in Supplementary materials. Cell-specific growth rates (µ) were also determined using OD~720~ (Fig. S2). 

<br>

## Picocyanobacteria cell counts {.unnumbered}

Picocyanobacterial cells mL^−1^ were estimated using linear regression models of OD at 680 nm or 720 nm vs. calibration counts of cell suspension densities (cell mL^−1^) (Table S1). The OD of cultures was measured using MCMIX-OD PSI Multicultivators (Photon Systems Instruments, Drásov, Czech Republic) and cell suspension density measures were conducted using an ImageXpress Pico Digital microscope equipped with CMOS camera and LED+ image autofocus (ImageXpress Pico Automated Cell Imaging System, Molecular Devices, LLC., CA, USA). Culture samples were preserved with 4% glutaraldehyde and kept at -80°C until the microscopy measures. Fixed samples of culture  (V = 10 µL) were transferred to Tissue Culture (TC)-treated surface, flat bottom black 96-well plates (Corning® Falcon® Microplate, MilliporeSigma, Merck, Darmstadt, Germany) containing 200 µL of f/2 media and centrifuged using a Beckman J-20 centrifuge with a swinging bucket JS-4.3 rotor at 4500 rpm (Beckman Coulter, Brea, California, United States). Cells were imaged with the Cy5 channels (Excitation: 630/40 nm; Emission: 695/45 nm; Dichroic: 655 nm) using selectable confocal geometries, which allowed us to distinguish cyanobacterial cells from co-occurring heterotrophic bacteria, and counted using a 63x objective in fluorescence imaging modes. Quantitative analysis on images acquired from automated microscopy obtained from 96-well microplates was performed using CellReporterXpress Image Acquisition and Analysis Software. The actual cell number mL^−1^ was calculated based on the dilution factor and selected count area from each well [@wlodkowicRecentProgressCytometric2022].

<br>

## Pigment content and pigment ratio {.unnumbered}

Whole-cell absorbance spectra of picocyanobacteria cells were collected using an integrating cavity spectrophotometer (CLARiTY 17 UV/Vis/NIR, On-Line Instrument Systems, Inc., Bogart, GA, USA) according to the method proposed by @blakeSituSpectroscopyIntact2012. The sample and reference observation cavities of the spectrophotometer were filled with 8 mL of f/2 medium at salinity 8 PSU. After establishing a baseline absorbance spectra from 375 to 710 nm, 4 mL culture medium was replaced with 4 mL of culture in the sample cavity. Pathlength corrected absorbance per cm was calculated using Jávorfi coefficients [@javorfiQuantitativeSpectrophotometryUsing2006]. We then conducted estimations of pigment content (µg mL^−1^) including Chlorophyll *a* (Chl *a*), Carotenoids (Car), Phycoerythrin (PE), Phycocyanin (PC), and Allophycocyanin (APC) from the PC-rich and PE-rich *Synechococcus* sp. cultures. These estimations were based on established linear correlations between pigment content, determined through extraction methods [@stricklandPracticalHandBook1972; @bennettComplementaryChromaticAdaptation1973], and absorbance values of individual pigment peaks (Car; 480 nm, PE; 565 nm, PC; 620 nm, APC; 650 nm, and Chl *a*; 665 nm) obtained from whole-cell absorbance spectra (Table S2). We also summed PE, PC, and APC protein to total Phycobiliproteins content. We then calculated the Car to Chl *a* ratio, and the ratio of the sum of Phycobiliproteins to Chl *a* (µg:µg) for each strain (Fig. S3).

<br>

## PSII effective absorption cross section of PSII, turnover time of PSII photochemistry, and photochemical quenching coefficient {.unnumbered}

We harvested 4 mL of picocyanobacteria cultures repeatedly across the growth trajectories for photophysiological characterizations. For the low oxygen cultures, to ensure photophysiological measurements were taken at low O~2~ of ~ 2.5 µM, we bubbled gently with N~2~ from a gas cylinder during measurements. [O~2~] was verified in culture samples for photophysiological measurements using oxygen optodes (PyroScience, Germany) inserted (data not presented). 

We used Fast Repetition & Relaxation chlorophyll fluorescence (FRRf) [@kolberMeasurementsVariableChlorophyll1998] (Solisense, USA), with a lab built temperature control jacket (22℃), to apply a series of XXX excitation flashlets of 1.2 µs to drive saturation of PSII variable fluorescence, followed immediately by logarithmically spaced flashlets to track relaxation of variable fluorescence. Induction/relaxation trajectories were fit using the onboard Solisense LIFT software [@falkowskiEstimationPhytoplanktonPhotosynthesis1993; @kolberMeasurementsVariableChlorophyll1998].

We used a double tap protocol [@xuConnectivityPhotosystemII2017], where FRRf induction/relaxation trajectories were collected during a rapid actinic light curve sequence increasing in steps of 10 s at 0, 20, 40, 80, 160, and 320 µmol photons m^−2^s^−1^ PAR. We applied 1 s darkness between the sequential 10 s steps of the light response curves, to allow re-opening of PSII immediately after application of the sequential increasing light steps. Flashlets and actinic light were delivered from LED emitters centred at Ex~445nm~,  preferentially exciting chlorophyll; Ex~470nm~,, preferentially exciting phycourobilin (PUB); Ex~535nm~, preferentially exciting phycoerythrin (PE); or Ex~590nm~, preferentially exciting phycocyanin (PC). Excitation flashlets and actinic light wavebands were matched for each run. These actinic and excitation wavebands in turn approximated 4 of our 7 growth light wavebands (450, 470, 530 & 620 nm), allowing us to evaluate *in situ* photosynthetic performance for those culture conditions.

Flashlet power delivered to the samples during the 1.2 µs flashlet duration was adjusted to achieve saturation of variable fluorescence; Ex~445nm~ at 60000 µmol photons m^−2^s^−1^ PAR; Ex~470nm~ and Ex~535nm~ at 25000 µmol photons m^−2^s^−1^ PAR; while for Ex~590nm~ excitation power at 14000 µmol photons m^−2^s^−1^, calibrated using a quantum sensor (LI-250, LI-COR, Inc.) in the temperature controlled cuvette. 

We estimated effective absorption cross section of PSII (σ~PSII~; nm^2^ quanta^−1^); turnover time of PSII photochemistry (τ~PSII~; µs); and the photochemical quenching coefficient (q~P~) using the FRRf induction curves, following [@xuConnectivityPhotosystemII2017].

<br>

## PSII electron flux {.unnumbered}

We calculated (Eq. (1)) an uncalibrated fluorescence based estimator for volumetric electron transport, *JV*~PSII~, (k × e^−^ L^−1^ s^−1^) under Ex~445nm~, blue; Ex~470nm~, blue-green; Ex~535nm~, green; or Ex~590nm~, red-orange excitation bands [@oxboroughDirectEstimationFunctional2012; @boatmanImprovingAccuracySingle2019; @tortellUserGuideApplication2021].


$$\begin{equation}
  {JV_{PSII}} = \frac{σ_{PSII}′ × qP × I × F_O}{σ_{PSII} }
  \qquad(1)
\end{equation}$$


where σ~PSII~′ is effective absorption cross section for PSII photochemistry under the relevant actinic PAR step (nm^2^ quanta^−1^); qP is an estimate of the fraction of PSII open for photochemistry estimated according to @oxboroughResolvingChlorophyllFluorescence1997; I is the applied PAR (µmol photons m^−2^s^−1^); *F*~O~ is the minimum fluorescence from a given sample and excitation waveband (relative fluorescence) and σ~PSII~ is the maximum effective absorption cross section for PSII photochemistry from a given sample and excitation waveband (nm^2^ quanta^−1^). 

We calibrated the *JV*~PSII~ estimator to absolute rates of electron transport (Eq. (2)) using parallel measures of oxygen evolution (µmol O~2~ L^−1^ s^−1^), captured simultaneously with the FRRf measures, taken below light saturation of electron transport to limit distortion from electron fluxes back to oxygen under super-saturating light [@hughesRoadmapsDetoursActive2018], using a FireSting robust oxygen probe (PyroScience, Germany) inserted in the cuvette for select Rapid Light Curve (RLC) runs (Table S3). 

$$\begin{equation}
  {JV_{PSII}(e^{−}~L^{−1}~s^{−1})} = \frac{Uncalibrated~JV_{PSII}(e^{−}~L^{−1}~s^{−1})}{Calibration~slope}
  \qquad(2)
\end{equation}$$

For the samples for FRRf measurements, Chl *a* (µg mL^−1^) was also measured using Trilogy Laboratory Fluorometer (Turner Designs, Inc., CA, USA) equipped with Chlorophyll In-Vivo Module. Quantitative analysis of Chl *a* was obtained after adding 50 µL of picocyanobacteria culture and 2 mL of a 90% acetone:DMSO solution in a 3:2 ratio.

<br>

## Statistical analysis {.unnumbered}

We used R version 4.3.0 [@rcore] running under RStudio [@posit]. We performed three-way factorial ANOVA (*aov()* function; R Base package) to determine whether strain, growth waveband, and [O~2~] significantly influence the chlorophyll-specific growth rate (µ; d^−1^; Tab. S4) vs. pigment content (Tab. S5). We also performed three-way factorial ANOVA (*aov()* function) to determine whether strain, Actinic PAR, and [O~2~] significantly influence the responses of σ~PSII~ (Tab. S6); τ~PSII~ (Tab. S7); or q~P~ to increasing light (Tab. S8).

We used *t*-tests of linear regressions to compare data across different strains and [O~2~] for a given growth waveband, for chlorophyll-specific growth rate vs. Phycobiliproteins to Chl *a* ratio (Tab. S9). We also performed *t*-tests of linear fits to compare data across different strains and [O~2~] in situations in which cultures were excited by, and growing in, corresponding growth wavebands of 450, 470, 530, or 620 nm, for chlorophyll-specific growth rate vs. *JV*~PSII~ (Tab. S10). Statistical differences for all analyses were determined at significance level α = 0.05. 

The manuscript was prepared as a Rmarkdown document [@handelAndreasHandelCustom2020] with figures plotted using ggplot2 [@wickhamDataAnalysis2016] and patchwork [@pedersenPatchworkComposerPlots2024] packages. All metadata, data, and code is available on GitHub (https://github.com/FundyPhytoPhys/BalticO2).

<br>

# Results & Discussion {.unnumbered}

## Chlorophyll-specific growth rates {.unnumbered}

We used logistic curve fits (Fig. S1) to determine chlorophyll-specific growth rates (μ; d^−1^) for PC-rich and PE-rich cultures of *Synechococcus* sp. grown under spectral wavebands centred at 405, 450, 470, 530, 620, 660, or 730 nm, and [O~2~]  of 250 µM or 2.5 µM (Fig. <a href="#fig:GrowthRate">1</a>. Cell-specific growth rates (µ) were also determined using OD~720~ (Fig. S2). Strain, growth waveband, [O~2~], and their interactions, significantly affected μ (Table S4). 

PC-rich and PE-rich *Synechococcus* sp. grow under 2.5 µM [O~2~], across the range of tested spectral wavebands from 405 – 730 nm. In contrast under 250 µM [O~2~], the PC-rich strain failed to grow under 405 nm, while the PE-rich strain failed to grow under 405, 450, and 730 nm. Failure of growth under 405 & 450 nm is consistent with accelerated photoinactivation of PSII under blue wavebands, which increases the cost of growth [@murphyPhotoinactivationPhotosystemII2017]. The PC-rich strain showed generally similar growth rates under 2.5 and 250 µM [O~2~], across tested spectral wavebands (nm). In contrast the PE-rich strain achieved faster growth rates under 2.5 µM [O~2~] than under 250 µM [O~2~]. PE-rich *Synechococcus* are typically found at greater depths, and lower light, than are PC-rich strains [@haverkampColorfulMicrodiversitySynechococcus2009a;  @sliwinska-wilczewskaEcophysiologicalCharacteristicsRed2018], but we suggest that the PE-rich strains are actually limited to lower light by an interaction between light and full air-saturated [O~2~]. In lower oxygen waters PE-rich strains are likely able to exploit higher light niches.

PC-rich *Synechococcus* sp. showed a peak in growth rate under red light of 620 or 660 nm, absorbed by phycocyanin and chlorophyll. Under 2.5 µM [O~2~] the PE-rich strain showed highest growth rates under 530 nm-660 nm absorbed by phycoerythin, phycocyanin and chlorophyll; while under 250 µM O~2~], the PE-rich strain showed the highest growth rate under green light of 530 nm absorbed by phycoerythrin. 

<br>

![<span id="fig:GrowthRate"></span>**Fig. **1: Chlorophyll-specific growth rates (µ; d^−1^) vs. growth waveband (nm, shaded regions). Growth rates (± SE) were estimated from logistic fits of chlorophyll proxy OD~680~ – OD~720~ (ΔOD) vs. elapsed time (Fig. S1), for PC-rich (green circle) and PE-rich (red circle) cultures of *Synechococcus* sp. grown at spectral wavebands of 405, 450, 470, 530, 620, 660, or 730 nm, and [O~2~] of 250 µM (open symbols and dashed line) or 2.5 µM (closed symbols and solid line).](../Output/Figures/Fig_GrowthRateDelta.png)

<br>

## Pigment content and pigment ratio {.unnumbered}

Fig. <a href="#fig:Pigment">2</a>*a* presents Chlorophyll *a* (Chl *a*), Phycobiliproteins (Phyco), or Carotenoids (Car) content (pg cell ^−1^) vs. growth waveband (nm) for PC-rich and PE-rich cultures of *Synechococcus* sp. grown at spectral wavebands centred at 405, 450, 470, 530, 620, 660, or 730 nm and 250 or 2.5 µM [O~2~]. Here, we omit data from those PE-rich cultures which showed negligible growth under 405, 450, 730 nm and 250 µM O~2~; and from those PC-rich cultures which showed negligible growth under 405 nm and 250 µM O~2~. 

Strain, growth waveband, [O~2~], and their interactions, significantly affected cell-specific Chl *a*, Phycobiliproteins, and Car content (Table S5). For the PC-rich strain, the highest Chl *a*, Phycobiliproteins, and Car contents were recorded after growth under 730 nm. Moreover, the Phycobiliproteins content was higher under 250 µM [O~2~] than under 2.5 µM [O~2~] for the PC-rich strain. In contrast for PE-rich *Synechococcus* sp. phycobiliproteins content was significantly lower under 250 µM [O~2~] than under 2.5 µM [O~2~], with the highest phycobiliproteins content under  620 nm and 2.5 µM [O~2~].

Chlorophyll-specific growth rates (µ; d^−1^) show positive linear responses to Phycobiliproteins:Chlorophyll *a* ratio (µg:µg), for both PC-rich and PE-rich *Synechococcus* sp. (Fig. <a href="#fig:Pigment">2</a>*b*, Tab. S9), although the relations vary across strain and [O~2~] XXXXNOT PROPER TABLE CITATION - make Sylwia anova for pig ratio!! XXX. 

<br>

![<span id="fig:Pigment"></span>**Fig. **2: Pigment content (pg cell ^−1^) vs. growth waveband (nm; *a*) and Chlorophyll-specific growth rates (µ; d^−1^) vs. Phycobiliproteins:Chlorophyll *a* ratio (µg:µg) (*b*) for PC-rich (green circle) and PE-rich (red circle) cultures of *Synechococcus* sp. grown at spectral wavebands of 405, 450, 470, 530, 620, 660, or 730 nm and 250 µM [O~2~] (open symbols and dashed line) or 2.5 µM [O~2~] (closed symbols and solid line). Data not presented for those PE-rich cultures which showed negligible growth under 405, 450, 730 nm and 250 µM [O~2~]; nor for those PC-rich cultures which showed negligible growth under 405 nm and 250 µM [O~2~]. Blue lines shows linear model fit for data from each strain and [O~2~] (solid for 2.5 µM [O~2~] or dashed for 250 µM [O~2~]) across spectral wavebands. Different blue lowercase letters indicate statistically significant differences between the fit models for different strains or given [O~2~] (*t*-test; *p* < 0.05).](../Output/Figures/Fig_GrowthPig.png)

<br>

## Effective absorption cross sections, turnover times, and photochemical quenching of PSII {.unnumbered}

Light response curves of effective absorption cross section of PSII (σ~PSII~; nm^2^ quanta^−1^); turnover time of PSII photochemistry (τ~PSII~; µs); and photochemical quenching coefficient (q~P~) vs. Actinic PAR (µmol photons m^−2^s^−1^) (Fig. <a href="#fig:SigLRC">3</a>*a-c*) are shown for PC-rich and PE-rich cultures grown in, and excited by, corresponding wavebands of 450, 470, 530, or 620 nm, at 250 µM or 2.5 µM [O~2~]. We omit functional data for those PE-rich cultures which showed negligible growth under 405, 450, 730 nm and 250 µM O~2~; and for those PC-rich cultures which showed negligible growth under 405 nm and 250 µM O~2~. In the Supplementary materials (Fig S4-S6), we also show the light response curves for all available excitation (Ex~445nm~, blue; Ex~470nm~, blue-green; Ex~535nm~, green; or Ex~590nm~, orange) and growth waveband (450, 470, 530, or 620 nm) cross-combinations.

σ~PSII~ (Fig. <a href="#fig:SigLRC">3</a>*a*), as expected, was low and shows little change with increasing actinic light during excitation through chlorophyll at Ex~445nm~. In cyanobacteria the number of chlorophyll per PSII is low, and nearly fixed, so the effective absorbtion cross section for chlorophyll is also low  [@xuPhytoplanktonSPSIIExcitation2018].  For the PC-rich strain, under orange excitation at Ex~590nm~, σ~PSII~ showed an initial small increase from darkness to the growth light level, followed by a mild decrease with increasing Actinic PAR,  and was higher at 250 µM [O~2~] compared to 2.5 µM O~2~. For the PE-rich strain, we again see a small increase from darkness to the growth light level, followed by a decrease in σ~PSII~ with increasing Actinic PAR. Moreover, for the PE-rich strain σ~PSII~ was higher in low [O~2~] conditions than in high [O~2~] conditions. Strain, Actinic PAR, and [O~2~] significantly influenced σ~PSII~ under excitation at Ex~590nm~ (Table S6).

For the PC-rich strain, across the excitation wavebands tested, τ~PSII~ showed an acceleration (decrease) from darkness to growth light Actinic PAR (Fig. <a href="#fig:SigLRC">3</a>*b*), to a plateau of ~ 800 µs. PE-rich strains, on the other hand, showed a progressive acceleration (decrease) with increasing Actinic PAR under excitation at Ex~470nm~, Ex~535nm~, or Ex~590nm~, declining towards ~ 400 µs under Ex~590nm~.  Thus the PE-rich strain showed more capacity to remove electrons from PSII>  τ~PSII~, was generally faster (smaller) for both PC-rich and PE-rich strains under 250 µM [O~2~], consistent with the cyanobacterial capacity for electron transport away from PSII to [O~2~] [@campbellOxygendependentElectronFlow1999; @hughesRoadmapsDetoursActive2018], particularly under excess actinic light. Strain, Actinic PAR, and [O~2~] significantly affected τ~PSII~ at Ex~470nm~, Ex~535nm~ and Ex~590nm~ (Table S7).

q~P~, across the excitation wavebands tested, showed a strong decrease with increasing Actinic PAR (Fig. <a href="#fig:SigLRC">3</a>*c*). As expected @campbellOxygendependentElectronFlow1999; @hughesRoadmapsDetoursActive2018] q~P~ was generally higher for both PC-rich and PE-rich strains under 250 µM [O~2~], since cyanobacteria show strong capacity for electron flow away from PSII to O~2~, particularly under excess excitation. Strain, Actinic PAR, and [O~2~] significantly affected q~P~ at Ex~470nm~, Ex~535nm~, and Ex~590nm~ (Table S8). 

<br>

![<span id="fig:SigLRC"></span>**Fig. **3: Effective absorption cross section of PSII (σ~PSII~; nm^2^ quanta^−1^, *a*); turnover time of PSII photochemistry (τ~PSII~; µs, *b*); or photochemical quenching coefficient (q~P~, *c*) vs. Actinic PAR (µmol photons m^−2^s^−1^). Parameters were estimated using FRRf induction curves with excitation (columns) at Ex~445nm~, blue; Ex~470nm~, blue-green; Ex~535nm~, green; or Ex~590nm~, orange; for PC-rich (green circle) or PE-rich (red circle) cultures of *Synechococcus* sp. Data show situations in which cultures were excited by, and growing in, corresponding growth wavebands of 450, 470, 530, or 620 nm and 250 µM [O~2~] (open symbols and dashed line) or 2.5 µM [O~2~] (closed symbols and solid line). The vertical lines show half diel peak PAR growth light of 90 µmol photons m^−2^s^−1^. Data not presented for those PE-rich cultures which showed negligible growth under 405, 450, 730 nm and 250 µM O~2~; nor for those PC-rich cultures which showed negligible growth under 405 nm and 250 µM O~2~.](../Output/Figures/Fig_SigTauqp.png)

<br>

## Growth rates vs. cumulative diel PSII electron flux {.unnumbered}

Fig. <a href="#fig:GrowthRateJVPSII">4</a> presents linear regressions between chlorophyll-specific growth rates (µ; d^−1^) and PSII electron flux (*JV*~PSII~; µmol e^−^ µmol Chl *a*^−1^ d^−1^) measured under half diel peak PAR growth light. *JV*~PSII~ was estimated using FRRf induction curves with excitation at Ex~445nm~, Ex~470nm~, Ex~535nm~, or Ex~590nm~, corresponding to growth wavebands of 450, 470, 530, or 620 nm and 250 µM or 2.5 µM [O~2~]. We did not present data for those PE-rich cultures which showed negligible growth under 405, 450, 730 nm and 250 µM O~2~; nor for those PC-rich cultures which showed negligible growth under 405 nm and 250 µM O~2~. 

µ (d^−1^), as expected, is positively correlated with *JV*~PSII~.  For the PE-rich strain .... positively affects µ of the tested PE-rich picocyanobacteria? XXX Stop here, need stats firstXXX

<br>

![<span id="fig:GrowthRateJVPSII"></span>**Fig. **4: Chlorophyll-specific growth rates (µ; d^−1^) vs. PSII electron flux (*JV*~PSII~; µmol e^−^ µmol Chl *a*^−1^ d^−1^) measured under half diel peak PAR growth light. Growth rates (± SE) were estimated from logistic fits of chlorophyll proxy OD~680~ - OD~720~ (ΔOD) vs. elapsed time (Fig. S1). *JV*~PSII~ was estimated using FRRf induction curves with excitation at Ex~445nm~, blue; Ex~470nm~, blue-green; Ex~535nm~, green; or Ex~590nm~, orange; for PC-rich (green circle) or PE-rich (red circle) cultures of *Synechococcus* sp. Data show situations in which cultures were excited by, and growing in, corresponding growth wavebands of 450, 470, 530, or 620 nm and 250 µM [O~2~] (open symbols and dashed line) or 2.5 µM [O~2~] (closed symbols and solid line). Blue lines (solid for 2.5 µM [O~2~] or dashed for 250 µM O~2~) show linear model fit for data from each strain across spectral wavebands. Different blue lowercase letters indicate statistically significant differences between the fit models for different strains or given [O~2~] (*t*-test; *p* < 0.05).](../Output/Figures/Fig_GrowthRateJVPSII.png)

<br>


<br>

# Conclusions {.unnumbered}

<br>

# Acknowledgements {.unnumbered}

We thank Naaman Omar for assistance with coding, data analyses and culture maintenance; Miranda Corkum who maintained cultures and trained personnel in culture handling; Laurel Genge, and Carlie Barnhill (Mount Allison students) who assisted with R code. 

<br>

# Article information {.unnumbered}
## Data availability statement {.unnumbered}

Data supporting this study is available on:
https://github.com/FundyPhytoPhys/BalticO2 (public GitHub Repository) and
https://docs.google.com/spreadsheets/d/1ZXpwR7Gfto-uRzVdXzMpQF4frbrvMLH_IyLqonFZRSw/edit#gid=0 (URL for MetaDataCatalog).

Code to perform data processing and analyses is available at https://github.com/FundyPhytoPhys/BalticO2.

<br>

# Author information {.unnumbered}
## Author ORCIDs {.unnumbered}

Sylwia Śliwińska-Wilczewska https://orcid.org/0000-0002-3147-6605
Mireille Savoie https://orcid.org/0009-0009-9499-6657
Douglas A. Campbell https://orcid.org/0000-0001-8996-5463

<br>

## Author contributions {.unnumbered}

Conceptualization: SSW, DAC
Data curation: SSW
Formal analysis: SSW, MS, DAC
Funding acquisition: DAC
Investigation: SSW
Methodology: SSW, MS, DAC
Project administration: DAC
Resources: DAC
Supervision: DAC
Validation: SSW, MS, DAC
Visualization: SSW
Writing – original draft: SSW, MS, DAC

<br>

## Competing interests {.unnumbered}

The authors declare there are no competing interests.

<br>

## Funding information {.unnumbered}

This work was supported by Canada Research Chair in Phytoplankton Ecophysiology (DAC) and Latitude & Light; NSERC of Canada Discovery Grant (DAC).

<br>

# Supplementary material {.unnumbered}

Supplementary data are available with the article at https: //github.com/FundyPhytoPhys/BalticO2.

<br>

# References {.unnumbered}
