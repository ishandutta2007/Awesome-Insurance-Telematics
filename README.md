# Awesome-Insurance-Telematics

## Top Insurance Telematics Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Usage-Based Insurance (UBI), Driving Behavior Scoring, Smartphone & Hardware Telematics, Risk Insights & Safe-Driving Programs*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Insurance Telematics**. These solutions collect and analyze driving data (via smartphone apps or connected devices) to support usage-based insurance, driver scoring, claims insights, and safer-driving incentives.

**Examples** include Cambridge Mobile Telematics, Octo Telematics, IMS, TrueMotion, Arity, DriveQuant, The Floow, LexisNexis Telematics, Trak Global, and Greater Than (the category leaders).

**Open-source emphasis**: Full commercial-grade insurance telematics platforms (with production SDKs, actuarial-grade scoring, and insurer integrations) are almost exclusively proprietary. However, useful open-source reference apps, SDKs demos, end-to-end UBI pipelines, driver-behavior models, and research projects exist. This section highlights every significant active project.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Cambridge Mobile Telematics (CMT)](https://www.cmtelematics.com/)**  
  Leading smartphone-based telematics platform powering many major UBI and safe-driving programs with advanced sensing, distraction detection, and risk scoring.

- **[Octo Telematics](https://www.octotelematics.com/)**  
  Global insurance telematics provider offering both hardware and smartphone solutions, widely used across Europe and other markets for UBI and claims services.

- **[IMS](https://www.ims.tech/)**  
  Insurance telematics specialist providing smartphone and device-based solutions for usage-based insurance and driver behavior insights.

- **[TrueMotion (Cambridge Mobile Telematics)](https://www.cmtelematics.com/)**  
  Smartphone telematics technology (now part of the broader CMT portfolio) focused on accurate trip detection and driving behavior measurement.

- **[Arity](https://www.arity.com/)**  
  Mobility data and analytics company (Allstate-backed) offering telematics-derived risk insights and UBI capabilities.

- **[DriveQuant](https://www.drivequant.com/)**  
  Smartphone telematics and driving-behavior analytics platform used by insurers and mobility players for scoring and engagement.

- **[The Floow](https://www.thefloow.com/)**  
  Telematics and data-analytics provider specializing in insurance and mobility risk insights, with strong European presence.

- **[LexisNexis Telematics / Risk Solutions](https://risk.lexisnexis.com/)**  
  Data and analytics offerings that incorporate telematics and driving data into insurance risk assessment and underwriting tools.

- **[Trak Global / Trakm8 and related](https://www.trakglobal.com/)**  
  Telematics and connected-vehicle solutions serving insurance and fleet use cases.

- **[Greater Than](https://www.greaterthan.eu/)**  
  AI-powered risk assessment platform that uses driving and mobility data to generate insurance risk scores and insights.

## Open-Source GitHub Projects

- **[Damoov / Mobile-Telematics (ZenRoad & SDK demos)](https://github.com/mobile-telematics)**  
  Open-source reference telematics apps (iOS & Android) and SDK integration samples for smartphone trip detection, driving behavior, and UBI-style product surfaces.

- **[Telematics UBI end-to-end pipelines](https://github.com/AjaySreekumar47/Sreekumar_Ajay_TelematicsUBI)**  
  Full proof-of-concept pipelines covering telematics event ingestion, feature engineering, claim frequency/severity modeling, driver risk scoring, and interactive dashboards.

- **[Driver behavior & UBI research projects](https://github.com/search?q=telematics+UBI+OR+driver+behavior+insurance)**  
  Academic and practitioner repositories that process GPS/IMU data, detect harsh events, cluster driver profiles, and build risk models for usage-based insurance.

- **[Chorus Mobility & incentive demos](https://github.com/chorusmobility/driver-behavior-android-ethereum-app)**  
  Prototype Android applications exploring driving-behavior scoring combined with token or incentive mechanisms for safer driving.

- **[Fleet & telematics analytics frameworks](https://github.com/surajit003/siphyy)**  
  Open-source agentic frameworks for fleet telematics analytics (driver behavior, anomalies, predictive maintenance) that can be adapted for insurance-oriented insights.

- **[IoT / edge telematics platforms](https://github.com/Benaah/DenoDrive)**  
  Modular open-source platforms for collecting vehicle sensor data, performing behavior analysis, and feeding dashboards or insurance-style scoring engines.

- **[Feature engineering & risk modeling notebooks](https://github.com/migue-rc/car-insurance)**  
  Explorations of telematics-derived features (GPS, G-force events) for driver profiling and insurance risk assessment using supervised and unsupervised methods.

### Additional Strong Open-Source Options

- **Smartphone sensor pipelines**: Libraries and sample apps for collecting accelerometer, gyroscope, GPS, and activity-recognition data.
- **Harsh-event detection**: Open algorithms for hard braking, rapid acceleration, sharp cornering, and speeding.
- **Trip segmentation**: Tools that detect trip start/stop and mode of transportation from mobile sensor streams.
- **Risk model building blocks**: Feature stores, scoring notebooks, and model-serving examples tailored to driving data.
- **Privacy-preserving techniques**: Research code exploring on-device processing or differential privacy for telematics.
- Various university and hackathon projects focused on **distracted driving detection**, **drowsiness**, and **UBI pricing engines**.

**Frameworks for building custom systems**:  
Start with open-source smartphone sensing and trip-detection reference apps (e.g., Damoov-style SDKs or custom sensor pipelines).  
Engineer behavioral features (speed profiles, harsh events, time-of-day, mileage).  
Train risk or claim models using open ML libraries and validate carefully.  
Serve scores via APIs and integrate with policy admin or engagement systems.  
Production insurance telematics still requires rigorous validation, regulatory review, actuarial oversight, and usually a commercial-grade sensing SDK for accuracy and battery efficiency.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Insurance telematics involves sensitive location and behavior data, regulatory requirements (privacy, insurance licensing, fair-rating rules), and actuarial standards. Any system used for pricing or underwriting must comply with applicable laws and be validated by qualified professionals.
- Open-source prototypes are valuable for research and learning but are not substitutes for production-grade, insurer-approved telematics platforms.

---

**Made for insurance product managers, telematics engineers, data scientists, and mobility innovators.**  
Let's advance safer driving and fairer risk assessment through transparent tools and responsible use of driving data.