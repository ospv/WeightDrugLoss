# WeightDrugLoss

This github page contains raw results generated in the context of the presentation to the German PV day on 17 September 2024 for a presentation entitled "Weight Loss Drugs - ​Independent Insights from Open Data & Open Source technology​" made by Lionel Van Holle for OpenSourcePV using FAERS data up to 24Q1. 

**Table of content of previous analyses:**
- [Disproportionality Analysis](#DPA)
- Time-to-onset Analysis:
  - [wegovy](#ttowegovy)
  - [zepbound](#ttozepbound)
  - [ozempic](#ttoozempic)
  - [mounjaro](#ttomounjaro)
- [Cluster Analysis](#Cluster)
- [Competitive Analysis](#competitive)

<a id="DPA"></a>
# Disproportionality Analysis    
The results of disproportionality analysis are [here](https://ospv.github.io/WeightDrugLoss/Disproportionality.html). A quantitative signal of disproportionate reporting was generated when IC025 was higher than 0. 

# Time-to-onset Analysis. 
Different time-to-onset signals were found using a minimal distance of 0.2 and a p-value lower than 0.01:

<a id="ttowegovy"></a>  
* Wegovy:

| TTO Signal | TTO Signal |
|------------|------------|
| ![Wegovy-vomiting](wegovy%20-%20vomiting.png) | ![Wegovy-pain-of-skin](wegovy%20-%20pain%20of%20skin.png) | 
| ![wegovy-injectionsitepain](wegovy%20-%20injection%20site%20pain.png) | ![wegovy-injectionsiteextravasation](wegovy%20-%20injection%20site%20extravasation.png) |
| ![wegovy-injectionsitebruising](wegovy%20-%20injection%20site%20bruising.png) | ![wegovy-headache](wegovy%20-%20headache.png) |
| ![wegovy-deviceleakage](wegovy%20-%20device%20leakage.png) | ![wegovy-dehydration](wegovy%20-%20dehydration.png) |

<a id="ttozepbound"></a>  
* Zepbound

| TTO Signal | TTO Signal |
|------------|------------|
| ![Zepbound-accidentalunderdose](zepbound%20-%20accidental%20underdose.png) | ![Zepbound-injectionsiteinjury](zepbound%20-%20injection%20site%20injury.png) | 
  
<a id="ttoozempic"></a>  
* Ozempic

| TTO Signal | TTO Signal |
|------------|------------|
| ![Ozempic-abortionspontaneous](ozempic%20-%20abortion%20spontaneous.png) | ![Ozempic-acutekidneyinjury](ozempic%20-%20acute%20kidney%20injury.png) | 
| ![Ozempic-asthenia](ozempic%20-%20asthenia.png) | ![Ozempic-constipation](ozempic%20-%20constipation.png) | 
| ![Ozempic-decreasedappetite](ozempic%20-%20decreased%20appetite.png) | ![Ozempic-dehydration](ozempic%20-%20dehydration.png) | 
| ![Ozempic-gastroenteritis](ozempic%20-%20gastroenteritis.png) | ![Ozempic-dehydration](ozempic%20-%20dehydration.png) | 
| ![Ozempic-hyperhidrosis](ozempic%20-%20hyperhidrosis.png) | ![Ozempic-hypertension](ozempic%20-%20hypertension.png) | 
| ![Ozempic-hypokalaemia](ozempic%20-%20hypokalaemia.png) | ![Ozempic-ketoacidosis](ozempic%20-%20ketoacidosis.png) | 
| ![Ozempic-swelling](ozempic%20-%20swelling.png) | ![Ozempic-therapychange](ozempic%20-%20therapy%20change.png) | 


<a id="ttomounjaro"></a>  
* Mounjaro

| TTO Signal | TTO Signal |
|------------|------------|
| ![mounjaro-asthenia](mounjaro%20-%20asthenia.png) | ![mounjaro-bonepain](mounjaro%20-%20bone%20pain.png) | 
| ![mounjaro-constipation](mounjaro%20-%20constipation.png) | ![mounjaro-decreasedappetite](mounjaro%20-%20decreased%20appetite.png) | 
| ![mounjaro-dehydration](mounjaro%20-%20dehydration.png) | ![mounjaro-diarrhoea](mounjaro%20-%20diarrhoea.png) | 
| ![mounjaro-fatigue](mounjaro%20-%20fatigue.png) | ![mounjaro-feedingdisorder](mounjaro%20-%20feeding%20disorder.png) | 
| ![mounjaro-gastrooesophagealrefluxdisease](mounjaro%20-%20gastrooesophageal%20reflux%20disease.png) | ![mounjaro-headache](mounjaro%20-%20headache.png) | 
| ![mounjaro-illness](mounjaro%20-%20illness.png) | ![mounjaro-influenza](mounjaro%20-%20influenza.png) | 
| ![mounjaro-injectionsitepruritus](mounjaro%20-%20injection%20site%20pruritus.png) | ![mounjaro-lymphadenopathy](mounjaro%20-%20lymphadenopathy.png) | 
| ![mounjaro-myalgia](mounjaro%20-%20myalgia.png) | ![mounjaro-nausea](mounjaro%20-%20nausea.png) | 
| ![mounjaro-neckpain](mounjaro%20-%20neck%20pain.png) | ![mounjaro-pain](mounjaro%20-%20pain.png) | 
| ![mounjaro-productdoseomissionissue](mounjaro%20-%20product%20dose%20omission%20issue.png) | ![mounjaro-suicidalideation](mounjaro%20-%20suicidal%20ideation.png) | 

<a id="Cluster"></a>  
# Cluster Analysis

Cluster analysis ran over all PTs reported for all products. 
By default, time window was one year and top 5 of the most significant signals of excess of reports within the last time period of one year (01APR2023-31MAR2024)
are listed here. 

| Product | Event | Report |
|---------|-------|--------|
| Ozempic | Suicidal ideation |  [Link](https://ospv.github.io/WeightDrugLoss/ozempic-cluster-suicidal_ideation.html) |
| Ozempic | Completed suicide |  [Link](https://ospv.github.io/WeightDrugLoss/ozempic-cluster-completed_suicide.html) |
| Ozempic | Impaired gastric emptying |  [Link](https://ospv.github.io/WeightDrugLoss/ozempic-cluster-impaired_gastric_emptying.html) |
| Ozempic | Brain fog |  [Link](https://ospv.github.io/WeightDrugLoss/ozempic-cluster-brain_fog.html) |
| Ozempic | Allodynia |  [Link](https://ospv.github.io/WeightDrugLoss/ozempic-cluster-allodynia.html) |
| Mounjaro | Accidental overdose |  [Link](https://ospv.github.io/WeightDrugLoss/mounjaro-cluster-accidental_overdose.html) |
| Mounjaro | Brain fog |  [Link](https://ospv.github.io/WeightDrugLoss/mounjaro-cluster-brain_fog.html) |
| Mounjaro | Impaired gastric emptying |  [Link](https://ospv.github.io/WeightDrugLoss/mounjaro-cluster-impaired_gastric_emptying.html) |
| Mounjaro | Alopecia |  [Link](https://ospv.github.io/WeightDrugLoss/mounjaro-cluster-alopecia.html) |
| Mounjaro | Overdose |  [Link](https://ospv.github.io/WeightDrugLoss/mounjaro-cluster-overdose.html) |

<a id="competitive"></a>  
# Safety Competitive Intelligence 
The results of the competitive analysis are here for: 
* [Ozempic vs Mounjaro](https://ospv.github.io/WeightDrugLoss/24Q1%20-%20Targetedcompetitive%20-%20ozempic%20vs%20mounjaro.html)

