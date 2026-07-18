<!-- profile README for github.com/geokousis  →  repo must be named  geokousis/geokousis -->

<h1 align="center">Hi, I'm Georgios 👋</h1>
<p align="center">
  <em>Bioinformatics @ University of Crete · building stuff that no one will use</em>
</p>

<p align="center">
  <!-- these are dynamic images, they update themselves -->
  <img src="https://github-readme-stats.vercel.app/api?username=geokousis&show_icons=true&hide_border=true&count_private=true" height="150" alt="stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=geokousis&layout=compact&hide_border=true&langs_count=8" height="150" alt="top languages" />
</p>

---

### 🧭 What I work on

```mermaid
mindmap
  root((geokousis))
    Genomics
      SoloVar
      Good-Wines
      DRAGMAP-GATK
      ddraptor
    Single-cell / Imaging
      scRNA-seq-Analysis
      TNT-seq
      Radiomics
    Dev tools
      NaeNae
      Sanger-Analysis-Tool
      PrimerToolKit
    Web / Lab infra
      evoleaf
      evocoffee
      evolab-site
```

---

### 🧬 Selected projects by domain

<details open>
<summary><b>Genomics & Variant Calling</b></summary>

| Project | What it does | Lang |
|---|---|---|
| [SoloVar](https://github.com/geokousis/SoloVar) | Tumor-only variant calling & annotation | Python |
| [ddraptor](https://github.com/geokousis/ddraptor) | Optimal ddRAD enzyme-pair selection via in-silico digests | Rust |
| [Good-Wines](https://github.com/geokousis/Good-Wines) | SNP identification in *Vitis vinifera* | Python |

</details>

<details>
<summary><b>Single-cell, Imaging & Analysis</b></summary>

| Project | What it does | Lang |
|---|---|---|
| [scRNA-seq-Analysis](https://github.com/geokousis/scRNA-seq-Analysis) | Single-cell RNA-seq workflows | — |
| [Radiomics](https://github.com/geokousis/Radiomics) | Radiomic feature analysis | — |
| [BCProjects](https://github.com/geokousis/BCProjects) | Academic bioinformatics projects | Jupyter |

</details>

<details>
<summary><b>Developer Tools</b></summary>

| Project | What it does | Lang |
|---|---|---|
| [NaeNae](https://github.com/geokousis/NaeNae) | Wrap long commands, match regex, ping Discord | Rust |
| [PrimerToolKit](https://github.com/geokousis/PrimerToolKit) | Primer design toolkit | R |
| [evoleaf](https://github.com/geokousis/evoleaf) | Self-hosted Overleaf CE with extras | JS |

</details>

---

### 🔬 How a typical analysis flows

```mermaid
flowchart LR
    A[Raw reads] --> B[QC & trim]
    B --> C[DRAGMAP / align]
    C --> D[GATK variant calling]
    D --> E[Annotation]
    E --> F[Figures & report]
    style A fill:#2d333b,stroke:#539bf5,color:#fff
    style F fill:#2d333b,stroke:#57ab5a,color:#fff
```

---

<p align="center">
  🌐 <a href="https://geokousis.github.io">geokousis.github.io</a> ·
  🎓 University of Crete
</p>
