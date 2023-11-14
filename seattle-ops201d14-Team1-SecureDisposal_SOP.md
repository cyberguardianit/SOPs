# SOP: Secure Disposal of Sensitive Data with DoD 5220.22-M Compliance

## Purpose:
This Standard Operating Procedure (SOP) outlines the secure process for disposing of sensitive data from storage media, adhering to the DoD 5220.22-M Standard.

## Scope:
This procedure applies to all employees involved in the disposal of storage media containing sensitive data within the company premises.

## Responsibilities:
- **Implementation:** IT Security Team and Data Management Personnel
- **Following:** All employees involved in data disposal
- **Reviewing:** IT Security Team
- **Maintaining and Updating:** IT Security Team

## Prerequisites:
- Access to storage media disposal tools compliant with DoD 5220.22-M.
- Knowledge of the company's sensitive data handling policies.

## Definitions:
- **Policy:** Broad, overarching guidance explaining "why" certain practices are implemented.
- **SOP (Standard Operating Procedure):** Specifies "what, when, why" actions; may consist of multiple SOPs supporting a specific policy.
- **Work Instructions:** Detailed "how-to" guides providing step-by-step directions for a particular task.

## Procedure:

### Overview:
This procedure focuses on the secure disposal of sensitive data from storage media, ensuring compliance with the DoD 5220.22-M Standard and preventing the unauthorized release of intellectual property.

#### 1. Identify Sensitive Data on Storage Media:
- **Overview:** Recognize and classify sensitive data stored on media slated for disposal.
- **Steps:**
  - Collaborate with data owners to identify sensitive information.
  - Perform scans or use data classification tools to confirm the presence of sensitive data.

#### 2. Prepare Storage Media for Disposal:
- **Overview:** Make storage media ready for secure disposal.
- **Steps:**
  - Physically label storage media identified for disposal.
  - Ensure backups of critical data have been completed before disposal.

#### 3. Perform Secure Data Erasure with DoD 5220.22-M Standard:
- **Overview:** Execute the data erasure process in compliance with the DoD 5220.22-M Standard.
- **Steps:**
  - **Use certified data wiping tools or software:**
    - Employ tools that adhere to the DoD 5220.22-M standard for secure data erasure.
    - The company will utilize DBAN (Darik's Boot and Nuke).
  - **Perform three overwriting passes using DBAN:**
    - Execute a series of three passes to overwrite the entire storage area.
    - Download DBAN: Visit the official [DBAN website](https://dban.org/) and download the ISO file.
    - Create a Bootable USB or CD/DVD: Use a tool like Rufus (for USB) or ImgBurn (for CD/DVD) to create a bootable media with the DBAN ISO.
    - Boot from DBAN: Insert the bootable media into the computer you want to securely erase. Boot the computer from the DBAN media.
    - Select DoD 5220.22-M Method: DBAN will present a menu with various erasure methods. Choose the method that corresponds to the DoD 5220.22-M standard. This is often labeled as "DoD Short" or "DoD 3 Pass." Ensure that the overwriting process covers all sectors of the storage media.
    - Start the Erasure Process: Follow the on-screen instructions to start the erasure process. DBAN will overwrite the entire storage area based on the selected method.
    - Complete the Process: Once the erasure process is complete, DBAN will provide a report indicating the success of the operation.
  - **Validate and document the successful completion of the data erasure process:**
    - Confirm that the data erasure process has been completed successfully.
    - Document the details of each pass, including the characters used and any relevant information.
    - Retain records for auditing and compliance purposes in accordance with local legal guidelines.

## Expected Results:
Sensitive data will be securely disposed of from storage media, following the DoD 5220.22-M Standard, safeguarding intellectual property within the physical confines of the company building.

## Revision History:
- Version 1.0 (2023.11.14): Initial document creation. Dominique Bruso

## References:
- Source 1: DoD 5220.22-M Standard
- Source 2: So, You Want to Write an SOP
- Source 3: 37 Best Standard Operating Procedure (SOP) Templates
- Source 4: [DBAN Official Website](https://dban.org/)
