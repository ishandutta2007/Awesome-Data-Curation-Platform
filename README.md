# Awesome-Data-Curation-Platform

# Top Data Curation Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Dataset Management, Active Learning, Embedding-Based Selection, Annotation, Quality Assurance & Data-Centric AI Workflows*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Curation**. These tools help ML teams select the most valuable data, remove redundancy, manage large datasets, accelerate labeling, detect label errors, and close the loop between data and models.

**Examples** include Lightly, Activeloop, DagsHub, Snorkel AI, Encord, Dataloop, Labelbox, Kili Technology, Scale AI, and SuperAnnotate (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for dataset visualization, curation, annotation, and quality improvement. Leading tools such as FiftyOne, CVAT, Label Studio, and LightlyStudio provide powerful self-hosted alternatives.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Lightly](https://www.lightly.ai/)**  
  Embedding-based data curation platform specializing in selecting the most informative samples for computer vision and reducing labeling waste (also offers open-source components).

- **[Activeloop](https://www.activeloop.ai/)**  
  Dataset management and streaming platform (Deep Lake) focused on efficient storage, versioning, and loading of large multimodal datasets for ML.

- **[DagsHub](https://dagshub.com/)**  
  Data science collaboration platform with dataset versioning, experiment tracking, and data-centric workflow support built around Git and DVC.

- **[Snorkel AI](https://snorkel.ai/)**  
  Programmatic labeling and data-centric AI platform that enables weak supervision, labeling functions, and scalable training data creation.

- **[Encord](https://encord.com/)**  
  Enterprise multimodal data annotation, curation, and model evaluation platform with strong support for images, video, medical data, and compliance.

- **[Dataloop](https://dataloop.ai/)**  
  End-to-end data operations and annotation platform combining dataset management, labeling pipelines, and automation for AI teams.

- **[Labelbox](https://labelbox.com/)**  
  Leading cloud-native data labeling and training-data platform with model-assisted labeling, quality workflows, and enterprise features.

- **[Kili Technology](https://kili-technology.com/)**  
  Annotation and data quality platform with strong support for document, NLP, and computer-vision use cases, often favored for EU data residency.

- **[Scale AI](https://scale.com/)**  
  Full-stack data engine providing high-quality annotation services, dataset management, and evaluation for frontier and production AI models.

- **[SuperAnnotate](https://www.superannotate.com/)**  
  Annotation platform with automation, quality assurance, and managed workforce options for image, video, and multimodal data.

## Open-Source GitHub Projects
- **[FiftyOne (Voxel51)](https://github.com/voxel51/fiftyone)**  
  Leading open-source tool for dataset visualization, curation, embedding analysis, model evaluation, and finding label errors or edge cases.

- **[CVAT (Computer Vision Annotation Tool)](https://github.com/cvat-ai/cvat)**  
  Widely used open-source annotation platform for images, video, and 3D data with AI-assisted labeling, team collaboration, and strong community support.

- **[Label Studio](https://github.com/HumanSignal/label-studio)**  
  Flexible open-source multi-type data labeling tool supporting images, text, audio, video, time series, and custom interfaces.

- **[LightlyStudio](https://github.com/lightly-ai)**  
  Open-source data curation and labeling platform from Lightly, focused on embedding-based selection and computer-vision workflows.

- **[Cleanlab](https://github.com/cleanlab/cleanlab)**  
  Open-source library for automatically detecting label errors, outliers, and data quality issues using confident learning techniques.

- **[Argilla](https://github.com/argilla-io/argilla)**  
  Open-source platform for data labeling, feedback collection, and iterative dataset improvement, especially strong for NLP and LLM workflows.

- **[Doccano](https://github.com/doccano/doccano)**  
  Open-source text annotation tool for sequence labeling, classification, and sequence-to-sequence tasks.

- **[Diffgram](https://github.com/diffgram/diffgram)**  
  Open-source training-data platform that combines annotation, dataset management, and workflow automation.

- **[Supervisely (Community / open components)](https://github.com/)**  
  Computer-vision platform with open-source elements for annotation and dataset handling (full enterprise features are commercial).

- **[Open-source active learning & selection libraries](https://github.com/)**  
  Research and production libraries for uncertainty sampling, diversity sampling, and embedding-based data selection.

### Additional Strong Open-Source Options
- Roboflow open tools and dataset conversion utilities.
- COCO, YOLO, and other format converters and validators.
- Embedding visualization tools (UMAP, t-SNE notebooks) combined with custom selection scripts.
- DVC + Git for dataset versioning and reproducibility.
- Self-hosted labeling backends that integrate with FiftyOne or Label Studio.
- Medical imaging annotation tools (e.g., for DICOM) built on open frameworks.

**Frameworks for building custom systems**: Use **FiftyOne** for exploration, embedding analysis, and curation; send selected samples to **CVAT** or **Label Studio** for annotation; apply **Cleanlab** or model predictions to find errors; version datasets with DVC or lakeFS; and close the loop with active-learning scripts. This combination delivers a powerful, fully open data-centric AI workflow that can run entirely on your own infrastructure.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- High-quality training data is critical for model performance. Open-source tools provide excellent control and cost advantages but require engineering effort for scaling, workforce management, and enterprise security features that commercial platforms often include out of the box.
- Always maintain clear data governance, labeling guidelines, and quality metrics regardless of the tooling chosen.

---
**Made for ML engineers, data-centric AI practitioners, and teams building better datasets.**
Let's make data curation more open, efficient, and model-aware.
