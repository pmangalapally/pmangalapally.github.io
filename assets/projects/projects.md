[Home](https://pmangalapally.github.io/)

**Projects:**  
Member Enrollment  
Member Eligibility  
Member Provider assignment  
Member Identity Cards  
Reports remediation for database platform migration  
Trizetto's Facets upgrade  
Encounters execution  
Encounters home-grown applications migration to Trizetto's Encounter Data Manager product including historical data. 
Application users reporting and monitoring for security  
File transfer batch job  
File archival batch job    
Windows Service control and monitoring  
File compression  
Extract Transform Load operations using SQL Server Integration Services (SSIS)  
Operational reports and alerts  
Data pipelines for Analytics systems  
Proprietary files consumption from vendors and Medicaid/Medicare Encounters processing agencies  
837 x12 compliance processes for outbound and inbound files  
999 responses for outbound and inbound files    
Encounter Data pipelines for CMS Interoperability Patient Access API implementation  
837 Claim data comparison between files generated between home-grown and EDM applications. This tool was extensively used at the time of homegrown application migration to EDM product.  
Tool to change import ID in EDM proprietary files to expedite unit testing EDM product and customizations.  
Testing automation for 837 File compliance, Inbound file translation proprietary files to load into Enterprise Data Warehouse and Encounters staging database.  
Batch jobs design   
Incident management process.  
Data Center Migration   
Facets Database migration from Sybase to SQL Server   
Data assets for low-code, cloud-based Business process management (BPM) product Appian to build necessary workflows for Enterprise Encounter (Error) Management.  
Utility scripts for Operations team test data setup, and validation and eliminate repeated manual day-to-day activities.  
Trizetto's Encounter Data Manager product new instance setup and upgrades.  
#metricsmatter - Built/assisted pipelines for data summarizations for several dashboards, examples are Encounters rolling 24th months summary, Trend dashboard for executives to view claims, encounters trends & Enterprise Encounters Error Management completeness, timeliness, accuracy, and rejections/scrubs dashboards.  
you can't manage what you can't measure.  
Differentiate data vs quality/good data.  
**Automation:**  
Identify terminated employees' EDM logins by looking up EDM login (email/network id) against Active Directory to term in EDM as well. Developed PowerShell scripts to scan for EDM active users against active directory to identify inactive in AD or users who changed departments to revoke user's permission to EDM product.

EDM files are generated and cleaned up for file generation for data corrections and generate files. The previous set of files and new file submissions resulted in duplicate rejections at the Encounters processing agency. Developed a process to scan for files in a configured directory recursively with matching file name regex and lookup those file names (in some cases we read Interchange Control# from ISA13) against the database table to move invalid files to a different directory and notified users.

Enrollment Consolidated Inventory Control System.
Workflow Inventory Reconciliation Enrollment System (WIRES) - Words changed in the name to make up the acronym. The purpose of the application is to maintain Enrollment error reconciliation.

According to HIPAA guidelines we are required to send vendor-specific responses to vendors. Developed a custom process to identify vendor files/content by NCPDP D.0 file batch ID between vendor inbound and response file from state, or date of service, or by looking up claim ID prefixes. 

Migrated all of the Encounter department's in-house file transfer applications that non-AmeriHealth entities are involved to the IBM Sterling File Gateway product. Advantages are:  
  1) Easy to onboard new trading partners (producer/consumer).  
  2) Duplicate check feature based on file name or content. A number of days to look for duplicate criteria can be configured.
  3) Seamless file deliveries from source to multiple destinations.  
  4) Ability to zip (compress)/ unzip (decompress), and rename files.
  5) Better alert, tracking, reporting, and analytics systems.
  6) Ability to customize scanner/file watcher run time for individual routes.
  7) Regular expressions are used for file name search expressions (file mask).
The background of the onboarding tool was batch jobs and manual interventions resulted in missing SLAs and sometimes assumed file was delivered to agencies.

