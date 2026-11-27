I am a machine learning engineer with a PhD in electronics engineering from Yıldız Technical University. Since 2020
most of my work has been medical AI built with pathologists and clinicians, and I usually build the software around
the model as well. Most of it lives in private repositories of the teams I work with, so here is a short summary.

### Public project

**Ovarian cancer report agent** ([ovarian-agent-contract](https://github.com/hamza3e/ovarian-agent-contract), Nov 2026,
in progress). A pathology-report agent on public TCGA-OV reports. A local open-weight model extracts the findings, code
checks each evidence quote against the report, and a LangGraph step sends a case for review when the report and the
registry disagree. The [study guide](https://hamza3e.github.io/ovarian-agent-contract/study-guide.html) is the clinical
and ML background I worked through, step by step, while building it.

### Medical AI (private repositories)

**Bladder cancer** (MedTech Pioneers in Innovation, 2026). The goal is grading support from hospital data with
post-surgery follow-up. As a first step on TCGA-BLCA, I reviewed recent pathology AI, compared pathology foundation
models, chose histological and molecular subtyping after studying the data, and built the pipeline: tissue masking,
patching, foundation-model features, and MIL and simpler models trained and compared on them. I now lead the team
extending it with new cohorts and clinical variables.

**Path2Peer** (MedTech Pioneers in Innovation, 2026). A case-discussion platform for pathologists led by Dr Mahmut
Akgül, in development. Several LLMs split consented case discussions into cases, and I built the tools to check them:
one to correct the grouping (case, non-case and uncertain labels, a review queue, an audited edit history) and one in
which pathologists approved, flagged or corrected each extracted case. I also started a pipeline that suggests likely
immunohistochemistry stains for a new case, and am building the platform's mobile and web apps with the team.

**TNTdetect.AI** ([*Cancers* 2022](https://doi.org/10.3390/cancers14194958), co-first author). Detection and counting
of tunnelling nanotubes, thin membrane channels between cancer cells, in microscopy images, with U-Net segmentation. I
trained Dr Emil Lou's cancer research team at the University of Minnesota on the labelling tool and built the counting
pipeline, with collaborators at Stanford and MD Anderson.

**Earlier.** PhD on video-based fall detection for older people: pose-estimation output turned into an image
representation of the skeleton joints and classified with ShuffleNet V2 plus a deformable layer, tested on four public
datasets ([*Image Analysis and Stereology* 2024](https://doi.org/10.5566/ias.3087)). M.Sc. on RF heating in 3 T MRI,
with in-vivo sheep experiments and organ-by-organ MR segmentation for simulation (*eMagRes* 2020).

### Software and hardware

At Codebody I work on the web, backend and mobile app of a clinical physiotherapy platform. At Elaves I brought up the
custom ESP32-S3 board of an interactive toy and took over its web, mobile and backend code (Next.js, NestJS,
PostgreSQL, MQTT).

[LinkedIn](https://www.linkedin.com/in/hamzaerguder/) · [Research profile](https://impact.yildiz.edu.tr/researchers/hamza-erguder-27067)
