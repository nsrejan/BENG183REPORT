# The future of precision medicine through cancer diagnostics
By - Neel Srejan (A12973643)

## Precision medicine through cancer:

Precision medicine is the future. Precision medicine aims to individualize treatment based on one’s medical history through their phenotypic and genotypic makeup. A life changing area of precision medicine is in the field of cancer. Over the course of the last century, cancer diagnostics have made many milestone discoveries in the hope of curing different cancers. Presently, the next generation sequencing technologies coupled with new discoveries of biomarkers, are slowly showing the emerging patterns of how cancer progresses(1). But, in order to celebrate these biomarkers, they first need to be able to show significant correlation between early detection and saving lives. Lung cancer has seen the benefits of biomarkers in increasing the early detection rate from 30% to 60%, and a reduced mortality rate of about 20%(2). As of now, the diagnosis, using tissue biopsies, radiology, and endoscopy are expensive and invasive, while also falling short of accurately measuring the tumor heterogeneity2. For all of these reasons, we look at liquid biopsies as a new method to use for the biomarkers in order to increase early detection capability, decrease cost, monitor patient cancer progression, and provide treatment in a noninvasive manner.

## The need for liquid biopsy:

Currently, to detect cancer, one must undergo a tissue biopsy, to screen for evidence of tumors in a certain area of the body. However, tumors are very diverse and a biopsy of one area does not accurately reflect the true molecular profile of the tumor as they are very heterogeneous. The only way to get a broad scope of the tumor is to sample various locations of the tumor(3). In cases such as lung cancer, one tissue biopsy let alone multiple tissue biopsies itself is quite risky for the issues such as, bleeding, nerve injury, or spreading the disease(3). Liquid biopsies aim to alleviate all these issues by taking approximately 10 ml sample of blood, saliva, or urine to look for signs of cancer. We search for cell free DNA (cfDNA) in the plasma of released apoptotic and necrotic tumor cells(4). These cfDNA can be sequenced and analyzed to create a molecular profile of the patient and track mutations at various times in a patient’s life. Specifically, in the scope of cancer, the tumor’s progression, before and after the treatment can be charted.


