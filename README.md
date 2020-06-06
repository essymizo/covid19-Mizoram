## covid19-Mizoram

Keeping track of covid19 in Mizoram. Data processed from official twitter account of [Directorate of Information and Public Relations, Mizoram (DIPR)](https://twitter.com/dipr_mizoram)

## Data features 

The official govt update on covid19 data are sourced from the above mentioned location only and any alterations anywhere else is not captured. 

The govt. released ambiguous data eg. a day update on covid numbers are usually in generic information -<i> there are 5 new infected patients out of which two are male and rest female, 3 comes from kolasib district and rest from aizawl etc </i>. Such data as and when found are recorded as blank during my processing. Please refer screenshot 

**If anyone knows anyone from DIPR, please ask them to upload data in standardised format :)**

[![Capture.png](https://i.postimg.cc/kgDJJGdp/Capture.png)](https://postimg.cc/0zRRZ8jY)

Below are the features -

1. Patient_Number - Pn (where n is number of covid patients, 1<=n) [NOT NULL]

2. Date_Announced - The date published on DIPR twitter account [NOT NULL]

3. Age_Bracket - Absolute, if mentioned. Else, a range separated by '-' if the number of infection is updated in groups (eg. 50, 18-56 etc) [NULL]

4. Gender - M/F, blank (null) in case ambiguous data [NULL]

5. Detected_City [NULL]

6. Detected_District [NULL]

7. Current_Status - Hospitalized/QC, null for ambiguity [NULL]

8. Notes [NULL]

9. Contracted_From - for local transmission, link to Patient_Numbe. Else, null for ambiguity [NULL]

10. Type_of_Transmission - Imported/Local [NOT NULL]

11. Status_change - the date changed status of patient is updated on DIPR twitter account [NOT NULL]

12. Source_1 - source of information [NOT NULL]

13. Source_2 - source of information [NOT NULL]

14. Travelling_From - if mentioned explicitly and if case is imported, else null [NULL]


## Maintainers

- [essymizo](https://github.com/essymizo)


## Contribution

If you're new to contributing to Open Source on Github, [this guide](https://guides.github.com/activities/contributing-to-open-source/) can help you get started. Please check out the [contribution guide](CONTRIBUTING.md) for more details on how issues and pull requests work

Open to corrections and suggestions. Please credit if you use any part of this repository. Thanks!
