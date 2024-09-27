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

The picocyanobacterial genus *Synechococcus*, one of the most abundant primary producers in marine ecosystems, comprises a diversity of strains of differing pigmentations, thriving across diverse niches. Oxygen Minimum Zones with low [O~2~] are expanding in both open ocean and coastal habitats. We found that PhycoCyanin- and PhycoErythrin-rich *Synechococcus* both grow under 2.5 µM [O~2~], characteristic of Oxygen Minimum Zones, across a range of spectral wavebands from 405 – 730 nm. The PhycoCyanin-rich strain showed generally similar chlorophyll-specific growth rates (µ; d^−1^) under 2.5 and 250 µM [O~2~], whereas PhycoErythrin-rich cultures achieved faster growth rates, across the spectral bandwidths, under 2.5 µM [O~2~] than under 250 µM [O~2~]. For PhycoCyanin- and PhycoErythrin-rich  *Synechococcus*, µ showed also positive linear responses to both Phycobiliproteins:Chlorophyll *a*, and to cumulative diel PSII electron flux, although the relations vary across strain and [O~2~]. Electron transport downstream of Photosystem II was generally higher for both PhycoCyanin- and PhycoErythrin-rich strains under 250 µM [O~2~], since cyanobacteria show strong capacity for electron flow away from PSII to O~2~, particularly under excess excitation. In spite of this stronger electron transport under 250 µM [O~2~], the PhycoErythrin-rich strain showed a higher growth yield of electron transport under 2.5 µM [O~2~]. PhycoErythrin-rich *Synechococcus* are currently typically found at greater depths, and lower light, than are PhycoCyanin-rich strains, but we suggest that the PhycoErythrin-rich strains are actually limited to lower light by an interaction between light and full air-saturated [O~2~]. In expanding Oxygen Minimum Zones PhycoErythrin-rich strains will likely exploit higher light niches, across a wider spectral range.

<br>

**Key words:** Colour, niches, OMZs, oxygen concentration, PC-rich strain, PE-rich strain, spectral wavebands, *Synechococcus*

<br>

# Introduction {.unnumbered}

Since the mid-20^th^ century, declining oxygen concentrations in regions of the open ocean, and in coastal waters [@breitburgDecliningOxygenGlobal2018] are affecting productivity, biodiversity, and biogeochemical cycles in marine ecosystems [@keelingOceanDeoxygenationWarming2010]. Low oxygen environments in the ocean, termed Oxygen Minimum Zones (OMZ) have expanded to an area equivalent to the European Union, and the global volume of oxygen-free water has quadrupled [@breitburgDecliningOxygenGlobal2018]. It is thus necessary to understand which species will survive and dominate under ongoing and predicted changes in ocean and coastal oxygen concentrations.

Oxygenic picocyanobacteria numerically dominate the phytoplankton across vast tracts of the world’s oceans, notably in oligotrophic regions, but also in some coastal ecosystems [@larssonPicocyanobacteriaContainingNovel2014; @sliwinska-wilczewskaEcophysiologicalCharacteristicsRed2018; @aguileraEcophysiologicalAnalysisReveals2023]. Oxygen is a product of photosynthesis, and a substrate for reductant consumption, but also has potential to damage Photosystem II (PSII) protein subunits [@anderssonPhotodamagePhotosystemII1992]. The oxygen evolving complex of PSII can also be directly inactivated by a photon in the UV or blue range directly absorbed by the Mn~4~Ca cluster [@hakalaEvidenceRoleOxygenevolving2005; @partenskyComparisonPhotosyntheticPerformances2018]; therefore, oxygen interacts with spectral band to influence the balance between productive photosynthesis and costly photoinactivations [@murphyPhotoinactivationPhotosystemII2017]. OMZ pose challenges for aerobic organisms [@breitburgDecliningOxygenGlobal2018], but picocyanobacteria inhabiting OMZs have genetic adaptations enabling them to tolerate and even thrive in oxygen-depleted environments, such as changes in energy metabolism, antioxidant defense mechanisms, and cellular structures optimized for oxygen scavenging and storage [@ulloaMicrobialOceanographyAnoxic2012; @bagbyResponseProchlorococcusVarying2015; @partenskyComparisonPhotosyntheticPerformances2018; @callieriDarkSidePicocyanobacteria2022a; @wongPhytoplanktonRequireOxygen2023; @ulloaCyanobacteriumProchlorococcusHas2021]. 

Picocyanobacteria also show photosynthetic adaptations to spectral wavebands, ranging from short-wavelength blue light [@luimstraBlueLightReduces2018], through green and yellow light to long-wavelength red light. Plankton ecologists have long acknowledged that a diverse array of photosynthetic pigments allows cyanobacteria species to exploit different spectral wavebands [@falkowskiEvolutionModernEukaryotic2004; @stompColourfulCoexistenceRed2007a]. The ecological success of picoplanktonic *Synechococcus* strains throughout the photic oceanic water column [@flombaumPresentFutureGlobal2013] results in part from diverse strategies to respond to variations in their environment [@scanlanMarinePicocyanobacteria2012]. The genus *Synechococcus* is genetically diverse and divided into several major clusters. Picocyanobacteria from *Synechococcus* cluster 5, often found in marine, brackish and freshwater environments [@aguileraEcophysiologicalAnalysisReveals2023], includes sub-clusters of strains rich in phycoerythrin (PE-rich), which imparts a range of orange, reddish, pink, and purple colors, as well as sub-clusters of strains rich in phycocyanin (PC-rich), which color the organism in various shades of blue-green [@stompAdaptiveDivergencePigment2004a]. Competition experiments demonstrate that PC-rich and PE-rich strains can coexist in white light but show spectral niche differentiation [@haverkampShadesRedGreen2008]. 