![Image 1](https://github.com/nsrejan/BENG183REPORT/raw/master/Fig1BENG.png)
#### Fig 1. A solid biopsy of 4 locations is needed to profile and treat a patient vs a liquid biopsy that is away from the site of the tumor that can diagnose the patient with minimal to no harm to the infected organs. 


## Biomarkers:

### Circulating tumor cell:

In the cfDNA we look to isolate circulating tumor cells (CTC’s). CTC is a tumor cell that is in the bloodstream, and are the causes of blood-borne metastasis(5). The presence of CTC in the plasma of a patient is indicative of early detection of metastasis. Although CTC’s are great biomarkers, there is about 1 to 10 CTC’s found in 1 to 100 million white blood cells(3).

### Circulating tumor DNA:

Another form of cfDNA, circulating tumor DNA (ctDNA), is said to have passively left dying tumor cells or are actively released by secretion of tumor cells(3). ctDNA is unique as it is slightly easier to isolate than CTC’s and are more stable than cells and RNA(6). ctDNA in the presence of cfDNA can be uniquely identified due to tumor specific mutations, copy numbers, and ctDNA methylation(7). Methylation of the ctDNA makes ctDNA a key biomarker for cancer detection. ctDNA not only show the mutations, but also the methylation around the promoter region, which helps show how and why cancer may be under expressing or overexpressing certain proteins. Furthermore, monitoring ctDNA levels compared to CTC levels shows that one can predict relapse after surgery.

![Image 2](https://github.com/nsrejan/BENG183REPORT/raw/master/Fig2BENG.png)
#### Fig 2. Random patient data with analysis of ctDNA versus CTC levels in a given time period where PD is progressive disease, PR is partial response, and SD is stable disease. 

## Detection of cancer:

### Whole Genome Sequencing 
Whole genome sequencing(WGS) is used to sequence an entire cancer patient’s genome and map it to a germline genome. WGS of the patient’s ctDNA allows us to map the mutations on the chromosomal loci to find the copy number variations(CNV) present. This approach also helps to detect a higher ratio of intronic or passenger mutations than targeted re-sequencing(8).

### Whole Exome Sequencing 
Whole exome sequencing (WES) is used to sequence the protein coding regions (exons) of the cancer patient’s genome and map it to a germline genome. WGS of the patient’s ctDNA allows counting of the number of allelic fractions of mutations present. This allows one to track the CNV over time from the beginning of the treatment to its end, and allows tracking of potential relapse. WES gives a deeper look into mutation regions sought out by WGS while being more cost effective(8).

## Treatment of cancer through targeted sequencing:

### Cancer personalized profiling by deep sequencing:
Cancer personalized profiling by deep sequencing (CAPP-Seq) is a next generation sequencing(NGS) technology that is an economical and an ultrasensitive method for quantifying ctDNA.9  Since tumor levels are correlated with ctDNA levels, CAPP-Seq is able to detect ctDNA levels in 100% of small cell lung cancer (NSCLC) patients in stage II-IV while being able to detect 50% of ctDNA in stage I(9). CAPP-Seq is able to quantify ctDNA by creating a library of the mutation regions shown by the global WES of cancer patients and having a “selector.” This “selector” is then used to find individual genetic variations in the patient and the ctDNA. This allows quantification of ctDNA(9). Using CAPP-Seq to monitor ctDNA levels proves important in monitoring relapse and treatment to avoid further tumor growth.

![Image 3](https://github.com/nsrejan/BENG183REPORT/raw/master/Fig3BENG.png)
#### Fig 3. Pipeline of CAPP-Seq through detection of cancer specific mutations used to compare to a new patient to discover patient specific mutations and quantify ctDNA levels.

### Tagged Amplicon deep Sequencing

Tagged Amplicon deep Sequencing (TAm-Seq) is another NGS technology that uses the library of gene hotspots and CNV’s that were produced through WGS and WES, to detect and quantify the known cancer mutations in the ctDNA. TAm-Seq is able to identify allele frequencies as low as 2% with a sensitivity and specificity of greater than 97%(10). TAm-Seq utilizes two step amplification with high throughput PCR. Primers are specifically designed to cover CNV regions of interest. The first amplification takes place in parallel, preserving all alleles with mutations, then, selectively amplifies regions of interest using single-plex PCR. Finally, sequence adaptors are added to the amplicons before being pooled and sequenced(10). Over time, TAm-Seq provides single nucleotide variation (SNV) level analysis to tract treatment and growth of tumors where one can find common mutations and patterns among individuals fighting the same cancer, so as  to personalize their treatment based on mutation variations. TAm-Seq as a targeted sequencing method is the cheapest NGS in which many samples can be run in parallel.

![Image 4](https://github.com/nsrejan/BENG183REPORT/raw/master/Fig4BENG.png)
#### Fig 4. Analysis of multiple patients and their allele frequency over time for multiple mutations from a given gene panel.

![Image 5](https://github.com/nsrejan/BENG183REPORT/raw/master/Fig5BENG.png)
####5 Fig 5: TAm-Seq pipeline for detection of mutations a gene panel though coloring of gene based on amount of mutations in gene present.

<table>
 <tbody>
    <tr>
        <th>Attribute / Parameter </td>
        <th>Whole Genome Sequencing (WGS) </td>
        <th>Whole Exome Sequencing (WES)</td>
        <th>Targeted Sequencing</td>
    </tr>
    <tr>
        <td> Information Level </td>
        <td> Everything </td>
        <td> Genes </td>
        <td> User Defined </td>
    </tr>
    <tr>
        <td> Cost Per Sample </td>
        <td> $5000 </td>
        <td> $2000 </td>
        <td> $200 </td>
    </tr>
    <tr>
        <td> Low Frequency Mutation Detection </td>
        <td> Not Possible </td>
        <td> Not Likely </td>
        <td> Yes </td>
    </tr>
    <tr>
        <td> DNA Input Amount </td>
        <td> 1 ug </td>
        <td> 100 - 200 ng </td>
        <td> 10 ng </td>
    </tr>
    <tr>
        <td> # of Samples in Parallel </td>
        <td> 1 </td>
        <td> 2 </td>
        <td> 96 </td>
    </tr>
 </tbody>
</table>
<br>

#### Table 1. Summary of WGS, WES, and targeted sequencing and their pros and cons.

## Future of precision medicine:

Cancer diagnostics continues to grow as its net worth is looking to rise to 168 million by 2022. With as many as 14 million new cancer cases each year(11), and 8.8 million deaths due to cancer per year11, the need to treat each person as an individual rather than a group becomes greater.  Precision medicine and liquid biopsies are the near future, and possibly a way to counter this alarming cancer growth. Through NGS we see that it is possible to create a library of every individual. WGS offers a way for new cancers to be detected early through mapping individuals to a germline genome. The combination of a library of person’s genes coupled with a detailed mapping will have tremendous effectiveness. Furthermore, WES offers a more in depth look at those exons and can give specific genes to target and find their function. Targeted sequencing offers individual base variations among genes as a way to find a one to one correlation to cancer and a solution to the problem. Through these methods a more precise treatment can be given. Such is the future of medicine and a way to a cure for cancer through liquid biopsies coupled with NGS.


## Works Cited <a name="7"></a> 
(1) Sudhir Srivastava, Rashmi Gopal-Srivastava; Biomarkers in Cancer Screening: A Public Health Perspective, The Journal of Nutrition, Volume 132, Issue 8, 1 August 2002, Pages 2471S–2475S, https://doi.org/10.1093/jn/132.8.2471S

(2) Tang, Yong et al. “Biomarkers for early diagnosis, prognosis, prediction, and recurrence monitoring of non-small cell lung cancer” OncoTargets and therapyvol. 10 4527-4534. 12 Sep. 2017, doi:10.2147/OTT.S142149

(3) Neumann, Martin H D et al. “ctDNA and CTCs in Liquid Biopsy - Current Status and Where We Need to Progress” Computational and structural biotechnology journal vol. 16 190-195. 1 Jun. 2018, doi:10.1016/j.csbj.2018.05.002 

(4) Ilié, Marius and Paul Hofman. “Pros: Can tissue biopsy be replaced by liquid biopsy?” Translational lung cancer research vol. 5,4 (2016): 420-3.


(5) Chen, Lichan et al. “Circulating Tumor Cells: Moving Biological Insights into Detection” Theranostics vol. 7,10 2606-2619. 25 Jun. 2017, doi:10.7150/thno.18588


(6) Lang, Julie E. “Advantages and Disadvantages of CtDNA vs CTC Assays: How to Move the Needle Forward towards Clinical Application.”

(7) Warton, Kristina et al. “Methylated circulating tumor DNA in blood: power in cancer prognosis and response” Endocrine-related cancer vol. 23,3 (2016): R157-71.

(8) Ma, Mingwei et al. “"Liquid biopsy"-ctDNA detection with great potential and challenges” Annals of translational medicine vol. 3,16 (2015): 235.

(9) Newman, Aaron M et al. “An ultrasensitive method for quantitating circulating tumor DNA with broad patient coverage” Nature medicine vol. 20,5 (2014): 548-54.

(10) Forshew, Tim, et al. “Noninvasive Identification and Monitoring of Cancer Mutations by Targeted Deep Sequencing of Plasma DNA.” Science Translational Medicine, American Association for the Advancement of Science, 30 May 2012, stm.sciencemag.org/content/4/136/136ra68.long?fbclid=IwAR0mAGpbXC5AW1E2db-EliHP5cppXg9aVd7sk8ZNUntVfxQLdngJQCATn8A.

(11) Montagnana, Martina and Giuseppe Lippi. “Cancer diagnostics: current concepts and future perspectives” Annals of translational medicine vol. 5,13 (2017): 268.

(Fig1) Vendrell, Julie A et al. “Circulating Cell Free Tumor DNA Detection as a Routine Tool forLung Cancer Patient Management” International journal of molecular sciences vol. 18,2 264. 29 Jan. 2017, doi:10.3390/ijms18020264

(Fig2) Lang, Julie E. “Advantages and Disadvantages of CtDNA vs CTC Assays: How to Move the Needle Forward towards Clinical Application.”

(Fig3) “CAPP-Seq.” Wikipedia, Wikimedia Foundation, 4 Mar. 2018, en.wikipedia.org/wiki/CAPP-Seq.

(Fig4) Rosenfeld, Nitzan. Assessment of Clinical Applications of Circulating Tumour DNA in Lung Cancer Using an Enhanced TAm-SeqTM Platform. www.inivata.com/wp-content/uploads/2016/06/InivataPoster_IASLC_September_2015.pdf.

(Fig 5) Clark, James, and Nitzan Rosenfeld. Analytical Performance and Validation of an Enhanced TAm-Seq™ Circulating Tumour DNA Sequencing Assay across Two Laboratories. www.inivata.com/wp-content/uploads/2016/11/inivata-ncri-poster.pdf.

(Table 1) LabRoots. “Raed Samara - Liquid Biopsy and NGS Moving from Sample to Insight.” YouTube, YouTube, 6 Apr. 2016, www.youtube.com/watch?v=dZ4MGn_8tDo&index=50&t=989s&list=LLL8qNBI8yRvgffU7lIsH8cw.
