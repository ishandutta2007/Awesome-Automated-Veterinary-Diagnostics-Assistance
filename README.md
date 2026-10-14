# Awesome-Automated-Veterinary-Diagnostics-Assistance

# Top Automated Veterinary Diagnostics Assistance Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Veterinary Imaging AI, Disease Detection & Clinical Decision Support*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Automated Veterinary Diagnostics Assistance**. These tools enable veterinarians, clinics, and animal-health programs to analyze medical images, detect diseases earlier, and augment clinical decision-making—using AI models trained on veterinary-specific data.

**Examples** include SignalPET, Vet-AI, Antech Diagnostics, Idexx VetLab, PetDx, Vet-Anatomy, Heska, Zoetis Dx, Vetspire, and Scribenote (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, veterinary-specific AI models, and open clinical infrastructure—ideal for veterinary researchers, clinics, and developers seeking transparent, vendor-independent diagnostic assistance.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[SignalPET](https://www.signalpet.com/)**  
  AI-powered veterinary radiology platform providing instant X-ray analysis. Uses deep learning to detect and classify abnormalities in canine and feline radiographs, delivering diagnostic reports to practitioners within minutes.

- **[Vet-AI](https://www.vet-ai.com/)**  
  AI-powered veterinary diagnostic support platform. Features clinical decision support, symptom analysis, and differential diagnosis assistance for veterinary practices.

- **[Antech Diagnostics](https://www.antechdiagnostics.com/)**  
  Veterinary reference laboratory with AI-enhanced diagnostic services including imaging analysis, pathology, and clinical chemistry. Provides comprehensive diagnostic panels for companion animals.

- **[Idexx VetLab](https://www.idexx.com/en/veterinary/)**  
  Industry-leading veterinary diagnostics platform with in-house laboratory analyzers, digital radiography, and AI-assisted imaging interpretation. Integrates with practice management software.

- **[PetDx](https://www.petdx.com/)**  
  Liquid biopsy platform for early cancer detection in dogs. Uses next-generation sequencing to detect circulating tumor DNA from blood samples.

- **[Vet-Anatomy](https://www.vet-anatomy.com/)**  
  Interactive veterinary anatomy reference platform with imaging correlation for education and clinical reference.

- **[Heska](https://www.heska.com/)**  
  Veterinary diagnostic and imaging solutions including digital radiography, point-of-care testing, and AI-assisted analysis tools.

- **[Zoetis Dx](https://www.zoetis.com/)**  
  Veterinary diagnostics division providing point-of-care testing, reference laboratory services, and imaging solutions for companion and production animals.

- **[Vetspire](https://www.vetspire.com/)**  
  Cloud-based veterinary practice management software with integrated diagnostic tools, treatment planning, and AI-assisted clinical documentation.

- **[Scribenote](https://www.scribenote.com/)**  
  AI-powered veterinary medical scribe that automatically generates clinical notes from veterinary appointments. Reduces documentation burden for practitioners.

## Open-Source GitHub Projects

- **[VetFractureAI](https://github.com/alvendherfrancisco/vet-fracture-ai)**  
  Open-source AI model for femoral shaft fracture detection and AO/OTA classification in dogs and cats (Apache-2.0). Uses **Faster R-CNN (ResNet-50 + FPN V2)** to detect and classify fractures from veterinary X-rays. **88.36% mAP@0.5** with **97.83% specificity** for no-fracture detection. Trained on **1,264 veterinary radiographs** (690 dogs, 574 cats) with AP and lateral views, annotated in COCO JSON format. Dataset available on Hugging Face. Includes FastAPI backend and web frontend. **Academic and non-commercial use only** .

- **[CARE Janwar](https://ohc.network/solutions/care-janwar)**  
  Open-source animal health infrastructure (MIT-licensed) adapting CARE Core for veterinary clinics, public animal-health programs, and field teams . Features longitudinal animal records linked to owners and facilities, veterinary encounters (outpatient, inpatient, field-visit), vaccination workflows with schedules and reminders, diagnostics and lab order tracking, pharmacy and inventory management, billing and accounts, mobile-first field workflows, and program dashboards. **Self-hostable for public-sector ownership** with role-based access and audit trails. AI-ready for field-note drafting, summaries, and stock review .

- **[RadioVet-h (viggoVet)](https://huggingface.co/viggovet/RadioVet-h)**  
  Open-weight veterinary radiology language model (7B parameters, CC BY-NC-SA 4.0) with **ISO/IEC 42001:2023 certification** . Features a **hybrid Sequential-Transformer architecture** achieving up to **70% memory reduction** vs. transformer-only models. Trained on peer-reviewed veterinary medical literature and radiology-specific cases. Provides clinical assessment, differential diagnoses, recommended diagnostic workup, and treatment considerations for veterinary radiology consultations. **Non-commercial license** restricts commercial deployment .

- **[abirmed_animal_slm](https://huggingface.co/abirmaheshwari/abirmed_animal_slm)**  
  Open-source veterinary and animal health specialist language model (MIT) as part of the ABIRMED Modular Medical Specialist Transformer System . **~38 million parameters** (8 layers, 8 attention heads, 512 hidden size) trained from scratch on curated veterinary educational datasets covering animal diseases, symptoms, and clinical reasoning for dogs, cats, and companion animals. **CPU-efficient inference** due to small model size. **Explicitly out-of-scope for veterinary diagnosis or treatment decisions**—research and education only .

- **[FMD AI Diagnosis System](https://zenodo.org/records/20171884)**  
  Open-source pre-trained YOLO11 and YOLO26 Oriented Bounding Box (OBB) model weights for automated **Foot and Mouth Disease (FMD) detection in cattle** . Detects 6 classes: Mouth Saliva, Mouth Sores, Nail Sores, Head, Healthy Mouth, Healthy Nails. Available in PyTorch (.pt) and ONNX (.onnx) formats. GitHub repository: [Ahmet-zmn/FMD](https://github.com/Ahmet-zmn/FMD). Licensed for research use .

- **[DISEASE_DETECTOR](https://github.com/im-Amrith/DISEASE_DETECTOR)**  
  Open-source livestock disease diagnostic web application using **MobileNetV2** and **Flask** . Detects **7 livestock skin conditions** including Bovine Respiratory Disease, Contagious Ecthyma, Dermatitis, and Lumpy Skin Disease. Features instant analysis with confidence scores, responsive UI, and mobile support. **Educational and supportive purposes only**—does not replace professional veterinary diagnosis .

- **[Canine Pneumothorax Detection](https://github.com/Pu-Wang-alt/Canine-pneumothorax)**  
  Open-source AI system for interpretable **canine pneumothorax diagnosis** (arXiv 2604.05482) . Uses **VLM-guided Flow Matching** for precise lesion segmentation combined with **Random Matrix Theory (RMT)** for spectral anomaly detection. Models healthy tissue as predictable random noise and identifies pneumothorax through statistically significant outlier eigenvalues. Provides highly accurate and **interpretable diagnostic results** with source code available .

- **[SEPO-WBC](https://github.com/)**  
  Open-source software for **automatic detection and classification of white blood cells in canine blood smear images** to compute differential counts . Uses two-stage design: YOLOv8 detection model (**mAP@50 of 0.935**) followed by DenseNet-201 classification (**accuracy of 0.878**). Clinical evaluation with five veterinary pathology experts confirmed **ICC score of 0.969** for detection and classification agreement of 0.855-0.883—within inter-expert agreement range. Significantly faster than manual analysis .

- **[OpenVPM (OpenPIMS)](https://github.com/evangauer/openvpm)**  
  Open-source veterinary practice information management system (PIMS) with **API-first architecture** . Features typed clinical data tables (SOAP notes, vaccination records, lab results, procedures, problem lists, cases), scheduling with recurring appointments, prescriptions with drug interaction checks, billing and inventory management. **REST API v1** with scoped API keys for integrations including AI agents and AI scribes. Docker Compose deployment with PostgreSQL and MinIO . More than **50,000 people** run it themselves according to the maintainer .

- **[Yosemite Crew](https://www.yosemitecrew.com/)**  
  Open-source, self-hostable, **FHIR-native** veterinary practice management system . Brings appointments, patient records, SOAP notes, diagnostics, treatment, billing, inventory, tasks, and client communication into one connected system. **Open-source and free to run** with desktop and mobile apps .

- **[Goat Disease Prediction (AIOT)](https://github.com/Biancaa-R/Goat-disease-prediction-using-AIOT-)**  
  Open-source IoT + AI system for predicting goat diseases using wearable sensors and external camera . Diseases covered: PPR-Scabby Mouth, Tetanus, Anthrax, Goat Pox. Uses **YOLO model in ONNX format** deployed on Raspberry Pi 4B for PPR detection. Features MQTT communication between Raspberry Pi and ESP8266, sensor data via ThingSpeak cloud, and Flask app for notifications .

- **[pig-respiratory-monitor](https://zenodo.org/records/20084414)**  
  Open-source code, pre-computed **Audio Spectrogram Transformer (AST) embeddings**, and leave-one-animal-out fold definitions for detecting breathing of individual piglets in noisy commercial barns (Zenodo v1.0.2) . Contains 1,553 ten-second segments from 16 piglets recorded with contact electronic stethoscope. Primary task: detection of audible breathing (**macro F1 0.8592**, 95% cluster-bootstrap interval 0.767-0.897, nested leave-one-animal-out cross-validation). Development continues at [Willy-chen/pig-respiratory-monitor](https://github.com/Willy-chen/pig-respiratory-monitor) .

### Additional Strong Open-Source Options

- **[MONAI](https://github.com/Project-MONAI/MONAI)** — Open-source framework for deep learning in healthcare imaging (Apache-2.0). Extends PyTorch with medical imaging-specific architectures, transformations, and utilities. Foundation for veterinary imaging AI development .
- **[VET-DINO](https://github.com/)** — Self-supervised learning framework leveraging multiple standardized views from the same study for anatomical understanding in veterinary imaging .
- **[V-REX](https://github.com/)** — Efficient specialist VLM for veterinary X-rays generating diagnostic reports. Uses fraction of parameters and compute of generalist models .
- **[RapidRead](https://github.com/)** — Semi-supervised learning approach combining NLP-derived labels with self-supervised training on 2.5M+ x-ray images for veterinary teleradiology .
- Community **n8n** workflows for veterinary diagnostic alert routing and clinical documentation automation.

**Frameworks for building custom systems**: Combine **VetFractureAI** for fracture detection with **RadioVet-h** for radiology clinical reasoning, **OpenVPM** or **Yosemite Crew** for practice management and patient records, **MONAI** for custom imaging model development, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade veterinary diagnostics platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Veterinary diagnostic AI tools are **clinical decision support aids, not replacements for licensed veterinarians**. All AI outputs must be validated by qualified veterinary professionals before clinical use.
- **Open-source veterinary AI is research-stage.** VetFractureAI is academic and non-commercial use only . RadioVet-h is CC BY-NC-SA 4.0 licensed . abirmed_animal_slm explicitly states it is **not intended for veterinary diagnosis or treatment decisions**—research and education only . DISEASE_DETECTOR is for educational and supportive purposes .
- **Dataset limitations affect generalizability.** Most open-source models are trained on limited datasets (e.g., 1,264 radiographs for VetFractureAI) and may not generalize to different imaging equipment, patient populations, or clinical settings. Always validate on local data before deployment.
- Self-hosted open-source solutions require proper security hardening, veterinary domain validation, and ongoing maintenance. Veterinary patient data is subject to professional confidentiality obligations and may fall under data protection regulations (GDPR, CCPA, etc.) depending on jurisdiction.

---

**Made for veterinarians, veterinary researchers, animal-health program managers, and developers building transparent diagnostic assistance solutions.**  
Let's make Automated Veterinary Diagnostics Assistance more open, data-driven, and clinically validated.