PE-rich strains, with high content of the chromophore phycourobilin (PUB), dominate oligotrophic deep waters where blue light predominates, and deep communities in more mesotrophic marine waters, characterized by blue-green light environments [@haverkampColorfulMicrodiversitySynechococcus2009a; @stompAdaptiveDivergencePigment2004a] are shifting towards PE-rich Synechococcus with more phycoerythrobilin (PEB). Conversely, PC-rich strains prevail near the surface, and in turbid waters where orange and red light dominate. The widespread coexistence of PC-rich and PE-rich picocyanobacteria is observed in waters of intermediate turbidity, such as mesotrophic lakes and coastal seas [@haverkampColorfulMicrodiversitySynechococcus2009a; @haverkampShadesRedGreen2008].

Our aim was to test the growth and functional responses of PC-rich and PE-rich *Synechococcus* cultures to the interaction of different oxygen concentrations (250 µM or 2.5 µM [O~2~]), and spectral wavebands (405 – 730 nm). We thus empirically answer the question posed by @wongPhytoplanktonRequireOxygen2023 regarding the sensitivity of modern picocyanobacteria to low levels of O~2~ and a wide range of wavebands found across depths and trophic levels.

<br>

# Materials and methods {.unnumbered}

## Culture condition and experimental setup {.unnumbered}

