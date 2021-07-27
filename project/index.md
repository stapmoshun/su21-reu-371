---
date: 2021-06-16
title: "Project: Detecting Multiple Sclerosis Symptoms using AI" 
linkTitle: "Multiple Sclerosis and AI"
tags: ["project", "reu", "multiple sclerosis", "disease", "AI", "machine learning"]
description: "This work implements machine learning algorithim apply in Multiple Sclerosis symptoms and provides treatment options available"
Author: "Raeven Hatcher"
github_url: https://github.com/cybertraining-dsc/su21-reu-371/edit/main/project/index.md
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"
---

[![Check Report](https://github.com/cybertraining-dsc/su21-reu-371/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-371/actions)
[![Status](https://github.com/cybertraining-dsc/su21-reu-371/workflows/Status/badge.svg)](https://github.com/cybertraining-dsc/su21-reu-371/actions)
Status: draft, Type: Project


Raeven Hatcher, [su21-reu-371](https://github.com/cybertraining-dsc/su21-reu-371), [Edit](https://github.com/cybertraining-dsc/su21-reu-371/blob/main/project/index.md)

{{% pageinfo %}}

## Abstract

Multiple sclerosis (M.S.) is a chronic central nervous system disease that potentially affects the brain, spinal cord, and optic nerves in the eyes. People that suffer from M.S had their immune system attacks the myelin (protective sheath) that covers nerve fibers, resulting in communication problems between the brain and the body. The cause of M.S. is unknown; however, researchers believe that genetic and environmental factors play a role in those affected. Symptoms differ significantly from person to person due to varying nerves involved. The most common symptoms include tremors, numbness or weakness in limbs, vision loss, blurry vision, double vision, slurred speech, fatigue, dizziness, involuntary movement, and muscle paralysis. There is currently no cure for Multiple sclerosis and treatment focuses on slowing the progression of the disease and managing symptoms.  

There is no proven way to predict how an individual with M.S will progress certainly. However, researchers established four phenotypes that will assist in identifying those who are more inclined to have disease progression and help aid in more effective treatment targeting. In this experiment, Artificial Intelligence (AI) will be applied by ascertaining what causes these different phenotypes and which phenotype is at most risk for disease progression using a Magnetic Resonance Scan.  

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** tensorflow, example. 

## 1. Introduction

MS or Multiple sclerosis is a potentially disabling autoimmune disease that can damage the brain, spinal cord, and optic nerves located in the eyes. It is the most common progressive neurological disability that affects adolescents. The immune system attacks the central nervous system in this disease, specifically myelin (sheth that covers and protects nerve fibers), oligodendrocytes (myelin-producing cells), and the nerve fibers located under myelin. Myelin enables nerves to send and receive electrical signals swiftly and effectively. The myelin sheath becomes scarred from being attacked. These attacks make the myelin sheath inflamed in little patches, observable on an MRI scan. These little inflamed patches potentially disrupt messages moving along the nerves, which ultimately lead to the symptoms of Multiple sclerosis. If these attacks happen frequently, permanent damage can occur to the involved nerve.  
Because Multiple sclerosis affects the central nervous system, which control all of the actions carried out in the body, symptoms can affect any part of the body and vary. The most common symptoms of this progressive disease include muscle weakness, pins and needle sensation, electrical shock sensation, loss of bladder control, muscle spasms, tremors, double or blurred vision, partial or total vision loss, to name a few. Researchers are not sure what causes Multiple sclerosis but believe those between the ages of 20 and 40, women, smoke, are exposed to certain infections, have a vitamin D and B12 deficiency, and related to someone affected by this disease are more susceptible.

It can be difficult to diagnose MS due to the symptoms usually being vague or very similar to other conditions. There is no single test to diagnose it positively. However, doctors can choose a neurological examination, MRI scan, evoked potential test, lumbar puncture, or a blood test to diagnose a patient properly. Currently, clinical practices divide MS into four phenotypes: clinically isolated syndrome (CIS), relapsing-remitting MS (RRMS), primary-progressive MS (PPMS), and secondary progressive MS (SPMS). Two factors define these phenotypes; disease activity (evidenced by relapses or new activity on MRI scan) and progression of disability. Phenotypes are routinely used in clinical trials to choose patients and conduct treatment plans. 

New technologies, such as artificial intelligence and machine learning, help assess multidimensional data to recognize groups with similar features. When implemented in apparent abnormalities on MRI scans, these new technologies have assured promising results in classifying patients who share similar pathobiological mechanisms rather than the typical clinical features. 

Researchers at UCL work with the Artificial intelligence (AI) tool SuStain (Subtype and Stage Inference) to ask whether AI can find Multiple sclerosis subtypes that follow a particular pattern on brain images? The results uncovered three data-driven MS subtypes defined by pathological abnormalities seen on brain images (Skylar).  The three data-driven MS subtypes are cortex-led, normal-appearing WM-led, Lesion-led. Cortex-led MS is characterized by early tissue shrinkage (atrophy) in the outer layer of the brain. Normal-appearing WM-led is identified by irregular diffused tissue located in the middle of the brain. Lastly, a lesion-led subtype is characterized by early extension accumulation of brain damage areas that lead to severe atrophy in numerous brain regions. All three of these subtypes correlate to the earliest abnormalities observed on an MRI scan within each pattern.

In this experiment, researchers utilized the SuStain tool to capture MRI scans of 6,332 patients. The unsupervised SuStain taught itself and identified those three patterns that were previously undiscovered. 

## 3. Using Images
![projectpic2](https://user-images.githubusercontent.com/85815818/126948339-7723b810-83e4-463b-a2b0-bf417fac4458.jpg)
The above image shows the MRI-based subtypes. The color shades range from blue to pink, representing the probability of abnormality mild to severe, respectively. (Eshaghi) 






   
## 4. Datasets

MRI brain scans of 6,322 MS patients. look if you can find figures descrbing the data.

CANT FIND

## 5. Benchmark

Your project must include a benchmark. The easiest is to use cloudmesh-common [^2]
- [ ] define method that will be used to study the performance of the proposed method 
 
## 6. Conclusion

A convincing but not fake conclusion should summarize what the conclusion of the project is.

## 7. Acknowledgments

-Yohn Jairo
-Carlos Theran

## 8. References

 [^1]: Eshaghi, A., Young, A. L., Wijeratne, P. A., Prados, F., Arnold, D. L., Narayanan, S., Guttmann, C. R. G., Barkhof, F., Alexander, D. C., Thompson, A. J., Chard, D., &amp; Ciccarelli, O. (2021, April 6). Identifying multiple sclerosis subtypes using unsupervised machine learning and MRI data. Nature News. https://www.nature.com/articles/s41467-021-22265-2. 
 [^2]: Mayo Foundation for Medical Education and Research. (2020, June 12). Multiple sclerosis. Mayo Clinic. https://www.mayoclinic.org/diseases-conditions/multiple-sclerosis/symptoms-causes/syc-20350269. 
 [^3]: MediLexicon International. (n.d.). Multiple sclerosis (MS): Types, symptoms, and causes. Medical News Today. https://www.medicalnewstoday.com/articles/37556. 
 [^4]: Skylar Kenney, A. E. (2021, April 12). Artificial Intelligence Identifies Novel Multiple Sclerosis Subtypes. Pharmacy Times. https://www.pharmacytimes.com/view/artificial-intelligence-identifies-novel-multiple-sclerosis-subtypes. 
 [^5]: Ucl. (2021, April 8). New multiple sclerosis subtypes identified using artificial intelligence. UCL News. https://www.ucl.ac.uk/news/2021/apr/new-multiple-sclerosis-subtypes-identified-using-artificial-intelligence. 
What Is MS? National Multiple Sclerosis Society. (n.d.). https://www.nationalmssociety.org/What-is-MS. 
