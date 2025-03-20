# Image-Analysis-with-Autopsy
## Overview
- A forensic analysis conducted using Autopsy
- Focus: File recovery, analysis, tagging, and generating a report

## Tools used
- Autopsy
- Hashing(MD5, SHA1, SHA256)

## Overview
A teacher was caught teaching students material that was inappropriate and irrelevant to the course. Their drive from the computer was taken in for analysis to retrieve evidence. Tools used were Autopsy and Hash Calc. Disclaimer: In real life, the drive would be imaged and copied to be analyzed to stop from tampering with original evidence.

## Process
1. Start Autopsy and start a case with a name and directory for the folder
![Process](./Autopsy_photos/Screenshot%202025-03-19%20214558.png)
2. Type a case number and examiner information if needed
![Process](./Autopsy_photos/Screenshot%202025-03-19%20215151.png)
3. My data source type consisted of a disk image so that is what was selected
![Process](./Autopsy_photos/Screenshot%202025-03-19%20220152.png)
4. I put in the path to the suspect drive and put in hash values to ensure integrity later on
![Process](./Autopsy_photos/Screenshot%202025-03-19%20230635.png)   
5. I ran ingest modules on all checkboxes
![Process](./Autopsy_photos/Screenshot%202025-03-19%20230855.png)   
6. From here, I am able to look at all of the contents of the suspect drive such as images and files
![Process](./Autopsy_photos/Screenshot%202025-03-19%20231908.png)   
7. I tagged what may seem like evidence that can be used against a suspect, this lab consisted of something not as serious- teaching evolution which isn't allowed at this school
![Process](./Autopsy_photos/Screenshot%202025-03-19%20232746.png)  
8. Now I generated a HTML report with the subject as the header and the examiner, which is me, as the footer
![Process](./Autopsy_photos/Screenshot%202025-03-19%20233730.png)   
9. I reported on all tagged results
![Process](./Autopsy_photos/Screenshot%202025-03-19%20233848.png)  
10. After double clicking the report, you can see the "evidence" against this suspect
![Process](./Autopsy_photos/Screenshot%202025-03-19%20234047.png)
