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








<img width="1920" height="1080" alt="Screenshot (386)" src="https://github.com/user-attachments/assets/77ab0730-e039-4056-90e0-f062c0e2a678" />

- I created a dedicated folder on my W: Drive to store all files related to the investigation. This ensured that the case data was kept separate from the system’s main drive (C:), reducing the risk of accidental modification or corruption of evidence.
- Problem Solved: By isolating the investigation files from the main disk, I maintained data integrity and organization, which is critical in forensic investigations.

<img width="1920" height="1080" alt="Screenshot (392)" src="https://github.com/user-attachments/assets/93d9fa77-79d8-4e8c-bc60-6af0527e9828" />

- I used FTK Imager to create a forensic disk image of the target drive. The tool allowed me to capture a bit-for-bit copy of the evidence drive, ensuring that all data, including hidden and deleted files, was preserved.

- Problem Solved: This step created a forensically sound replica of the original evidence, allowing me to perform further analysis without risking alteration of the original data.
<img width="1920" height="1080" alt="Screenshot (394)" src="https://github.com/user-attachments/assets/9d810400-c08e-45ce-b9b5-973dd1b9d5ab" />
- The disk image was created successfully and I stored it in this folder on my W: Drive
<img width="1920" height="1080" alt="Screenshot (395)" src="https://github.com/user-attachments/assets/6b96e263-8a4c-4911-b193-669dad7d1087" />
-After creating the disk image, I loaded the evidence file into Autopsy. During the case setup, I selected the necessary modules that were relevant to this investigation, such as File Type Identification, Hash Lookup, and Keyword Search.

- Problem Solved: This step allowed me to automate evidence extraction and analysis, ensuring that critical artifacts (deleted files, file types, and suspicious data) were efficiently identified for further examination.
<img width="1920" height="1080" alt="Screenshot (400)" src="https://github.com/user-attachments/assets/4319bd68-e00d-4ad1-acb3-6f2be7ff4907" />
- Since this was a drug related investigation, I created a custom keyword list in Autopsy. The list included terms connected to drugs, which helped narrow down the search and detect relevant digital evidence more efficiently.

- Problem Solved: By creating a focused keyword list, I ensured that the search targeted drug related communications, files, and financial transactions, instead of wasting time on irrelevant data. This increased both the accuracy and speed of the investigation.
<img width="1920" height="1080" alt="Screenshot (403)" src="https://github.com/user-attachments/assets/a88ae9dd-8bf1-4151-9d3e-9f1f667287dd" />

- During the analysis, I discovered a folder labeled “Encrypted”, which appeared to contain sensitive information. Within this folder, files had extensions like .enc.txt and .gpp.txt, suggesting they were encrypted or specially formatted. I tagged these files as notable in Autopsy for further review.

- Problem Solved: This step ensured that potentially critical evidence was flagged for deeper investigation, preventing important files from being overlooked and maintaining a structured approach to case analy

<img width="1920" height="1080" alt="Screenshot (404)" src="https://github.com/user-attachments/assets/74e2d04d-dbaa-4ad0-96ec-4e74ba8c3a1a" />
- During the investigation, I located a file named invoice_new_goods.Docx. Based on its name and context, it was suspected to contain important information from suppliers. I marked this file as notable in Autopsy for further review and analysis.

<img width="1920" height="1080" alt="Screenshot (405)" src="https://github.com/user-attachments/assets/f24d3808-2304-4b6b-9540-c992725e695d" />

- Problem Solved: By tagging this document, I ensured that potentially crucial financial or transactional evidence was highlighted, making it easier to correlate with other findings in the case.
 During the analysis, I discovered two text files: client.txtx and debt.txt. Based on their filenames, these files were suspected to contain customer related information. I tagged both files as notable in Autopsy for further examination.

- Problem Solved: Tagging these files ensured that potential customer and debt related evidence was clearly identified and preserved for correlation with other case data.

  
  <img width="1920" height="1080" alt="Screenshot (407)" src="https://github.com/user-attachments/assets/ba21e7e9-59ab-42ef-9663-0044f40459ff" />

- Using Autopsy’s file carving and unallocated space analysis, I successfully recovered multiple deleted files from the disk image. These files included documents, spreadsheets, and text files that were no longer visible in the normal file system.

- Problem Solved: This step ensured that hidden or intentionally deleted evidence was retrieved, preventing loss of critical case inform<img width="1920" height="1080" alt="Screenshot (408)" src="https://github.com/user-attachments/assets/b9ffeb18-5e9b-49cc-bb59-169c893e0077" />
ation and providing a more complete picture of the digital activity related to the investigation.
<img width="1920" height="1080" alt="Screenshot (409)" src="https://github.com/user-attachments/assets/18b31268-4c39-49dc-8757-12fe3f40aaac" />

- During the analysis, I identified images depicting buildings and locations that appeared relevant to the investigation. I tagged these images as notable, as they could provide information about suspected meet-up points or transaction sites.

- Problem Solved: Highlighting these images ensured that location based evidence was preserved, supporting the reconstruction of events and potential links between suspects and physical locations.<img width="1920" height="1080" alt="Screenshot (410)" src="https://github.com/user-attachments/assets/676b2d1f-dbad-44fb-b26a-4944a88277c7" />

- During the investigation, I discovered a fake text file disguised as a video file. Upon inspection, the file contained sensitive information such as shipping details related to the suspected criminal activity. I tagged this file as notable in Autopsy for further review.

- Problem Solved: Identifying this decoy file ensured that hidden or misleading evidence was not overlooked, preserving critical information about transactions and shipments relevant to the case.
<img width="1920" height="1080" alt="Screenshot (411)" src="https://github.com/user-attachments/assets/a0ed60a5-0735-4868-981d-bfdaf76f93b7" />

- After completing the analysis, tagging notable files, and recovering deleted data, I used Autopsy’s reporting feature to generate a comprehensive case report. The report included:

- Recovered and notable files

- Tagged images and documents

- File paths and metadata

- Timeline of file activity

- Problem Solved: Generating this report consolidated all findings into a structured, professional document, providing a clear overview of the investigation and creating a record suitable for case review or presentation.

