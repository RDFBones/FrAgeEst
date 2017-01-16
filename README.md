# Extension “Freiburg Age Estimation” for RDFBones-O
## Anthropological background

This is an extension for the age estimation of adults utilising cranial and dental traits. The Freiburg method of age estimation (abbr. FrAgeEst) is a morphological method based on the scoring system developed in Vallois 1937 and adjusted by Hermann et al. 1990. Furthermore, the dental abrasion is based on the scoring system developed by Miles (1963) and Hermann et al. (1990). In addition, age groups following Knußman (1996) can be determined. The traits of the degree of ectocranial suture closure are evaluated according to Hermann et al. 1990. The ten cranial suture traits of FrAgeEst were used in the age estimation of skulls from the Alexander-Ecker-Collection in Freiburg. Additionaly, the Sphenofrontal suture and the sphenoparietal suture are evaluated. The morphological traits evaluated in a age estimation investigation are regarded as "assays" according to the definition of the OBI-ontology [class (obo:OBI_0000070)]:

    A planned process with the objective to produce information about the material entity that is the evaluant, by physically examining it or its proxies.

In this case, the evaluant is a specimen under investigation. The assays of the FrAgeEst-extension should be scored according to Hermann et al. 1990. All sections according to Hermann et al. 1990 that can be found on the fragment should be scored in an objective manner by the researcher. The sections should be classified as either 1) open, 2) in fusion, 3) closed, or 4) N/A. 

## Cranium:

**Sutura Coronoidea**

C1 = open = >45 years 
C1 = fusion = 45-54 years 
C1 = closed = <54 years 

C2 = open = >70 years 
C2 = fusion = 70 years 
C2 = closed = <70 years 

C3 = open = >33 years 
C3 = fusion = 33-42 years 
C3 = closed = <42 years 


**Sutura Sagittalis**

S1 = open = >50 years 
S1 = fusion = 50-59 years 
S1 = closed = <59 years 

S2 = open = >35 years 
S2 = fusion = 35-44 years 
S2 = closed = <44 years 

S3 = open = >20 years 
S3 = fusion = 20-29 years 
S3 = closed = <29 years 

S4 = open = >38 years 
S4 = fusion = 38-47 years 
S4 = closed = <47 years 


**Sutura Lambdoidea**

L1 = open = >55 years 
L1 = fusion = 55-64 years 
L1 = closed = <64 years 

L2 = open = >65 years 
L2 = fusion = 65-74 years 
L2 = closed = <74 years 

L3 = open = >70 years 
L3 = fusion = 70 years 
L3 = closed = <70 years 


**Sphenofrontal Suture**

SF1 = open = >50 years
SF1 = fusion = 50-59 years 
SF1 = closed = <59 years 


**Sphenoparietal Suture**

SP1 = open = >55 years
SP1 = fusion = 55-64 years 
SP1 = closed = <64 years


These traits (regarded as “assays” in the framework of RDF-Bones) and their age range are in general according to  Vallois 1937 and adjusted by Hermann et al. 1990.Ferembach et al. The traits of the degree of ectocranial suture closure are evaluated according to Hermann et al. 1990. 

These twelve cranial sutures of FrAgeEst were used in the age estimation of skulls from the Alexander-Ecker-Collection in Freiburg (for further information on the Alexander-Ecker-Collection cf. Kästner et al. 2011). Thus, the collected data from the Alexander-Ecker-Collection can be digitized and made accessible for future research within the flexible RDFBones-Ontology by means of this extension.

## References:

Vallois, H.V., La duree de la vie chez l'homme fossile. (1937), L'Anthropologie, Vol. 47, Dec.

Bernd Herrmann/Gisela Grupe/Susanne Hummel/Hermann Piepenbrink/ Holger Schutkowski, Prähistorische Anthropologie. Leitfaden der Feld- und Labormethoden (Berlin/Heidelberg 1990), 67, Abb. 3.2.1.8.

A.E.W. Miles, The dentition in the assessment of individual age in skeletal material, in: D.R. Brothwell (Hrsg.), Dental anthropologie (Oxford 1963), 191-209, Fig. 10 R. Knußmann, Vergleichende Biologie des Menschen, Lehrbuch der Anthropologie und Humangenetik (Stuttgart 1996), 169.

## Wiki index

This wiki should satisfy two objectives at once. On the one hand, the wiki contains further information about the extension itself (mostly network graphs) and some general tips for writing extensions to make FrAgeEst understandable and a valuable resource for programmers interested in writing their own extensions. On the other hand, it explicates the workflow of an FrAgeEst investigation for anthropologists interested in carrying out age estimations accordingly and archiving research data. The information is spread over the following wiki pages:

* [General structure of FrAgeEst](General structure of FrAgeEst)
* [Investigation planning](Investigation planning FrAgeEst)
* [Study design execution](Study design execution FrAgeEst)
* [Drawing a conclusion](Drawing a conclusion FrAgeEst)
* [General tips for extension writing](General tips for extension writing FrAgeEst)

    
For a first impression, it is recommended to read them in the order ahead. Some of these pages relate to other pages which further explicate some points. The last page addresses programmers exclusively and can be skipped. The network graphs in this wiki follow the key to symbols in network graphs defined in the RDFBOnes-O wiki.
