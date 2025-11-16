# MIST-4610-Group-Project-2

# 15058 - Group 6 - MIST 4610 Group Project #2 - Finding Phenomena in the Meteorite Landings Data Set with Tableau

## Authors

- Maxwell Stewart [@maxwellstewart](https://github.com/maxwellstewart)
- Andrew Robertson [@Andrew-Robertson10](https://github.com/Andrew-Robertson10)
- Alex Zou [@FireguyZou123](https://github.com/FireguyZou123)
- AJ Willis[@AJWillis172](https://github.com/AJWillis172)
- Aakash Parmar [@aakashbparmar](https://github.com/aakashbparmar)

Our dataset was found on https://catalog.data.gov/dataset which is a list of many different data set types. Our dataset contains information on all known meteorite landings worldwide. The data were collected by The Meteoritical Society, in association with NASA.
Some of the data that the set includes is the name, the class, the mass, the year it fell, and the latitude and longitude of where it fell for each meteorite.

## Question #1: Which regions of the world have the most discovered meteorite landings?
<img width="1433" height="666" alt="Image" src="https://github.com/user-attachments/assets/380100fc-6e11-4978-944b-c35b5872c72d" />
<img width="1402" height="660" alt="Image" src="https://github.com/user-attachments/assets/2a0834b6-2fb8-4fda-9f94-c2110f283d1e" />
<img width="1353" height="666" alt="Image" src="https://github.com/user-attachments/assets/83c2c56d-7920-4437-9783-4b5f0f8876bf" />
<img width="1344" height="594" alt="Image" src="https://github.com/user-attachments/assets/8f4b9dfe-3aef-4773-b684-156279660470" />
<img width="924" height="539" alt="Image" src="https://github.com/user-attachments/assets/31f0a76a-5098-48b7-8fba-300a82914c7b" />

- This density map shows that the majority of meteorites are found in Antarctica, followed by southeast Asia, Africa, and western Australia.
- Meteorites are more likely to be found in deserts (both hot and cold deserts) due to their unique climate that does not cause much erosion or change in the surface. Meteorites fall here and sit for many years before they are found, and nothing much has happened to the meteorite in this time. On the other hand, places with more precipitation or unpredictable climates experience more erosion and changes in the surface. Meteorites are harder to find in these regions because they erode or get covered up, leading to fewer meteorite discoveries.
- Antartica is especially significant because of the East Antarctic Icesheet. When the icesheet moves further into the surface and comes into contact with mountains, it pushes old deep ice to the surface and exposes centuries-old meteorites.

## Question #2: How has the number of documented meteorite landings changed over time, and how will this number likely change in the future?
<img width="1435" height="711" alt="Image" src="https://github.com/user-attachments/assets/9f627034-d1da-4850-a321-92acb074c37a" />
<img width="1232" height="708" alt="Image" src="https://github.com/user-attachments/assets/0919955b-a92d-417a-8272-0603ea85b140" />
<img width="1435" height="707" alt="Image" src="https://github.com/user-attachments/assets/765c843b-cfca-4200-a110-1eb5e57cb3fa" />

- This data shows that meteorite discoveries began an upward trend in the 1970s. This reflects the start of large-scale systematic search programs, including Antarctic expeditions by Japan (JARE) in 1969 and the U.S. ANSMET program beginning in 1976, which made meteorite collection far more organized and efficient.
- Improvements in classification methods, global scientific collaboration, and expanding international databases also drove rapid growth in the number of documented meteorites.
- The drop after the early 2010s is not a real decline in meteorite falls; it reflects delays in laboratory classification, publication lag in the Meteoritical Bulletin, and reduced field expeditions in key collection regions like Antarctica.

## Question #3: Which classes of meteorites are the most common? Which types of meteorites are the heaviest? Are heavier or lighter meteorites more common?
The visualizations created for this data are included in the following links because the number of different classes creates too many rows to be able to include these visualizations as screenshots.

[Table: Class Frequency](https://drive.google.com/file/d/1FDUKMRemxaiy9LFgGT54xDAULE8KMA4l/view?usp=sharing)

[Table: Median Class Mass Largest to Smallest](https://drive.google.com/file/d/1VfPwiMtnP7GGCCU2ByREHhpLtbjwacfv/view?usp=sharing)

- Iron meteorites are the heaviest but appear less frequently.
- The most common meteorites are small and belong to non-metallic classes.

## Manipulations
We excluded the last five years of data in the prediction model because meteorite records have a significant publication delay, which artificially depresses recent counts. After removing these incomplete years, Tableau is able to detect the underlying long-term growth trend in meteorite discoveries, resulting in a more realistic upward forecast.

We also filtered out very early data from before the 20th century, since efforts to discover meteorites did not exist back then and the number of meteorites found for each year during these time periods is either zero or in the single digits. Manipulating the data in this fashion allowed us to clean up the visualizations and better predict the future.

## Analysis and Results
We found one issue with the data set that we analyzed. Less data has been collected or the data is less complete for the more recent years. This is causing a dip in recorded data after the mid-2010s that is not necessarily representative of the number of meteorites that actually fell during these years. 