**Application unification:** 
  1) Individual LOB's HIPAA/SNIP level validation (so-called compliance) applications are unified into a single application/batch job. IBM's Special Processing Engine product is used to validate HIPAA validations. A unified job is implemented to scan for multiple LOBs X12 files using a configuration table. This approach reduced the onboarding of new vendors/LOBs, and the decommissioning of existing vendors/LOBs. At least 1000 hours (planning, development, testing, implementation) invested in implementing LOB-specific bath jobs in the past. Duplication was a pain for maintenance since the same change was required in multiple places.

  2) Response split process unifications: 277U, 835, proprietary, NCPDP HTML/999, EXT Rejects, etc. Vendor-specific response delivery for Encounters response received from Medicaid/Medicare Encounters processing agencies.   
  
  3) Data pipelines for EEM's Appian workflow system: Developed data pipelines to bring errors (rejected encounters) & scrubs (drops due to validation failures) from multiple source systems to a single system for building a workflow system for the error remediation process.  
     
**Disaster Recovery Orchestration & Testing:**
  1) Orchestrated Disaster Recovery for Encounters (EDM, SPE, and Encounters legacy) applications.
  2) Assisted the DR team in developing disaster recovery workflows using the IBM Resiliency Orchestration product.
  3) United tested workflows, automated failback, failover validations & IBM RO's fallback scripts using PowerShell.
  4) Collaborated with PCE, NOC, AD, DR, MFT, SQL DBAs & QA teams during DR testing activities.
  5) Yearly 4 times (2x production and 2x non-production).

**Vendors/Subcontractors:**   
  **Vision:** Avesis, DavisVision Premier & VSP.  
  **Lab:** LabCorp & JVHL.  
  **Dental:** Scion/SkyGen, Avesis, DinalDental, DentaQuest & Dencap.  
  **Transportation:** MTM, Access2Care, LYFT, Southeastrans/Verida, Coordinated Transportation Solutions (CTS) & Logisticare/ModivCare.  
  **Hearing:** HearUSA.  
  **Behavioral Health:** Optum.  
  **Nursing Facilities:** Coastal Care.   
  **Pharmacy:** Abarca, DST Pharmacy Solutions (formerly Argus Health), SS&C Health, Magellan Rx, PerformRx.  
  **Other:** PPL (Public Partnerships LLC).  

**Line Of Businesses:**  
Medicaid, Medicare, Medicare-Medicaid, Exchanges, Children's Health Insurance Program (CHIP) and Third Party Administration.  

**States:**  
Delaware, Florida, Kentucky, Louisiana, Michigan, New Hampshire, New Jersey, North Carolina, Pennsylvania, South Carolina, Ohio, and Washington District of Columbia.  
**Training:**
Trained 15 programmers/developers to use an open-source git source code (version) control system with detailed release strategy documentation.  

**Achievements:**  
$10 million one-time saving by reconciling source claims against Encounters submitted to submit unprocessed and resubmit rejected Encounters with corrected information to meet State defined completeness and accuracy SLAs.  
Reconciliation uncovered a bunch of problems in claims adjudication and Enterprise Data Warehouse systems.  
$70K per year saving by automating manual activities in a legacy home-grown application at the time of reinsurance application migration to the Open Twins application.
40% (~400) of batch jobs were eliminated by redesigning applications. This is a great relief for the Technology Operations team.  
Current state systems assessment and future (to be) state systems recommendations. Get claims, Encounters volume, and $ summary.  
Redesign Encounters Data Processing System applications to improve acceptance by 18% in the initial submission. Resubmission cost $360,000 (2 resources * 1800 hours * $100) per year cost savings.  
End-to-end Medicaid/Medicare/Medicare-Medicaid Encounter Data Processing execution in Delaware, Florida, Kentucky, Louisiana, Michigan, New Hampshire, New Jersey, North Carolina, Pennsylvania, South Carolina, and Washington District of Columbia states.  
Trained 15 programmers/developers to use an open-source git source code (version) control system with detailed release strategy documentation.  

