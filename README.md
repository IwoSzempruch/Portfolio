---

# Portfolio — Iwo Michał Szempruch
This Portfolio has a **Website version:** https://iwoszempruch.github.io/Portfolio/

Welcome! This repository is my personal portfolio focused on **research**, **laboratory work**, and **software projects for life sciences** (especially microbiology/bioinformatics).

---

## Featured Project: Bacterial Growth Curves Analyser (Web App)

**Live demo:** https://bacterial-growth-curves-analyser-pc0se7igi.vercel.app  
**Source code:** https://github.com/IwoSzempruch/Bacterial_Growth_Curves_Analyser  
**Example dataset (JSON assignment):** https://bacterial-growth-curves-analyser-pc0se7igi.vercel.app/examples/example-dataset.json

### What this app is for

In microbiology laboratories, growth curves are measured using different instruments, and **each instrument exports data in different file formats**. In addition, **the exact processing steps** needed to obtain meaningful results from growth curves can vary between labs.

This project aims to provide **laboratory staff without data-analysis expertise** and **students** with a tool for **fast, preliminary analysis** of growth-curve datasets from various input formats in a **unified workflow**, aligned with the **current consensus practices** for this type of data processing.

**Status:** in active development (prototype / demo).

### Planned improvements before a stable public release

- **Language consistency:** unify the UI language (some places currently mix Polish and English)
- **Layout consistency:** unify the overall layout and spacing
- **Plot styling improvements:** add plot appearance customization with the ability to select and import a preferred plot layout/style
- **Statistical overlays:** add standard deviations, confidence intervals, and other statistical summaries on plots
- **Bug fixing** and general stability improvements
- **Landing page tutorial:** add a short video tutorial on the landing page
- **More input formats:** extend support for additional growth-curve instrument export formats

### How to test the current demo (step-by-step)

1) Open the **Live demo** and click **Start workflow**  
2) In the **Setup** tab, step **“0. Import assignment”**  
   - import the example assignment JSON file:  
     https://bacterial-growth-curves-analyser-pc0se7igi.vercel.app/examples/example-dataset.json  
3) Scroll to the bottom of the Setup tab and click **NEXT**  
4) In **Raw Data**, click **SEND TO BLANK CORRECTION**  
5) At the bottom of **Blank Check**, click **APPLY BLANK CORRECTION**  
6) Scroll to the bottom of **Blank Check** and click **NEXT**  
7) At the top of **Curves Smoothing**, click **LOESS (ALL)**  
8) Click **Next: Parameters**

**Tech stack:** TypeScript, React, Vite

---

## Research Poster: MaoP protein and *E. coli* chromosome organization

This repository also contains a poster from a project I contributed to during my B.Sc. studies.

### My contribution

During my undergraduate studies, I **constructed 32 *E. coli* strains** using:
- bacteriophage **transduction**
- **molecular cloning**
- **homologous recombination**
- bacterial **transformation**

These strains contributed to investigating the function of the **MaoP protein** in the project.

**Poster file:** `Poster-Biology-and-Physics-of-Chromosomes...` (available in this repository)

---

## Contact

- GitHub: https://github.com/IwoSzempruch  
- LinkedIn: (link in my CV header)

If you are reviewing my application and would like a short guided walkthrough of the demo or codebase, feel free to reach out.
