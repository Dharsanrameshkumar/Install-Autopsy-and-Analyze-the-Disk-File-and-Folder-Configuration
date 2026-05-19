<img width="1600" height="807" alt="WhatsApp Image 2026-05-19 at 2 32 38 PM" src="https://github.com/user-attachments/assets/9574394a-57fa-4743-ba6f-3fa22dc1c44f" /># Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results
<img width="1914" height="978" alt="image" src="https://github.com/user-attachments/assets/15797946-b188-4da1-a668-3cb4f46e667d" />
<img width="1911" height="951" alt="image" src="https://github.com/user-attachments/assets/167184fa-4d66-4bed-89e9-251e70bdbf3f" />
<img width="1904" height="874" alt="image" src="https://github.com/user-attachments/assets/8e876dfe-f9be-4aa9-a416-6a2dbca01e10" />
<img width="1807" height="982" alt="image" src="https://github.com/user-attachments/assets/ab7a723c-c619-462e-8a36-4ebd8a7669d1" />
<img width="1511" height="865" alt="image" src="https://github.com/user-attachments/assets/18cf1847-4b8f-4140-b136-824533726148" />
<img width="1418" height="858" alt="image" src="https://github.com/user-attachments/assets/5a89bac5-df65-4c0c-8cea-bb0ff6545c79" />
<img width="1367" height="863" alt="image" src="https://github.com/user-attachments/assets/7c19d7f5-eee7-41b7-a0bd-0bdbdb26b7a4" />
<img width="1600" height="900" alt="WhatsApp Image 2026-05-19 at 2 32 10 PM" src="https://github.com/user-attachments/assets/4e42453c-8fc1-40b6-bd0d-48204497e83d" />
<img width="1600" height="900" alt="WhatsApp Image 2026-05-19 at 2 31 54 PM" src="https://github.com/user-attachments/assets/a752754d-3623-4652-9b05-faaeba9a1889" />


<img width="1600" height="807" alt="WhatsApp Image 2026-05-19 at 2 32 38 PM" src="https://github.com/user-attachments/assets/d58f1d1d-bd76-467d-bb1a-ba13ad358674" />









## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