Xenic cultures of  PC-rich (CCBA_077) and PE-rich (CCBA_127) *Synechococcus* were obtained from the Culture Collection of Baltic Algae (https://ccba.ug.edu.pl/pages/en/home.php) [@latalaCultureCollectionBaltic2006]. *Synechococcus* strains were cultured in Tissue Culture Flasks (VWR International, Cat. No. 10062-872, PA, USA) and transferred biweekly to fresh f/2 media [@guillardCulturePhytoplanktonFeeding1975] prepared at a salinity of 8 PSU, reflective of their natural brackish habitat. Pre-cultures were maintained in incubators with full air saturated dissolved oxygen concentration [O~2~] of 250 µM, 22℃, with a light/dark cycle of 12 hours (h) and Photosynthetically Active Radiation (PAR) of 10 µmol photons m^−2^s^−1^ from Philips Cool White F14T5/841 Alto, 14 watts, fluorescent bulbs.

Controlled growth experiments were performed using MCMIX-OD PSI Multicultivators (Photon Systems Instruments, Drásov, Czech Republic) set to 22℃. Each of 8 round bottom cylindrical glass tubes contained 75 mL of f/2 medium and 5 mL of growing pre-culture. These parameters allowed for exponential growth of the cultures from the beginning of the experiment, with little lag phase. Inoculation of culture tubes took place in the afternoon, with a period of low light and then 12 h darkness before a sinusoidal 12 h photoperiod cycle commenced at 07:00 the following morning, with peak PAR of 180 µmol photons m^−2^s^−1^ reached at 13:00 each day.

Each tube was maintained under an individual combination of one of 7 spectral wavebands centred at 405, 450, 470, 530, 620, 660, or 730 nm and under 250 µM or 2.5 µM [O~2~]. Culture tubes were closed with a silicone inert silicone stopper perforated by an aeration input tube extending to the bottom of the culture tube, and a pressure outlet tube. We used aeration with a total gas flow rate of around ~ 140 mL min^−1^ tube^−1^ through a 0.2µm sterile microfilter provided via a G400 gas mixing system (Qubit Systems Inc., Kingston, Ontario, Canada). ~ 250 µM [O~2~] was achieved by sparging with lab air (78% N~2~, 21% O~2~, 1% Ar and 0.05% CO~2~). ~ 2.5 µM [O~2~] was achieved by sparging with a gas mixture containing 99.95% N~2~ and 0.05% CO~2~. [O~2~] *in situ* was verified using oxygen optodes (PyroScience, Germany) inserted into tubes for real-time measurements (data not presented), with software correction to account for the salinity of the media (8 PSU). The pH of tested cultures remained about 8, with limited fluctuation during the growth experiment (data not presented). 

<br>

## Chlorophyll-specific growth rates {.unnumbered}

Picocyanobacterial growth was monitored every 5 minutes by automatically recording OD~680~, OD~720~, and ΔOD (ΔOD = OD~680~ – OD~720~) for at least 5 days, independently for each culture tube. The chlorophyll-specific growth rates (µ) were determined by fitting logistic growth curves using a modified Levenberg-Marquardt fitting algorithm [@elzhovMinpackLmInterface2023] to plots of the chlorophyll *a* proxy of ΔOD vs. elapsed time (d) for each combination of strain, spectral waveband, and [O~2~].

<br>

## Picocyanobacteria cell counts {.unnumbered}

Picocyanobacterial cells mL^−1^ were estimated using linear regression models of OD at 680 nm or 720 nm vs. calibration counts of cell suspension densities (cell mL^−1^) (Tab. S1). The OD of cultures was measured using MCMIX-OD PSI Multicultivators (Photon Systems Instruments, Drásov, Czech Republic) and cell suspension density measures were conducted using an ImageXpress Pico Digital microscope equipped with CMOS camera and LED+ image autofocus (ImageXpress Pico Automated Cell Imaging System, Molecular Devices, LLC., CA, USA). Culture samples were preserved with 4% glutaraldehyde and kept at -80°C until the microscopy measures. Fixed samples of culture (V = 10 µL) were transferred to surface treated Tissue Culture (TC) black walled 96-well plates (Corning® Falcon® Microplate, MilliporeSigma, Merck, Darmstadt, Germany) with a transparent flat bottom containing 200 µL of f/2 media and centrifuged using a Beckman J-20 centrifuge with a swinging bucket JS-4.3 rotor at 4500 rpm (Beckman Coulter, Brea, California, United States). Cells were imaged with the Cy5 channels (Excitation: 630/40 nm; Emission: 695/45 nm; Dichroic: 655 nm) using selectable confocal geometries, which differentiates cyanobacterial cells from co-occurring heterotrophic bacteria, and counted using a 63x objective in fluorescence imaging modes. Quantitative analysis on images acquired from automated microscopy obtained from 96-well microplates was performed using the CellReporterXpress Image Acquisition and Analysis Software. The representative cell number mL^−1^ was calculated based on the dilution factor and selected count area from each well [@wlodkowicRecentProgressCytometric2022].

<br>

## Pigment content and pigment ratio {.unnumbered}

Whole-cell absorbance spectra of picocyanobacteria cells were collected using an integrating cavity spectrophotometer (CLARiTY 17 UV/Vis/NIR, On-Line Instrument Systems, Inc., Bogart, GA, USA) according to the method proposed by @blakeSituSpectroscopyIntact2012. The sample and reference observation cavities of the spectrophotometer were filled with 8 mL of f/2 medium at salinity 8 PSU. After establishing a baseline absorbance spectra from 375 to 710 nm, 4 mL culture medium was replaced with 4 mL of culture in the sample cavity. Pathlength corrected absorbance per cm was calculated using Jávorfi coefficients [@javorfiQuantitativeSpectrophotometryUsing2006]. We then conducted estimations of pigment content (µg mL^−1^) including Chlorophyll *a* (Chl *a*), Carotenoids (Car), Phycoerythrin (PE), Phycocyanin (PC), and Allophycocyanin (APC) from the PC-rich and PE-rich *Synechococcus* cultures. These estimations were based on established linear correlations between pigment content, determined through extraction methods [@stricklandPracticalHandBook1972; @bennettComplementaryChromaticAdaptation1973], and absorbance values of individual pigment peaks (Car; 480 nm, PE; 565 nm, PC; 620 nm, APC; 650 nm, and Chl *a*; 665 nm) obtained from whole-cell absorbance spectra (Tab. S2). Additionally, we summed PE, PC, and APC protein to total Phycobiliproteins content. 

Using whole-cell absorbance spectra of *Synechococcus* cultures, we also estimated Photosynthetically Usable Radiation (PUR; µmol photons m^−2^s^−1^) according to [@morelAvailableUsableStored1978]. 

<br>

## PSII effective absorption cross section of PSII, turnover time of PSII photochemistry, and photochemical quenching {.unnumbered}

We harvested 4 mL of picocyanobacteria cultures repeatedly across the growth trajectories for photophysiological characterizations. For the low oxygen cultures, to ensure photophysiological measurements were taken at low O~2~ of ~ 2.5 µM, we bubbled gently with N~2~ from a gas cylinder during measurements. [O~2~] was verified in culture samples for photophysiological measurements using oxygen optodes (PyroScience, Germany) inserted (data not presented). 

We used Fast Repetition & Relaxation chlorophyll fluorescence (FRRf) [@kolberMeasurementsVariableChlorophyll1998] (Solisense, USA), with a lab built temperature control jacket (22℃), to apply a series of 100 excitation flashlets of 1.6 µs to drive saturation of PSII variable fluorescence, followed immediately by logarithmically spaced flashlets to track relaxation of variable fluorescence. Induction/relaxation trajectories were fit using the onboard Solisense LIFT software [@falkowskiEstimationPhytoplanktonPhotosynthesis1993; @kolberMeasurementsVariableChlorophyll1998].

We used a double tap protocol [@xuConnectivityPhotosystemII2017], where FRRf induction/relaxation trajectories were collected during a rapid actinic light curve sequence increasing in steps of 10 s at 0, 20, 40, 80, 160, and 320 µmol photons m^−2^s^−1^ PAR. We applied 1 s darkness between the sequential 10 s steps of the light response curves, to allow re-opening of PSII immediately after application of the sequential increasing light steps. Flashlets and actinic light were delivered from LED emitters centred at Ex~445nm~, preferentially exciting chlorophyll; Ex~470nm~, preferentially exciting phycourobilin (PUB); Ex~535nm~, preferentially exciting phycoerythrin (PE); or Ex~590nm~, preferentially exciting phycocyanin (PC). Excitation flashlets and actinic light wavebands were matched for each run. These actinic and excitation wavebands in turn approximated 4 of our 7 growth light wavebands (450, 470, 530 & 620 nm), allowing us to evaluate *in situ* photosynthetic performance for those culture conditions.

Flashlet power delivered to the samples during the 1.6 µs flashlet duration was adjusted to achieve saturation of variable fluorescence; Ex~445nm~ at 60000 µmol photons m^−2^s^−1^ PAR; Ex~470nm~ at 30000 µmol photons m^−2^s^−1^ PAR; Ex~535nm~ at 25000 µmol photons m^−2^s^−1^ PAR; while for Ex~590nm~ excitation power at 14000 µmol photons m^−2^s^−1^, calibrated using a quantum sensor (LI-250, LI-COR, Inc.) in the temperature controlled cuvette. 

We estimated effective absorption cross section of PSII (σ~PSII~; nm^2^ quanta^−1^); turnover time of PSII photochemistry (τ~PSII~; µs); and the photochemical quenching coefficient (q~P~) using the FRRf induction curves, following [@xuConnectivityPhotosystemII2017].  We fit a model with three τ~PSII~ to describe the re-opening of PSII after closure by the saturating flash train.  For subsequent analyses we estimated an average of the three τ~PSII~, weighted by their respective amplitudes, to describe the overall time to reopen PSII after closure.

<br>

## PSII electron flux {.unnumbered}

We calculated (Eq. (1)) an uncalibrated fluorescence based estimator for volumetric electron transport, *JV*~PSII~, (k × e^−^ L^−1^ s^−1^) under Ex~445nm~, blue; Ex~470nm~, blue-green; Ex~535nm~, green; or Ex~590nm~, red-orange excitation bands [@oxboroughDirectEstimationFunctional2012; @boatmanImprovingAccuracySingle2019; @tortellUserGuideApplication2021].


$$\begin{equation}
  {JV_{PSII}} = \frac{σ_{PSII}′ × q_{P} × I × F_O}{σ_{PSII} }
  \qquad(1)
\end{equation}$$


where σ~PSII~′ is effective absorption cross section for PSII photochemistry under the relevant actinic PAR step (nm^2^ quanta^−1^); q~P~ is an estimate of the fraction of PSII open for photochemistry estimated according to @oxboroughResolvingChlorophyllFluorescence1997; I is the applied PAR (µmol photons m^−2^s^−1^); *F*~O~ is the minimum fluorescence from a given sample and excitation waveband (relative fluorescence) and σ~PSII~ is the maximum effective absorption cross section for PSII photochemistry from a given sample and excitation waveband (nm^2^ quanta^−1^). 

We calibrated the *JV*~PSII~ estimator to absolute rates of electron transport (Eq. (2)) using parallel measures of oxygen evolution (µmol O~2~ L^−1^ s^−1^), captured simultaneously with the FRRf measures, taken below light saturation of electron transport to limit distortion from electron fluxes back to oxygen under super-saturating light [@hughesRoadmapsDetoursActive2018], using a FireSting robust oxygen probe (PyroScience, Germany) inserted in the cuvette for select Rapid Light Curve (RLC) runs (Tab. S3). 

$$\begin{equation}
  {JV_{PSII}(e^{−}~L^{−1}~s^{−1})} = \frac{Uncalibrated~JV_{PSII}(e^{−}~L^{−1}~s^{−1})}{Calibration~slope}
  \qquad(2)
\end{equation}$$


We converted *JV*~PSII~ (µmol e^−^ L^−1^ s^−1^) to *JV*~PSII~ (µmol e^−^ µmol Chl *a*^−1^ d^−1^) by performing Chl *a* (µg L^−1^) measurements using Trilogy Laboratory Fluorometer (Turner Designs, Inc., CA, USA) equipped with Chlorophyll In-Vivo Module, on the samples taken for the FRRf measurements.

To generate an index of the ratio of Chl *a* : PSII we divided PSII electron transport (e- PSII^-1^ s^-1^) by *JV*~PSII~ (e- Chl^-1^ s^-1^), both estimated under Ex~445nm~,  with units cancelling to Chl *a* : PSII.  Since the number of Chl *a* directly associated with the core of PSII is fixed, variations in Chl *a* to PSII reflect changes in the PSI:PSII ratio, and possibly the presence of other chl-containing complexes.

<br>

## Statistical analysis {.unnumbered}

We used R version 4.3.0 [@rcore] running under RStudio [@posit]. We performed three-way factorial ANOVA (*aov()* function; R Base package) to determine whether strain, growth waveband, and [O~2~] significantly influence the chlorophyll-specific growth rate (µ; d^−1^; Tab. S4) or pigment content (Tab. S5). We also performed three-way factorial ANOVA (*aov()* function) to determine whether strain, Actinic PAR, and [O~2~] significantly influence the responses of σ~PSII~ (Tab. S6); τ~PSII~ (Tab. S7); q~P~ (Tab. S8); or *JV*~PSII~ (Tab. S9) to increasing light. We fit the light response curves of *JV*~PSII~ with a three parameter model [@harrisonPhotosynthesisirradianceRelationshipsPolar1986] using [@elzhovMinpackLmInterface2023] for *nlsLM()* function. Three-way factorial ANOVA (*aov()* function; R Base package) was performed to determine whether strain, growth waveband, and [O~2~] significantly influence Chl *a* to PSII (Tab. S10).

We used *t*-tests of linear regressions to compare data across different strains and [O~2~] for a given growth waveband, for chlorophyll-specific growth rate vs. Phycobiliproteins to Chl *a* ratio (Tab. S11). We also performed *t*-tests of linear fits to compare data across different strains and [O~2~] in situations in which cultures were excited by, and growing in, corresponding growth wavebands of 450, 470, 530, or 620 nm, for chlorophyll-specific growth rate vs. *JV*~PSII~ (Tab. S12). Statistical differences for all analyses were determined at significance level α = 0.05. 

The manuscript was prepared as a Rmarkdown document [@handelAndreasHandelCustom2020] with figures plotted using ggplot2 [@wickhamDataAnalysis2016] and patchwork [@pedersenPatchworkComposerPlots2024] packages. All metadata, data, and code is available on GitHub (https://github.com/FundyPhytoPhys/BalticO2).

<br>

# Results {.unnumbered}

## Chlorophyll-specific growth rates across [O~2~], spectral wavebands, and strains {.unnumbered}

We used logistic curve fits (Fig. S1) to determine chlorophyll-specific growth rates (μ; d^−1^) for PC-rich and PE-rich cultures of *Synechococcus* grown under spectral wavebands centred at 405, 450, 470, 530, 620, 660, or 730 nm, and [O~2~]  of 250 µM or 2.5 µM (Fig. <a href="#fig:GrowthRate">1</a>). Growth curves, tracked as OD~680~, OD~720~, ΔOD and logistic fits of ΔOD vs. elapsed time are shown in Fig. S1 in Supplementary materials. Cell-specific growth rates (µ) were also determined using OD~720~ (Fig. S2). Strain, growth waveband, [O~2~], and their interactions, significantly affected μ (Tab. S4). 

PC-rich and PE-rich *Synechococcus*  grow under 2.5 µM [O~2~], across the range of tested spectral wavebands from 405 – 730 nm. In contrast, under 250 µM [O~2~], the PC-rich strain failed to grow under 405 nm, while the PE-rich strain failed to grow under 405, 450, and 730 nm. The PC-rich strain showed generally similar growth rates under 2.5 and 250 µM [O~2~], across tested spectral wavebands (nm). In contrast the PE-rich strain achieved faster growth rates under 2.5 µM [O~2~] than under 250 µM [O~2~]. 

PC-rich *Synechococcus*  showed a peak in growth rate under both [O~2~] and red light of 620 or 660 nm, absorbed by phycocyanin and chlorophyll. Under 2.5 µM [O~2~] the PE-rich strain showed high growth rates under 530 nm – 660 nm absorbed by phycoerythin, phycocyanin, and chlorophyll; while under 250 µM [O~2~], the PE-rich strain showed the highest growth rate under green light of 530 nm absorbed by phycoerythrin. 

<br>

![<span id="fig:GrowthRate"></span>**Fig. **1: Chlorophyll-specific growth rates (µ; d^−1^) vs. growth waveband (nm, shaded regions). Growth rates (± SE) were estimated from logistic fits of chlorophyll proxy OD~680~ – OD~720~ (ΔOD) vs. elapsed time (Fig. S1), for PC-rich (green circle) and PE-rich (red circle) cultures of *Synechococcus*  grown at spectral wavebands of 405, 450, 470, 530, 620, 660, or 730 nm, and [O~2~] of 250 µM (open symbols and dashed line) or 2.5 µM (closed symbols and solid line).](../Output/Figures/Fig_GrowthRateDelta.png)

<br>

## Pigment content and pigment ratio across [O~2~], spectral wavebands, and strains {.unnumbered}

Fig. <a href="#fig:Pigment">2</a>*a* presents Chlorophyll *a* (Chl *a*), Phycobiliproteins (Phyco), or Carotenoids (Car) content (pg cell ^−1^) vs. growth waveband (nm) for PC-rich and PE-rich cultures of *Synechococcus* grown at spectral wavebands centred at 405, 450, 470, 530, 620, 660, or 730 nm and 250 or 2.5 µM [O~2~]. We also calculated the Car to Chl *a* ratio, and the ratio of the sum of Phycobiliproteins to Chl *a* (µg:µg) for each strain (Fig. S3). Moreover, phycobiliproteins:Chlorophyll *a* ratio (µg:µg) and chlorophyll-specific growth rates (µ; d^−1^) vs. Photosynthetically Usable Radiation (PUR, µmol photons m^−2^s^−1^) for PC-rich and PE-rich cultures of *Synechococcus* grown at spectral wavebands of 405, 450, 470, 530, 620, 660, or 730 nm and 250 µM [O~2~] or 2.5 µM [O~2~] are presented in Fig. S4.

To focus on the responses of growing cells, we omit pigmentation data from those PE-rich cultures which showed negligible growth under 405, 450, 730 nm and 250 µM [O~2~]; and from those PC-rich cultures which showed negligible growth under 405 nm and 250 µM [O~2~]. 

Strain, growth waveband, [O~2~], and their interactions, significantly affected cell-specific Chl *a*, Phycobiliproteins, and Car content (Tab. S5). For the PC-rich strain, the highest Chl *a*, Phycobiliproteins, and Car contents were recorded after growth under 730 nm. The phycobiliproteins content was higher under 250 µM [O~2~] than under 2.5 µM [O~2~] for the PC-rich strain. In contrast, for PE-rich *Synechococcus*, phycobiliproteins content was significantly lower under 250 µM [O~2~] than under 2.5 µM [O~2~], with the highest phycobiliproteins content under 620 nm and 2.5 µM [O~2~].

Chlorophyll-specific growth rates (µ; d^−1^) show positive linear responses to the Phycobiliproteins:Chlorophyll *a* ratio (µg:µg), for both PC-rich and PE-rich *Synechococcus*  (Fig. <a href="#fig:Pigment">2</a>*b*), although the relations vary across strain and [O~2~] (Tab. S11). 

<br>

![<span id="fig:Pigment"></span>**Fig. **2: Pigment content (pg cell ^−1^) vs. growth waveband (nm) (*a*) and Chlorophyll-specific growth rates (µ; d^−1^) vs. Phycobiliproteins:Chlorophyll *a* ratio (µg:µg) (*b*) for PC-rich (green circle) and PE-rich (red circle) cultures of *Synechococcus*  grown at spectral wavebands of 405, 450, 470, 530, 620, 660, or 730 nm and 250 µM [O~2~] (open symbols and dashed line) or 2.5 µM [O~2~] (closed symbols and solid line). Data not presented for those PE-rich cultures which showed negligible growth under 405, 450, 730 nm and 250 µM [O~2~]; nor for those PC-rich cultures which showed negligible growth under 405 nm and 250 µM [O~2~]. Blue lines shows linear model fit for data from each strain and [O~2~] (solid for 2.5 µM [O~2~] or dashed for 250 µM [O~2~]) across spectral wavebands. Different blue lowercase letters indicate statistically significant differences between the fit models for different [O~2~] within a given strain. Different blue uppercase letters indicate statistically significant differences between the fit models for different strains within a given [O~2~] (*t*-test; *p* < 0.05).](../Output/Figures/Fig_GrowthPig.png)

<br>

## Effective absorption cross sections, turnover times, and photochemical quenching of PSII across [O~2~], spectral wavebands, and strains {.unnumbered}

Light response curves of effective absorption cross section of PSII (σ~PSII~; nm^2^ quanta^−1^); turnover time of PSII photochemistry (τ~PSII~; µs); and the photochemical quenching coefficient (q~P~) vs. Actinic PAR (µmol photons m^−2^s^−1^) (Fig. <a href="#fig:SigLRC">3</a>*a-c*) are shown for PC-rich and PE-rich cultures grown in, and excited by, corresponding wavebands of 450, 470, 530, or 620 nm, at 250 µM or 2.5 µM [O~2~]. We omit functional data determined for those PE-rich cultures which showed negligible growth under 405, 450, 730 nm and 250 µM O~2~; and for those PC-rich cultures which showed negligible growth under 405 nm and 250 µM O~2~. In the Supplementary materials (Fig S5-S7), we also show the light response curves for all available excitation (Ex~445nm~, blue; Ex~470nm~, blue-green; Ex~535nm~, green; or Ex~590nm~, orange) and growth waveband (450, 470, 530, or 620 nm) cross-combinations.

σ~PSII~ (Fig. <a href="#fig:SigLRC">3</a>*a*), a measure of excitation driving PSII photochemistry, was low and shows little change with increasing actinic light during excitation through chlorophyll at Ex~445nm~. For the PC-rich strain, under orange excitation at Ex~590nm~, σ~PSII~ showed an initial small increase from darkness to the growth light level, followed by a mild decrease with increasing Actinic PAR, and was higher at 250 µM [O~2~] compared to 2.5 µM [O~2~]. For the PE-rich strain, we again see a small increase from darkness to the growth light level, followed by a decrease in σ~PSII~ with increasing Actinic PAR. Moreover, for the PE-rich strain σ~PSII~ was higher in low [O~2~] conditions than in high [O~2~] conditions. Strain, Actinic PAR, and [O~2~] significantly influenced σ~PSII~ under excitation at Ex~590nm~ (Tab. S6).

For the PC-rich strain, across the excitation wavebands tested, τ~PSII~ showed an acceleration (decrease) from darkness to growth light Actinic PAR (Fig. <a href="#fig:SigLRC">3</a>*b*), to a plateau of ~ 800 µs. PE-rich strains, on the other hand, showed a progressive acceleration (decrease) with increasing Actinic PAR under excitation at Ex~470nm~, Ex~535nm~, or Ex~590nm~, declining towards ~ 400 µs under Ex~590nm~. Thus, the PE-rich strain showed more capacity to remove electrons from PSII. τ~PSII~, was generally faster (smaller) for both PC-rich and PE-rich strains under 250 µM [O~2~]. Strain, Actinic PAR, and [O~2~] significantly affected τ~PSII~ at Ex~470nm~, Ex~535nm~ and Ex~590nm~ (Tab. S7).

q~P~, a measure of the fraction of PSII available for photochemistry,  showed a strong decrease with increasing Actinic PAR across the excitation wavebands tested (Fig. <a href="#fig:SigLRC">3</a>*c*). q~P~  generally remained higher for both PC-rich and PE-rich strains under 250 µM [O~2~]. Strain, Actinic PAR, and [O~2~] significantly affected q~P~ at Ex~470nm~, Ex~535nm~, and Ex~590nm~ (Tab. S8). 

<br>

![<span id="fig:SigLRC"></span>**Fig. **3: Effective absorption cross section of PSII (σ~PSII~; nm^2^ quanta^−1^) (*a*); turnover time of PSII photochemistry (τ~PSII~; µs) (*b*); or photochemical quenching coefficient (q~P~) (*c*) vs. Actinic PAR (µmol photons m^−2^s^−1^). Parameters were estimated using FRRf induction curves with excitation (columns) at Ex~445nm~, blue; Ex~470nm~, blue-green; Ex~535nm~, green; or Ex~590nm~, orange; for PC-rich (green circle) or PE-rich (red circle) cultures of *Synechococcus*. Data show situations in which cultures were excited by, and growing in, corresponding growth wavebands of 450, 470, 530, or 620 nm and 250 µM [O~2~] (open symbols and dashed line) or 2.5 µM [O~2~] (closed symbols and solid line). The vertical lines show half diel peak PAR growth light of 90 µmol photons m^−2^s^−1^. Data not presented for those PE-rich cultures which showed negligible growth under 405, 450, 730 nm and 250 µM O~2~; nor for those PC-rich cultures which showed negligible growth under 405 nm and 250 µM O~2~.](../Output/Figures/Fig_SigTauqp.png)

<br>

## PSII electron flux across [O~2~], spectral wavebands, and strains {.unnumbered}


PSII electron flux (*JV*~PSII~) measures the generation of reductant available to support biosynthetic assimilation and growth. *JV*~PSII~ was estimated using FRRf inductions with excitation at Ex~445nm~, Ex~470nm~, Ex~535nm~, or Ex~590nm~, corresponding to growth wavebands of 450, 470, 530, or 620 nm and 250 µM or 2.5 µM [O~2~]. To focus on responses of growing cells, we do not present *JV*~PSII~ data for those PE-rich cultures which showed negligible growth under 405, 450, 730 nm and 250 µM O~2~; nor for those PC-rich cultures which showed negligible growth under 405 nm and 250 µM O~2~. PSII electron flux (*JV*~PSII~; µmol e^−^ µmol Chl *a*^−1^ s^−1^) vs. Actinic PAR (µmol photons m^−2^s^−1^) estimated using FRRf induction curves with excitation at Ex~445nm~, blue; Ex~470nm~, blue-green; Ex~535nm~, green; or Ex~590nm~, orange; for PC-rich or PE-rich cultures of *Synechococcus* grown at spectral bandwidths of 450, 470, 530, or 620 nm and O~2~ concentrations of 250 µM or 2.5 µM are also presented (Fig. S8).

Light response curves of PSII electron flux (*JV*~PSII~; µmol e^−^ µmol Chl *a*^−1^ s^−1^) vs. Actinic PAR (µmol photons m^−2^s^−1^) are shown in Fig. <a href="#fig:JVPSII">4</a>*a*. For the PC-rich strain, under all tested excitations (Ex~445nm~, Ex~470nm~, Ex~535nm~, or Ex~590nm~), *JV*~PSII~ increased with increasing Actinic PAR, and did not fully saturate across the range of tested actinic PAR. Under all excitations, except Ex~590nm~, *JV*~PSII~ was higher at 2.5 µM [O~2~] compared to 250 µM [O~2~] for the PC-rich strain. Conversely, for the PE-rich strain, *JV*~PSII~ under Ex~470nm~, Ex~535nm~, or Ex~590nm~ was higher at 250 µM [O~2~] compared to 2.5 µM [O~2~]. Moreover, for the PE-rich strain, *JV*~PSII~ plateaued above ~90 µmol photons m^−2^s^−1^ under Ex~535nm~, or Ex~590nm~ for both low and high [O~2~]. Strain, Actinic PAR, and [O~2~] significantly influence *JV*~PSII~ under some of the tested excitations (Tab. S9), but *JV*~PSII~ for cultures grown under, and excited through, Ex~445nm~, absorbed by chlorophyll, shows no difference between low and high [O~2~] with increasing actinic light.

Fig. <a href="#fig:JVPSII">4</a>*b* presents linear regressions between chlorophyll-specific growth rates (µ; d^−1^) and cumulative diel PSII electron flux (*JV*~PSII~; µmol e^−^ µmol Chl *a*^−1^ d^−1^) measured under half (90 µmol photons m^−2^s^−1^) of the diel peak PAR growth light. µ (d^−1^), as expected, was positively correlated with *JV*~PSII~, with slopes significantly greater than 0. [O~2~] significantly influences the linear regressions between chlorophyll-specific growth rates and PSII electron flux for both PC-rich and PE-rich strains of *Synechococcus*  (*p* < 0.05, Tab. S12). In the PC-rich strain higher [O~2~] increases the growth yield of electron transport. In contrast, the PE-rich strain, under higher [O~2~], decreases the growth yield of electron transport. However, the regressions for a given [O~2~] are not significantly different between the two strains (*p* > 0.05, Tab. S12). 

Strain, actinic PAR waveband, and [O~2~] significantly influence Strain, Actinic PAR, and [O~2~] significantly influence our metric of Chl *a* : PSII (<a href="#fig:PSII"><strong>??</strong></a>  (Tab. S9), with Chl *a* : PSII higher under 250 than under 2.5 µM [O~2~] in the PC-rich strain, and Chl *a* : PSII generally lower in the PC-rich stain compared to the PE-rich strain.

<br>

![<span id="fig:JVPSII"></span>**Fig. **4: PSII electron flux (*JV*~PSII~; µmol e^−^ µmol Chl *a*^−1^ s^−1^) vs. Actinic PAR (µmol photons m^−2^s^−1^) (*a*). *JV*~PSII~ was estimated using FRRf induction curves with excitation at Ex~445nm~, blue; Ex~470nm~, blue-green; Ex~535nm~, green; or Ex~590nm~, orange; for PC-rich (green circle) or PE-rich (red circle) cultures of *Synechococcus*. Data show situations in which cultures were excited by, and growing in, corresponding growth wavebands of 450, 470, 530, or 620 nm and 250 µM [O~2~] (open symbols and dashed line) or 2.5 µM [O~2~] (closed symbols and solid line). *JV*~PSII~ vs. Actinic PAR (µmol photons m^−2^s^−1^) was fit with a Harrison and Platt Light Response Curve model [@harrisonPhotosynthesisirradianceRelationshipsPolar1986], used to estimated *JV*~PSII~ at 90 µmol photons m^−2^s^−1^ (vertical dotted lines). Chlorophyll-specific growth rates (µ; d^−1^) vs. PSII electron flux (*JV*~PSII~; µmol e^−^ µmol Chl *a*^−1^ d^−1^) measured under half (90 µmol photons m^−2^s^−1^) of diel peak PAR growth light (*b*). Blue lines (solid for 2.5 µM [O~2~] or dashed for 250 µM O~2~) show linear model fit for data from each strain across spectral wavebands. Different blue lowercase letters indicate statistically significant differences between the fit models for different [O~2~] within a given strain. Different blue uppercase letters indicate statistically significant differences between the fit models for different strains within a given [O~2~] (*t*-test; *p* < 0.05).](../Output/Figures/Fig_JVPSII.png)

<br>

# Discussion {.unnumbered}

## Growth responses of PC-rich and PE-rich picocyanobacteria across [O~2~] and spectral wavebands {.unnumbered}

Picocyanobacteria from the genus *Synechococcus* are major contributors to primary marine production, across a wide range of environments [@aguileraEcophysiologicalAnalysisReveals2023; @sliwinska-wilczewskaEcophysiologicalCharacteristicsRed2018] but interactive influences of [O~2~] and spectral wavebands on their growth rates and ecophysiology have not yet been investigated.

PC-rich and PE-rich *Synechococcus* from coastal habitats are exposed to changes in irradiance, spectral waveband, and sometimes [O~2~], by vertical movements through the mixed layer. Fluctuation in spectral wavebands changes the balance between productive photosynthesis, and photoinactivation of PSII [@sixLightVariabilityIlluminates2007], increasing the cost of growth by diverting protein metabolism towards PSII repair [@murphyPhotoinactivationPhotosystemII2017]. Indeed, under 250 µM [O~2~], the PC-rich strain failed to grow under 405 nm, while the PE-rich strain failed to grow under 405 and 450, consistent with accelerated photoinactivation of PSII under blue wavebands [@murphyPhotoinactivationPhotosystemII2017]. In contrast, growth persisted in both strains at 405 & 450 nm under 2.5 µM [O~2~], likely because generation of toxic Reactive Oxygen Species (ROS) was suppressed, lowering the burden of photoinactivation of PSII. 

µ shows positive responses to both Phycobiliproteins:Chlorophyll *a* ratio, an index of light capture capacity, and to cumulative diel PSII electron flux (*JV*~PSII~) for *Synechococcus*, although the relations varied across strain and with [O~2~]. In the PC-rich strain lower [O~2~] lowered the yield of growth per electron flux, while in the PE-rich strain the yield of growth per electron flux increased under lower [O~2~]. Note that these regressions excluded those conditions where no growth occurred. In contrast, growth showed no correlation to estimated Photosynthetically Usuable Radiation (PUR) (Fig. S4), likely because of variable allocations of excitation from phycobilisomes across growth conditions [@campbellComplementaryChromaticAdaptation1996], not captured in the PUR metric based upon light absorption.

@wongPhytoplanktonRequireOxygen2023 found that vertical structures of phytoplankton communities in OMZ are not sufficiently explained by top-down predation pressure nor light and/or nutrient limitation and thus, some phytoplankton may have a higher than expected direct O~2~ requirement, with growth inhibited by low O~2~ levels. However, in our work we show that low oxygen levels either do not affect, or sometimes even benefit, growth of different *Synechococcus*  phenotypes across spectral wavebands. What is more, historical data link major extinction events to warm climates and oxygen-deficient oceans, with current anthropogenic activities possibly leading to widespread OMZ within a thousand years [@breitburgDecliningOxygenGlobal2018]. The PC-rich *Synechococcus* strain showed generally similar growth rates under high and low tested [O~2~], while the PE-rich strain achieved faster growth rates under low (2.5 µM) than under high (250 µM) [O~2~]. PE-rich *Synechococcus* are typically found at greater depths, and lower light, than are PC-rich strains [@haverkampColorfulMicrodiversitySynechococcus2009a; @sliwinska-wilczewskaEcophysiologicalCharacteristicsRed2018] but we suggest that the PE-rich strains may  actually be limited to lower light niches by the interaction between light level, spectral band, and full air-saturated [O~2~]. In lower oxygen waters PE-rich strains will likely exploit higher light niches nearer the surface.

<br>

## Physiological adaptations of PC-rich and PE-rich picocyanobacteria to [O~2~] and spectral wavebands {.unnumbered}

*Synechococcus* strains vary widely in pigment composition, enabling them to exploit different spectral niches [@mooreComparativePhysiologySynechococcus1995; @sixLightVariabilityIlluminates2007; @grebertLightColorAcclimation2018a; @efimovaInfluenceLightDifferent2020]. With a small diameter of 0.8–2.0 µm, *Synechococcus*  possess a high surface-to-volume ratio [@sliwinska-wilczewskaAllelopathicBloomformingPicocyanobacteria2018], minimizing pigment package effects [@finkelLightAbsorptionSize2001], and resulting in high optical absorption per pigment. This characteristic allows them to thrive under low light deep in the water column [@mooreComparativePhysiologySynechococcus1995], and to disproportionately influence sub-surface light fields [@bertholdPhosphorusDynamicsEutrophic2020]. Although limited package effect increases photon capture per pigment investment, it also increases *Synechococcus*  susceptibility to light-induced damage [@llabresEffectsUltravioletRadiation2010; @llabresPicophytoplanktonCellDeath2006]. In some *Synechococcus*, a carotenoid-protein complex regulates the connectivity of the phycobilisome to the reaction center, mediating a form of non-photochemical quenching of excitation [@wilsonSolubleCarotenoidProtein2006; @gorbunovKineticModelNonphotochemical2011; @kirilovskyModulatingEnergyArriving2015]. In our work we found no change in bulk carotenoids content (Fig. <a href="#fig:Pigment">2</a>), nor in Car to Chl *a* ratio (Fig. S3) under the different [O~2~]. What is more, for the PE-rich strain, the carotenoids content did not change across tested wavebands. On the other hand, for PC-rich picocyanobacteria, a slight increase in carotenoids content was recorded under 405 nm, although these cells were not growing and were thus under stress.

σ~PSII~ was low and showed little change with increasing actinic light during excitation through chlorophyll at Ex~445nm~, because in cyanobacteria the number of chlorophyll per PSII is low, and nearly fixed, so the effective absorption cross section of PSII for chlorophyll is low  [@xuPhytoplanktonSPSIIExcitation2018].  With excitation through the phycobilisomes at 535 and 590 nm σ~PSII~ rose to a peak near the acclimated light level of ~ 90 µmol photons m^−2^s^−1^ [@campbellPredictingLightAcclimation1996a], reflecting the state transition mechanism.

τ~PSII~ was generally faster for both PC-rich and PE-rich strains under 250 µM [O~2~], consistent with the cyanobacterial capacity for pseudo-cyclic electron flows away from PSII to [O~2~] [@campbellOxygendependentElectronFlow1999; @hughesRoadmapsDetoursActive2018; @grossmanPerspectivePhotosynthesisOligotrophic2010; @allahverdiyevaCyanobacterialOxygenicPhotosynthesis2015], thereby controlling feedback inhibition of electron transport, and decreasing the risks of ROS production. In parallel,q~P~ was generally higher for PC-rich, and particularly for PE-rich strains, under 250 µM [O~2~], since cyanobacteria show strong capacity for electron flow away from PSII to O~2~ [@campbellOxygendependentElectronFlow1999; @hughesRoadmapsDetoursActive2018], particularly under excess excitation above the acclimated PAR of ~ 90 µmol photons m^−2^s^−1^. In spite of this superior electron transport performance under 250 µM [O~2~] the PE-rich strain grew faster under 2.5 µM [O~2~], showing an increase in the growth return upon electron transport.

Picocyanobacteria numerically dominate vast tracts of the oceans, contributing significant primary production, particularly in oligotrophic regions, but also some coastal habitats [@aguileraEcophysiologicalAnalysisReveals2023; @larssonPicocyanobacteriaContainingNovel2014; @haverkampShadesRedGreen2008; @doreGlobalPhylogeographyMarine2022]. The ecological success of picoplanktonic *Synechococcus* reflects specific lineages occupying different niches to populate the world’s oceans [@scanlanMarinePicocyanobacteria2012]. Picocyanobacteria species can share the light spectrum by specializing in different wavelengths [@haverkampColorfulMicrodiversitySynechococcus2009a; @stompAdaptiveDivergencePigment2004a; @stompColourfulCoexistenceRed2007a]. Competition models and laboratory experiments show that PE-rich picocyanobacteria outperform competitors in green light while PC-rich picocyanobacteria dominate in red light, while both species can coexist across the full spectrum [@stompAdaptiveDivergencePigment2004a; @stompColourfulCoexistenceRed2007a]. We now find that spectral wavebands interact with [O~2~] as determinants of growth rates across different *Synechococcus* strains, and that changing ocean [O~2~] may drive different pigmentation phenotypes into changing ecological niches.

<br>

# Acknowledgements {.unnumbered}

We thank Naaman M. Omar for assistance with coding, data analyses and culture maintenance; Miranda Corkum who maintained cultures and trained personnel in culture handling; Laurel Genge, and Carlie Barnhill (Mount Allison students) who assisted with R code. 

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