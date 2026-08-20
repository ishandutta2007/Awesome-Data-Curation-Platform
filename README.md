# Awesome-Data-Curation-Platform

## Top Data Curation Platforms Ecosystem

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

| Platform | Description | Pricing (Starting Tier) | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Lightly](https://www.lightly.ai/)** | Embedding-based data curation platform specializing in selecting informative samples for computer vision and reducing labeling redundancy. | Professional tier starts at ~$350 - $440/month; Enterprise custom quotes. | **Free Plan**: Up to 3 datasets and 1,000 samples per dataset. Also offers a 14-day free trial for LightlyStudio. |
| **[Activeloop](https://www.activeloop.ai/)** | Dataset management and streaming platform (Deep Lake) focused on storage, versioning, and loading multimodal datasets. | Paid tiers start at $40/month (or $99/month for Pro); $15 starter credit on pay-as-you-go. | **Free Plan**: Core features for individual developers; Academic/research tier includes up to 1TB storage & 100,000 queries/month. |
| **[DagsHub](https://dagshub.com/)** | Data science collaboration platform with dataset versioning, experiment tracking, and DVC/Git-based workflows. | Team plan starts at $99/user/month (annual billing) or $119/user/month (monthly billing). | **Free Plan (Individual)**: 20GB storage, unlimited public repos, unlimited private repos (non-commercial), 2 collaborators on private repos, and up to 100 tracked private experiments. |
| **[Snorkel AI](https://snorkel.ai/)** | Programmatic labeling and data-centric AI platform for weak supervision, labeling functions, and dataset curation. | Annual enterprise contracts start at ~$50,000 - $60,000/year (custom scoped). | **Free Trial / Access**: No self-serve free plan. Free pilot/evaluation access granted only via sales engagement and demo request. |
| **[Encord](https://encord.com/)** | Enterprise multimodal data annotation, curation (Encord Active), and model evaluation platform. | Starter plan custom-quoted per organization (Starter/Team/Enterprise tiers). | **Free Trial / Access**: Free evaluation access upon demo request and pilot setup (no open self-serve free tier; Encord Active package is open source). |
| **[Dataloop](https://dataloop.ai/)** | End-to-end data operations and annotation platform combining dataset management, pipelines, and serverless automation. | Custom tier-based and consumption pricing (managed datapoints/UI hours). | **Free Trial / Access**: Free onboarding access / sales-led pilot upon demo request; system-level cap of 25M items per dataset. |
| **[Labelbox](https://labelbox.com/)** | Cloud-native training-data platform with model-assisted labeling, catalog search, and data quality workflows. | Starter plan starts at $0.10 per Labelbox Unit (LBU) consumed; Enterprise custom quotes. | **Free Plan**: 500 Labelbox Units (LBUs)/month, supporting up to 30 users, 50 projects, and 10M total data rows. |
| **[Kili Technology](https://kili-technology.com/)** | Annotation and data quality platform supporting documents, NLP, and computer vision with EU data residency. | Grow and Enterprise plans with custom volume-based quotes. | **Free Plan**: 1 seat, up to 100 text/doc/image assets and 5 video/satellite assets. Also offers a 14-day (2-week) full-feature free evaluation. |
| **[Scale AI](https://scale.com/)** | Full-stack data engine providing annotation services, dataset curation (Nucleus), and model evaluation. | Self-serve annotation tasks start at ~$0.05 per labeling unit after free credits; custom enterprise contracts. | **Free Plan**: Nucleus Free Tier for dataset exploration; 200 free labeling units/month for self-serve annotation accounts. |
| **[SuperAnnotate](https://www.superannotate.com/)** | Annotation and curation platform with automated QA, workflow orchestration, and multimodal editors. | Pro plan custom-quoted per seat/project requirements. | **Free Plan / Trial**: Free Starter tier with up to 1,000 compute hours via Orchestrate; 14-day free trial with full Pro features. |



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
