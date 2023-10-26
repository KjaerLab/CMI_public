---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: CMI data and projects
---
&nbsp;
### **Micro CT dataset**



This is the official site for updates on the microCT dataset published in Nature Scientific Data by 
[Cluster for Molecular Imaging](https://www.rigshospitalet.dk/afdelinger-og-klinikker/diagnostisk/klinisk-fysiologi-og-nuklearmedicin/forskning/Sider/cluster-for-molecular-imaging.aspx).

**The most recent version of the dataset can be accessed by filling out the form [here]().**

The dataset consists of 452 individual CT scans from 223 unique mice with subcutaneous tumors. The dataset is collected from 10 different studies and all CT scans have been labelled by 3 annotators. The data is saved in NIfTI format and with following structure
```
Root
|-- Study 1
|-- Study 2
    |-- M01_M02_8d
        |-- M01_8d
        |-- M02_8d
            |-- Annotator_A_M02_8d.nii.gz         
            |-- Annotator_B_M02_8d.nii.gz         
            |-- Annotator_C_M02_8d.nii.gz
            |-- CT_M02_8d.nii.gz
|-- Study 3
...
```

#### **Changelog**:
<!-- **20-01-2023:** First version of dataset published together with paper. [Link](https://erda.ku.dk/archives/ff0a03a995ea2024d86090b65e341daf/published-archive.html) -->