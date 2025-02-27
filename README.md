# Bioinfo Class I Notes & Study Plan
Zihan Xu  
2025/2/27  
School of Life Sciences, Tsinghua University  
Teacher: Lu Zhi
---

## 0. Course Overview
### Schedule  
 * Programming Skills  
   Weeks 1-4: Linux  
   Weeks 5-16: R  
   Weeks 11-16: Python (optional)  
 * Basic & NGS Data Analyses   
   Weeks 2-12  
   Machine Learning & AI  
 * Weeks 13-16: basics and model introduction  
 
### Course score composition  
 * **20%** classroom interaction questions.  
 * **80%** of in-class and after-class assignments (7-9 times) (Suggestions and feedback: +5-10%; The total score after each extra point is not more than 10 points)  
   *Issues in gitbook and docker/singularity*  
   *Recommended resources*  
 * Experience sharing and Presentation once (3 marks for teachers and teaching assistants + 7 marks for students' mutual evaluation)  
 * Extra points  
 *Assignments are graded according to the overall score.*  
 
### Contact  
 * Teacher: [Lu Zhi](zhilu@tsinghua.edu.cn)  
 * TA: [Bai Yilan](baiyl22@mails.tsinghua.edu.cn)  
       [Gao Letian](glt23@mails.tsinghua.edu.cn)  
      
---

## 1. Introduction  
### 1.1 4 steps of Bioinformatics  
#### Question: Biological/Medical Knowledge 
  * Science  
  * Technology  
  * Philosophy  
#### Information: Biological/Medical data   
  * NGS (Next Generation Sequencing):  
    DNA-seq  
    RNA-seq  
    Epigenetics: DNAase/Methylation/Histone modifications  
    Interaction  Protein-DNA:ChIP-seq / Protein-RNA:CLIP-seq / DNA-RNA:Grid-seq   
  * Big and HD data: persons * cells * omics  
  * Metagenomics  
#### Analysis: Data Clean & Feature Extraction   
    NGS Data Analysis – Sequencing Method + Bioinformatics Tool  
    
| **Variation** | **Sequencing Methods** | **Bioinformatics Tools** |
|---|---|---|
| Abundance | RNA-seq | DEGseq, EdgeR, Cufflinks |
| Splicing | RNA-seq | rMATs, Tophat/Cufflinks |
| Editing | RNA-seq | GIREMI, REDItools, SPRINT |
| APA (Alternative Polyadenylation) | RNA-seq / PAT-seq | DaPars, APAtrap |
| Translation | Ribo-seq | RiboWave, RiboTaper, ORFscore |
| Degradation | Degradome-Seq (PARE-seq), cfRNA-seq | sPARTA, cfPeak |
| Modification | m6A-seq, MeRIP-seq, miCLIP | m6aViewer, MeRIP-PF |
| Structure | icSHAPE, SHAPE-map, DMS-seq | RNAstructure, RNAfold, RME |
| RNA-protein interaction | HITS-CLIP, PAR-CLIP, iCLIP, eCLIP | Piranha, PARalyzer, CIMS; POSTAR/CLIPdb |  

#### Modeling: Probabilistic Model& Computational Algorithm  

  
### 1.2 Two types of Bioinformatics studies:  
 **Data Problems**  
- Representation (graphics)   
- Storage and retrieval (databases)   
- Analysis method (statistics, artificial intelligence, optimization, etc.)

 **Biology Problems**   
- Interpreting biological sequences  
- Predicting structure or function  
- Mining clinical (i.e. cancer) data/information  
  
### 1.3 Hypothesis Driven VS. Data Driven   
  **Hypothesis Driven:** QIAM  
  **Data Driven:** IAMQ  
    
---

## 2.Algorithm and Model  
### 2.1 What Is an Algorithm?  
- **Definition**: An algorithm is a finite set of clear, step-by-step instructions used to solve a specific problem or accomplish a particular task.    
- **Examples**:  
  - **Sorting**: e.g., Bubble Sort, Quick Sort   
  - **Searching**: e.g., Linear Search, Binary Search  

### 2.2. What Is a Model?  
- **Definition**: A model is a simplified or abstract representation of a real-world process, phenomenon, or system. Models are typically used to analyze, predict, or explain behaviors and outcomes. 
- **Examples**  
  - **Mathematical/Statistical Models**: e.g., Linear Regression, Logistic Regression   
  - **Machine Learning Models**: e.g., Decision Trees, Neural Networks 
 
### 2.3 Key Differences Between Algorithms and Models 
1. **Focus**   
   - **Algorithms**: Emphasize the procedure or sequence of steps to solve a problem.   
   - **Models**: Emphasize the abstraction or representation of real-world phenomena.
2. **Dependency on Data**   
   - **Algorithms**: May or may not rely heavily on external data; they mainly define how to process given inputs.  
   - **Models**: Often require training or fitting to observed data to make predictions or analyses.  
3. **Purpose**   
   - **Algorithms**: Provide a clear, systematic method to achieve a goal (e.g., finding the shortest path).   
   - **Models**: Provide insight into how a system works or behaves under certain conditions.  

---

## 3. Study Plan  

### 3.1 Goals  
1. Understand the fundamental concepts and scope of bioinformatics. 
2. Learn how to use common bioinformatics databases and tools. 
3. Develop basic skills for data analysis. 
4. Complete a small project by the end of the semester. 

### 3.2 Learning Contents  
## Weeks 1–4: Linux Fundamentals  
- **Core Commands**: file/folder operations, permissions, process management    
- **Text Processing**  
- **Shell Scripting**: automate data processing, create basic pipelines    

## Weeks 2–12: Basic & NGS Data Analysis  
- **NGS Overview**: key workflows, file formats   
- **Pipeline Steps**: data import, quality control, alignment, visualization    
- **Project**: download a public dataset, perform differential expression analysis, and present results  

## Weeks 5–16: R Programming & Analysis  
- **Weeks 5–8**: R basics (data types, cleaning, plotting with `ggplot2`)    
- **Weeks 9–12**: Bioconductor packages (e.g., DESeq2, edgeR)   
- **Weeks 13–16**: Advanced R topics   
*Use R Markdown to document my workflow, track code via GitHub*  

## Weeks 11–16: Python  
- **Python Essentials**: data structures  
- **Bioinformatics Tools**: for machine learning / NGS  
- **Comparison**: replicate a subset of your R analysis in Python for cross-verification  

## Weeks 13–16: Machine Learning & AI  
- **Basics**   
- **Practical**: use R or Python to build simple classification/regression models    
- **Mini-Project**  

---
 
Please visit my [GitHub Pages](https://ZihanXu4.github.io/) for more information and future updates!  

# ZihanXu4.github.io
