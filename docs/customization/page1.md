# **Adding or Updating Regional Data**

**Important:** Administrative rights are required to edit or create ADM data. If you do not have the necessary permissions but believe you should, please contact your system administrator (**Jack Harrison – jharrison@redcross.nl**).  

## **Adding a New Country to the System**  

Before using the system for a new country, you must first upload its administrative regions.  

This process involves multiple steps, as each administrative layer must be uploaded separately.  

**Note:** The system is only recommended for use if you have administrative data down to at least **ADM2**. Additionally, the system currently supports data up to **ADM3**.  

### **Required Data for Each Administrative Layer (Template name shown in brackets)**

**ADM0 (Country):**

- Country name (name)
- ADM0 PCODE (pcode)
- Population (pcode)

Download ADM0 template [here](https://docs.google.com/spreadsheets/d/1bGP0UqasEV6Qjf38MlnMrv_Wf5WNp_1vVmRBOxb0EGo/export?format=csv)

**ADM1:**

- Country name (adm0Name)
- ADM1 Name (name)
- ADM1 PCODE (pcode)
- ADM1 Population (pop)

Download ADM1 template [here](https://docs.google.com/spreadsheets/d/1HiYCJLmZCGibhGUpdpNGbwbfwH-l5y5Qwn9eqNH82JE/export?format=csv)

**ADM2:**

- Country name (adm0Name)
- ADM1 Name (adm1Name)
- ADM2 Name (adm2Name)
- ADM2 PCODE (pcode)
- ADM2 Population (pop)

Download ADM2 template [here](https://docs.google.com/spreadsheets/d/1e0D-MQaNHPO_FEdkFs6sdY4q8h3oNhShs9jALvwLOCo/export?format=csv)

**ADM3:**

- Country name (adm0Name)
- ADM1 Name (adm1Name)
- ADM2 Name (adm2Name)
- ADM3 Name (name)
- ADM3 PCODE (pcode)
- ADM3 Population (pop)

Download ADM3 template [here](https://docs.google.com/spreadsheets/d/1nQMXl4sDsl0dtA6qVBbTzAfeqeN69DZbPc3tbn6kyNY/export?format=csv)


## **Adding the data to the system**

**Important:** Files must be uploaded in order from ADM0 to ADM3 to make sure they connect correctly to the higher administrative levels. Uploading them in the wrong order may cause errors in the data.

**Important:** Ensure the file has **no empty rows** before importing data into the system. Remove any empty rows beforehand.

Access the import page <a href="http://172.201.122.141/#Import" target="_blank">here</a>.


### **Step 1:**

Step 1 of the import page will look like this: 

![image](https://github.com/user-attachments/assets/83df7ddf-30f9-4a33-b3c6-6dfcb70d234b)

Most of this page can be ignored, but these key features are important:

**"What to Import?" Tab**

- **Entity Type:**

  Select the entity you are uploading data for. In this case, it’s administrative data, so choose from **ADM0, ADM1, ADM2, or ADM3**.

- **File (CSV):**

  Upload your file here using the template you previously downloaded and filled in. Ensure the file is saved as a **CSV**.

- **What to do?:**

  This is set to **"Create Only"** by default. If you are adding new regions, leave this as **"Create Only"**.

**Properties Tab**  
This section can mostly be ignored, but ensure **"Silent Mode"** is not enabled.

Click Next to proceed to Step 2.

### **Step 2: Reviewing and Running the Import**

At this stage, the import page will display a preview of your data, as shown below (example using ADM2 data from Mozambique):


![image](https://github.com/user-attachments/assets/2844159d-68af-4253-8b17-359b714c78d2)

The system should automatically match the fields. If any fields are incorrect or unmatched, you can manually adjust them using the dropdown menus.

Once everything looks correct, click **"Run Import"**. If the process encounters errors, click **"Revert Import"**, correct any mistakes in your CSV, and try again.


# Import Page Overview  

The **Import Page** provides an overview of a data import process, showing key details such as the file used, entity type, status, and results of the import.  

![image](https://github.com/user-attachments/assets/15506cd6-820a-4b0f-a562-49b51821c108)

## Main Sections  

### 1. Import Details  
- Displays the import timestamp.  
- Shows the entity type being imported (e.g., regions, locations, or other dataset types).  
- Links to the imported file.  
- Indicates the status of the import (e.g., *Complete*, *In Progress*, *Failed*).  

### 2. Import Results  
- **Imported**: Lists successfully imported records.  
- **Duplicates**: Shows any records that were flagged as duplicates.  
- **Updated**: Displays records that were modified instead of newly created.  
- **Errors**: Highlights any issues that prevented some data from being imported.  

This page allows users to verify the outcome of their data import and troubleshoot any issues if necessary.




