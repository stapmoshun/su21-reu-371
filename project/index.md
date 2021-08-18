---
date: 2021-06-16
title: "Project: Detecting Multiple Sclerosis Symptoms using AI" 
linkTitle: "Multiple Sclerosis and AI"
tags: ["project", "reu", "health", "ai"]
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

## 2. Figures

![Figure 1](https://github.com/cybertraining-dsc/su21-reu-371/raw/main/project/images/MRI-subtypes.jpg)

**Figure 1:** The figure shows the MRI-based subtypes. The color shades range from blue to pink, representing the probability of abnormality mild to severe, respectively. (Eshaghi)

![Figure 2](https://github.com/cybertraining-dsc/su21-reu-371/raw/main/project/images/EDSS-progression.jpg)

**Figure 2:** This figure compares the training set and validation set of EDSS progression.

## 3. Datasets

MRI brain scans of 6,322 MS patients. look if you can find figures descrbing the data.

## 4. Benchmark

Your project must include a benchmark. The easiest is to use cloudmesh-common.

## 5. Conclusion

A vital barrier in distinguishing subtypes in Multiple sclerosis is to stitch observations together from cross-sectional or longitudinal studies. Grouping individuals based wholly on their MRI scan is ineffective because patients belonging to the same subgroup could show ranging abnormalities as the disease progresses and would appear different. SuStaIn, Subtype and Staging Inference, a newly developed unsupervised machine learning algorithm aids in uncovering data-driven disease subtypes that have distinct temporal progression patterns. "The ability to disentangle temporal and phenotypic heterogeneity makes SuStain different from other unsupervised learning or clustering algorithms" (Eshaghi). SuStaIn identifies subtypes given the data, defined by a particular pattern of variation in a set of features, such as MRI abnormalities. Once the SuStain subtypes and their MRI trajectories are adequately identified, the disease model can conclude how approximately a patient, whose MRI is unseen, belongs to each of the three subtypes and stages.

A total of 9,390 patients participated in this research study. Six thousand three hundred twenty-two patients were utilized in training, and 3,068 patients were used for the validation dataset. Patient characteristics such as sex, age, disease duration, and expanded disability status scale (EDSS) were similar between the training and validation dataset. There were 18 MRI features measured, 13 of those differed dramatically from those between the MS training dataset and control group and were maintained in the SustaIn model. Three subtypes, with very distinct patterns, were identified in the training dataset and validated in the validation dataset. The early abnormalities noticed by SuStain helped define the three subtypes: cortex-led, normal-appearing white matter-led, and lesion-led.

There was a statistically significant difference in the rate of the disease progression between the subtypes in the training dataset and validation datasets. The lesion-led subtype held a 30% higher risk of developing 24-week confirmed disability progression (CDP) than the cortex-led subtype in the training dataset. The lesion-led validation dataset had a 32% higher risk of confirmed disability progression than the cortex-led subtype. No other differences in the advancement of disability between subtypes were noted. When SuStaIn was applied to the training and validation dataset, it was pointed out that there were differences in the risk of disability progression between SuStaIn stages.

Each MRI-based subtype had a different response to treatment, comparing those on treatment and those on placebo. The lesion-led subtype showed a remarkable response to the treatment. Patients on the lesion-led active treatment subtype showed a significantly slower worsening of EDSS than those on the placebo. No differences in the rate of EDSS were observed in those on the placebo compared to active treatment in the NAWM-led and cortex-led subtypes.

When SuStain was applied to a large set of Multiple sclerosis scans, it identified three subtypes. Researchers found out the patient's baseline subtype and stage were associated with an increased risk of disease progression. Combining clinical information with the MRI-based three subtypes increased the predictive accuracy of just using the MRI scan information alone. The patterns of MRI abnormality in these subtypes provide perspicacity into disease mechanisms, and, alongside clinical phenotypes, they may aid the stratification of patients for future studies. 

## 6. Acknowledgments

The author likes to thank Gregor von Laszewski, Yohn Jairo, and Carlos Theran.

## 7. References

[^1]: Eshaghi, A., Young, A. L., Wijeratne, P. A., Prados, F., Arnold, D. L., Narayanan, S., Guttmann, C. R. G., Barkhof, F., Alexander, D. C., Thompson, A. J., Chard, D., &amp; Ciccarelli, O. (2021, April 6). Identifying multiple sclerosis subtypes using unsupervised machine learning and MRI data. Nature News.
      <https://www.nature.com/articles/s41467-021-22265-2>
 
[^2]: Mayo Foundation for Medical Education and Research. (2020, June 12). Multiple sclerosis. Mayo Clinic.
      <https://www.mayoclinic.org/diseases-conditions/multiple-sclerosis/symptoms-causes/syc-20350269>

[^3]: MediLexicon International. (n.d.). Multiple sclerosis (MS): Types, symptoms, and causes. Medical News Today.
      <https://www.medicalnewstoday.com/articles/37556>

[^4]: Skylar Kenney, A. E. (2021, April 12). Artificial Intelligence Identifies Novel Multiple Sclerosis Subtypes. Pharmacy Times.
      <https://www.pharmacytimes.com/view/artificial-intelligence-identifies-novel-multiple-sclerosis-subtypes>
 
[^5]: Ucl. (2021, April 8). New multiple sclerosis subtypes identified using artificial intelligence. UCL News.
      <https://www.ucl.ac.uk/news/2021/apr/new-multiple-sclerosis-subtypes-identified-using-artificial-intelligence>

[^6]: What Is MS? National Multiple Sclerosis Society. (n.d.).
      <https://www.nationalmssociety.org/What-is-MS>
