# MIST-4610-Group-Project-2

# 15058 - Group 6 - MIST 4610 Group Project #2 - Finding Phenomena in the Meteorite Landings Data Set with Tableau

## Authors

- Maxwell Stewart [@maxwellstewart](https://github.com/maxwellstewart)
- Andrew Robertson [@Andrew-Robertson10](https://github.com/Andrew-Robertson10)
- Alex Zou [@FireguyZou123](https://github.com/FireguyZou123)
- AJ Willis[@AJWillis172](https://github.com/AJWillis172)
- Aakash Parmar [@aakashbparmar](https://github.com/aakashbparmar)

Our dataset was found on https://catalog.data.gov/dataset which is a list of many different data set types. Our dataset contains information on all known meteorite landings worldwide. The data were collected by The Meteoritical Society, in association with NASA.
Some of the data that the set includes is the name, the class, the mass, the year it was discovered, and the latitude and longitude of where it fell for each meteorite.

## Question #1: Which regions of the world have the most discovered meteorite landings?
<img width="1433" height="666" alt="Image" src="https://github.com/user-attachments/assets/380100fc-6e11-4978-944b-c35b5872c72d" />
<img width="1402" height="660" alt="Image" src="https://github.com/user-attachments/assets/2a0834b6-2fb8-4fda-9f94-c2110f283d1e" />
<img width="1353" height="666" alt="Image" src="https://github.com/user-attachments/assets/83c2c56d-7920-4437-9783-4b5f0f8876bf" />
<img width="1344" height="594" alt="Image" src="https://github.com/user-attachments/assets/8f4b9dfe-3aef-4773-b684-156279660470" />
<img width="924" height="539" alt="Image" src="https://github.com/user-attachments/assets/31f0a76a-5098-48b7-8fba-300a82914c7b" />

- This density map shows that the majority of meteorites are found in Antarctica, followed by southeast Asia, Africa, and western Australia.
- Meteorites are more likely to be found in deserts (both hot and cold deserts) due to their unique climate that does not cause much erosion or change in the surface. Meteorites fall here and sit for many years before they are found, and nothing much has happened to the meteorite in this time. On the other hand, places with more precipitation or unpredictable climates experience more erosion and changes in the surface. Meteorites are harder to find in these regions because they erode or get covered up, leading to fewer meteorite discoveries. (Case Western Reserve University, n.d.)
- Antarctica is especially significant because of the East Antarctic Icesheet. When the icesheet moves further into the surface and comes into contact with mountains, it pushes old deep ice to the surface and exposes centuries-old meteorites.

## Question #2: How has the number of documented meteorite landings changed over time, and how will this number likely change in the future?
<img width="1435" height="711" alt="Image" src="https://github.com/user-attachments/assets/9f627034-d1da-4850-a321-92acb074c37a" />
<img width="1232" height="708" alt="Image" src="https://github.com/user-attachments/assets/0919955b-a92d-417a-8272-0603ea85b140" />
<img width="1435" height="707" alt="Image" src="https://github.com/user-attachments/assets/765c843b-cfca-4200-a110-1eb5e57cb3fa" />

- This data shows that meteorite discoveries began an upward trend in the 1970s. This reflects the start of large-scale systematic search programs, including Antarctic expeditions by Japan (JARE) in 1969 (National Institute of Polar Research, n.d.) and the U.S. ANSMET program beginning in 1976 (Satterwhite et al., 2016) , which made meteorite collection far more organized and efficient.
- Improvements in classification methods, global scientific collaboration, and expanding international databases also drove rapid growth in the number of documented meteorites.
- The drop after the early 2010s is not a real decline in meteorite falls; it reflects delays in laboratory classification, publication lag in the Meteoritical Bulletin, and reduced field expeditions in key collection regions like Antarctica.

## Question #3: Which classes of meteorites are the most common? Which types of meteorites are the heaviest? Are heavier or lighter meteorites more common?
The visualizations created for this data are included in the following links because the number of different classes creates too many rows to be able to include these visualizations as screenshots.

[Table: Class Frequency](https://drive.google.com/file/d/1FDUKMRemxaiy9LFgGT54xDAULE8KMA4l/view?usp=sharing)

[Table: Median Class Mass Largest to Smallest](https://drive.google.com/file/d/1VfPwiMtnP7GGCCU2ByREHhpLtbjwacfv/view?usp=sharing)

- Iron meteorites are the heaviest but appear less frequently.
- The most common meteorites are small and belong to non-metallic classes (L and H classes).
- Carbonaceous chondrites (CM2, CO3, CV3, CK4) also have low masses because they are fragile and break up easily.
- Martian meteorites (shergottites, nakhlites, chassignites) show up with frequencies in the teens and median masses generally well under 200 g. 

## Manipulations
We excluded the last five years of data in the prediction model because meteorite records have a significant publication delay, which artificially depresses recent counts. After removing these incomplete years, Tableau is able to detect the underlying long-term growth trend in meteorite discoveries, resulting in a more realistic upward forecast.

We also filtered out very early data from before the 20th century, since efforts to discover meteorites did not exist back then and the number of meteorites found for each year during these time periods is either zero or in the single digits. Manipulating the data in this fashion allowed us to clean up the visualizations and better predict the future.

## Analysis and Results

- Geographic Distribution: The density map shows that meteorite discoveries are heavily concentrated in Antarctica, with additional hotspots in northern Africa, western Australia, and parts of Asia. This pattern aligns with environmental conditions. Hot and cold deserts preserve meteorites for long periods due to minimal erosion. Antarctica is especially productive because the movement of the East Antarctic Ice Sheet continuously exposes old ice and the meteorites trapped within it, resulting in unusually high discovery density in that region.

- Temporal Trends in Discoveries: The time-series visualization reveals a sharp rise in documented meteorite finds beginning in the 1970s. This period corresponds with the launch of large-scale systematic search programs, including JARE (1969) and ANSMET (1976), which shifted meteorite discovery from occasional chance finds to structured scientific expeditions. The forecast initially showed a flat trend until the final five years were excluded; once cleaned, the model displayed a realistic upward trajectory consistent with increasing global recovery efforts and expanding classification capabilities.

- Data Completeness and Publication Lag: The decline in meteorite counts after the early 2010s is not an actual decrease in meteorite falls. Instead, our cleaned visualizations confirm that recent years appear artificially low because meteorites cannot enter the Meteoritical Bulletin database until they have been chemically classified and approved. This process can take several years, especially for large batches collected in Antarctica. Filtering out these incomplete years significantly improved the accuracy of the forecast and showed that the number of meteorite discoveries will likely increase over time as technology improves and research activity increases.

- Class Frequency Patterns: Ordinary chondrites, particularly L6, H5, L5, H6, and LL5, are the most common meteorite classes, each with thousands of documented samples. These meteorites are stony, fragile, and prone to fragmentation during atmospheric entry, which explains both their high frequency and their consistently low median masses. The abundance of these small stony meteorites highlights that most recovered meteorites originate from common asteroid parent bodies and are not structurally robust enough to produce large masses.

- Mass Distribution and Composition: Median mass calculations show that iron meteorites dominate the high-mass end of the dataset despite being extremely rare. Nearly all of the top 20 highest-median-mass classes are iron groups or stony-iron types (mesosiderites, pallasites). These metals survive atmospheric entry more effectively than stony meteorites, making them more likely to reach the ground intact and be found as large, recognizable specimens. Conversely, fragile meteorite types such as carbonaceous chondrites (CM2, CO3, CV3) cluster near the bottom of the mass distribution, typically weighing under 200 grams.

- Relationship Between Mass and Frequency: A clear inverse relationship exists between mass and frequency. The most common meteorite classes have low median masses, while the heaviest meteorite types are rare. This pattern reinforces the role of physical survivability and detection bias. Large iron meteorites retain mass through atmospheric entry and are easier to spot on the ground, whereas smaller stony meteorites break into many fragments, increasing their frequency but reducing individual mass.

Overall Findings:
Together, the geographic, temporal, and compositional analyses show that meteorite discovery is shaped largely by environmental preservation, targeted scientific expeditions, and the material properties of meteorites themselves. After cleaning and filtering the dataset, our visualizations provide a clearer representation of these trends and allow for a more accurate forecast of future discovery patterns, causing a dip in recorded data after the mid-2010s that is not necessarily representative of the number of meteorites that actually fell during these years. 

## Works Cited

Case Western Reserve University. (n.d.). FAQs – ANSMET, The Antarctic Search for Meteorites. CASLabs. https://caslabs.case.edu/ansmet/faqs/

National Institute of Polar Research. (2025). History of Antarctic meteorite exploration. Antarctic Meteorite Research Center. https://yamato.nipr.ac.jp/english/exploration/exploration3/

Satterwhite, C. E., Funk, R. C., Righter, K., & Harrington, R. H. (2016). 40 years of processing pieces of space (NASA Technical Report No. JSC-CN-36539). NASA. https://ntrs.nasa.gov/archive/nasa/casi.ntrs.nasa.gov/20160007502.pdf

