# DIGITAL FORENSICS WITH AUTOPSY

## Objective

The project aimed to investigate a SanDisk flash drive as potential evidence in a drug trafficking case. The primary focus was to acquire a forensic image of the device, preserve the integrity of the original evidence, and analyze the data using Autopsy. The investigation involved recovering deleted files, examining metadata, and performing keyword searches related to trafficking activity. This hands on case simulation was designed to strengthen understanding of digital forensics procedures, chain-of-custody documentation, and evidence reporting for criminal investigations.

### Skills Learned
- 🕵️ Proficiency in using Autopsy for forensic analysis.

- 💾 Ability to acquire and preserve digital evidence from storage media.

- 🔍 Recovery and examination of deleted files and hidden data.

- 📜 Understanding and documentation of chain-of-custody procedures.

- 📝 Enhanced skills in writing professional forensic investigation reports
- 🧠 Development of analytical thinking for correlating evidence with case co



### 🛠️ Tools Used  

- **FTK Imager** 🖼️ – Created and managed forensic disk images  
- **Windows Registry Editor (Regedit)** 📝 – Configured as a software write blocker  
- **Autopsy** 🔍 – Performed forensic analysis and evidence recovery  


## Steps


<img width="1920" height="1080" alt="Screenshot (385)" src="https://github.com/user-attachments/assets/1fe313ba-76f4-46e2-8a3e-62e8bceb44d8" />

-  I implemented a software based write blocker using Windows Registry Editor (Regedit) to ensure that the original evidence files remained unaltered during the disk imaging process. By applying this configuration, the system was prevented from making any write operations to the evidence drive.


-  Problem Solved: This step safeguarded the integrity of digital evidence, ensuring compliance with forensic best practices and maintaining a reliable chain of custody.  


<img width="1920" height="1080" alt="Screenshot (392)" src="https://github.com/user-attachments/assets/93d9fa77-79d8-4e8c-bc60-6af0527e9828" />

- I used FTK Imager to create a forensic disk image of the target drive. The tool allowed me to capture a bit-for-bit copy of the evidence drive, ensuring that all data, including hidden and deleted files, was preserved.

- Problem Solved: This step created a forensically sound replica of the original evidence, allowing me to perform further analysis without risking alteration of the original data.

