🧪 OptoAnalytica - Inclusive Webcam Spectrometer for Hazardous Dye Analysis


⚠️ WORK IN PROGRESS - NOT COMPLETE YET
This project is currently under active development. The documentation, code, and experimental results are still being finalized.


📌 Overview
This project aims to develop a low-cost, open-source spectrometer using a standard webcam and a DVD diffraction grating, combined with Principal Component Analysis (PCA) to detect and classify illegal synthetic dyes (such as Rhodamin B) in traditional Indonesian street snacks (jajanan pasar).

The instrument is designed to be affordable, replicable by schools and communities, and capable of distinguishing between legal and illegal food colorants despite overlapping spectral signatures.


🎯 Research Objectives
Design, build, and test a functional spectrometer using a webcam and DVD grating to capture visible light spectra (400–700 nm) with adequate resolution

Extract spectral features from dye samples (Rhodamin B, Tartrazin, Sunset Yellow, Metanil Yellow) and apply PCA to objectively classify dye types


🔬 Background
Food safety is a critical public health concern in Indonesia. Between March 2024 and March 2025, BPOM (Indonesian Food and Drug Authority) found multiple food products containing hazardous substances, including Rhodamin B (a textile dye) and Borax. The number of such findings has been increasing by 10–20% annually over the past three years.

While standard UV-Vis spectrophotometers can detect these dyes, they cost hundreds of millions of rupiah and are inaccessible to many schools, community health centers, and remote areas. This project addresses that gap by building a functional alternative for under 2 million rupiah (≈ $130 USD) .


🧠 Methods
Instrument Design
-Light source: White LED

-Dispersion element: DVD-R grating (~1350 lines/mm), reflective layer removed

-Detector: USB webcam (2+ MP, IR filter removed)

-Sample holder: Standard 1 cm pathlength cuvette

-Enclosure: Black cardboard or 3mm plywood (30×20×15 cm)

-Calibration
Using neon lamp spectral lines (404.7, 435.8, 546.1, 577.0, 579.1 nm)

-Verification with red (650 nm), green (532 nm), and blue (470 nm) LEDs

-Data Processing
Spectral extraction using Tracker or ImageJ

-PCA implementation via Python (scikit-learn, matplotlib)

-Normalization using Z-score to eliminate concentration effects

-Validation
-Blind testing on synthetic samples (target accuracy >90%)

-Reproducibility testing (RSD <5%)

-Limit of detection (LOD) determination


📊 Expected Outcomes
Component	Expected Result
Spectrometer cost	< 2 million IDR (~$130 USD)
Wavelength range	400–700 nm
Resolution	Sufficient to distinguish dye peaks
PCA classification accuracy	>90% (target)
Open-source deliverables	Hardware design + Python analysis code


🛠️ Materials (Estimated)
Item	Quantity	Estimated Cost (IDR)
Webcam (2 MP)	1 unit	500,000
DVD-R	2 pieces	30,000
3mm plywood/triplek	6 sheets	20,000
Glass cuvette (1 cm)	2 pieces	60,000
White LED	1 unit	(included)
Neon lamp (for calibration)	4 pieces	120,000
Tartrazin (dye standard)	-	180,000
Metanil Yellow	-	50,000
Rhodamin B	-	50,000
Total (approx.)		~1,739,000 IDR


📚 Key References
Vernando, E., & Uranus, H. P. (2015). Development of simple spectrometer using DVD-R grating and webcam CCD sensor.

Kaykhaii et al. (2020). Smartphone-based spectrophotometer for organic dye monitoring. ACS Omega.

Rahmawati et al. (2023). PCA-LDA for tofu dye classification using Vis-NIR spectroscopy. Food Science and Technology.

Widiatmoko et al. (2011). Simple spectrophotometer using common materials and digital camera. Physics Education.


👥 Researchers
Keanu Dasha Harison – SMA Negeri 5 Surabaya
Muhammad Arlo Heilife – SMA Negeri 5 Surabaya

Affiliation: ITS DKv, SMA Negeri 5 Surabaya, Jawa Timur, Indonesia

Timeline: February – July 2026


📝 To-Do List (What's Missing)
Complete physical spectrometer assembly
Perform wavelength calibration with neon/mercury lamps
Collect spectral data for all dye standards
Implement PCA pipeline in Python
Run blind tests on spiked food samples
Calculate accuracy, reproducibility, and LOD
Upload all raw data and analysis code
Add photos and assembly diagrams
Write step-by-step replication guide


📄 License (Tentative)
This project is intended to be released as open-source hardware/software to enable replication by schools, community labs, and food safety volunteers. Specific license to be determined upon completion.


🙏 Acknowledgments
SMA Negeri 5 Surabaya for laboratory access
BPOM East Java for published food safety data
ITS Visual Communication Design department for 3d printing and prototyping access


📬 Contact
@keanudasha_4


Last updated: June 2026
Status: 🔴 Not complete – research in progress
