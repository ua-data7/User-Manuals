<figure style="display: flex; justify-content: center;" markdown="span">
    ![cover](../assets/cover.png){ width="300", border="100" }
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    ![cyverse](../assets/de/cyverse.png){width="250"}
</figure>
 
<br>

![cy_h-banner](../assets/Cyverse_Health/banner.jpg)

<br>

# **CyVerse Health User Manual Overview**

---

## CyVerse Health: Spotlight on Functionality

Within the secure perimeters of Soteria lies CyVerse Health, a specialized web workbench designed for data science teams navigating the complex landscapes of PII and PHI. This component amplifies Soteria’s functionalities, providing a space where collaboration, customization, and control converge.

Key features of CyVerse Health include:

**Collaborative Workbench:** CyVerse Health offers a dynamic space where research teams can manage data and share customized workflows securely. This feature is instrumental in fostering collaboration and ensuring consistency across projects.

**Reproducible Research:** With its emphasis on containerization technology, CyVerse Health enables users to create reproducible workflows, a cornerstone in promoting transparency and verifiability in scientific discoveries.

**Secure Data Access:** It maintains a controlled environment where access to specific data sets is regulated, ensuring that only authorized individuals can view or manipulate sensitive information.

CyVerse Health therefore supports researchers by providing a secure, collaborative platform equipped with tools designed for in-depth data exploration and analysis, all within the secure ecosystem provided by Soteria.

##  Synergy: How CyVerse Health Complements Soteria

CyVerse Health is an integral part of the Soteria platform, designed to extend the capabilities provided by Soteria into more specialized areas of data management and analysis. It leverages Soteria’s foundational security infrastructure, providing a space where researchers can perform more nuanced tasks with an assurance of data protection.

This integration ensures that while researchers benefit from advanced tools and collaborative features specific to CyVerse Health, they remain within the overarching secure environment established by Soteria. This interconnectedness makes the combined platform a robust, comprehensive solution for conducting sensitive health-related research projects securely.

---

## Getting Started with CyVerse Health

!!! Warning "Getting Soteria Access"
    Before diving into the specific features and capabilities of CyVerse Health, users must first gain access to the overarching Soteria platform. Please refer to the [VPN Access page](../access/access_vpn.md) in the Logging in & Access section.

### Accessing CyVerse Health

!!! info " Although a [CyVerse](https://user.cyverse.org/) account is not needed, CyVerse Health require an approved [University of Arizona NetID](https://netid-portal.iam.arizona.edu/)."

Upon obtaining access to Soteria and connecting to the Soteria VPN, users can now access CyVerse Health at [**de.soteria.arizona.edu**](https://de.soteria.arizona.edu/).

<figure markdown="span">
  ![cyversehealthspash](../assets/Cyverse_Health/cyverse_health_01.png)
  <figcaption> CyVerse Health Home screen. </figcaption>
</figure>

Clicking the **Login** button will redirect you to the UA Web Authentication page. Insert your UA NetID and password, and you should be able to log in!

<figure markdown="span">
  ![cyversehealthspash](../assets/Cyverse_Health/cyverse_health_02.png){width="700"}
</figure>

Logging in should give you additional information on your Home screen. Now you will be able to see the following features:

- **Resource Usage**
    - **Data Storage**: How much data you have uploaded/generated and stored in the CyVerse Health Data Store.
    - **CPU Consumption**: All time [core hours](https://datascience.arizona.edu/research/cyverse#:~:text=*%20Compute%20units%20are%20normalized%20if%20jobs%20run%20on%20CPUs%2C%20GPUs%2C%20etc.%3B%201%20Compute%20Unit%20equals%201%20Core%20Hour%20on%20a%20CPU.)* consumed.
- **Analysis Status**: All time analyses status (completed, cancelled, failed, submitted and running)
- **Previous Analyes**: Shows previous results of completed analyses (non-depending of status).

**\*** Compute units are normalized if jobs run on CPUs, GPUs, etc.; 1 Compute Unit equals 1 Core Hour on a CPU.

<figure markdown="span">
  ![cyversehealthspash](../assets/Cyverse_Health/cyverse_health_03.png)
  <figcaption> CyVerse Health Home screen post log in. </figcaption>
</figure>

### Working with CyVerse Health

Once your account is set up, and you have access to the necessary services, you can start your projects on CyVerse. Utilize the Learning Center for helpful guides and tutorials on using different tools and services effectively. These resources are designed to assist you in understanding specific tasks or in-depth functionalities of CyVerse platforms.

**Remember:** Keep your account details secure, and ensure you log out from shared or public computers to maintain the security of your data.

## Getting Started with the Discovery Environment Interface

### Exploring the Main Interface:

Once logged in, take a moment to view the main dashboard. This central hub provides a snapshot of the tools and features at your disposal within the Discovery Environment.

1. Locate the search bar typically positioned at the top of the page. Here, you have the ability to perform integrated searches across different data points:

   a. Click on the dropdown menu adjacent to the search bar to filter your search criteria by 'Data,' 'Apps,' or 'Analyses'.

   b. Enter your query into the search field and press 'Enter' to execute the search. Review the returned results, accessible by navigating through the tabs corresponding to the categories mentioned above.
   
2. Familiarize yourself with the quick access icons, often found near the search bar:

   a. Look for a 'bag' or cart icon, symbolizing a space where you can aggregate items for download or sharing. It functions similarly to an online shopping cart, allowing you to organize data or apps you wish to further interact with.

   b. The 'notifications' bell icon is your go-to for updates on the platform. Clicking this will show you a history of your activities, including analysis statuses, data sharing updates, and general account activity.

3. Navigating the Sidebar Menu:

   a. Shift your attention to the left-hand sidebar, known as the 'DE Menu'. This is your primary navigation tool for the platform's various sections. If the sidebar is collapsed, you can expand it for more detailed descriptions by clicking the expand button (three line icon).

4. Explore the following key areas by clicking on each respective icon or text:

   **a. Home/Dashboard:** Your main control panel that may display summary widgets, quick links to recent activities, or educational content such as tutorials and webinars.
   
   **b. Data:** This interface connects you to the Data Store. Here, you can manage your files, including uploading, downloading, organizing, and sharing data. You'll have access to your personal storage space and shared directories.
   
   **c. Apps:** Discover various applications, including VICE (Visual Interactive Computing Environment) apps for interactive computing sessions. You can browse, search, and launch these applications based on your research needs.
   
   **d. Analyses:** View and manage your computational tasks. This section logs your history of analysis jobs, allowing you to monitor current processes, review completed ones, and access resulting data.
   
   **e. Cloud Shell:** Access a Linux shell environment directly within the DE. This feature enables advanced users to perform command-line operations without leaving the platform.
   
   **f. Teams:** Create and manage collaboration groups. Teams allow you to group together with other users for easier sharing of data, analyses, and other collaborative efforts.
   
   **g. Collections:** Explore public collections of data and apps curated by other users or the CyVerse team. This resource can be invaluable for finding information relevant to your studies.
   
   **h. Help:** Access various support materials, including FAQs, guides, and contact information for direct assistance from the CyVerse support team.

4. Data Management Overview: Return to the 'Data' section from the DE Menu to explore further. Within this space, you'll interact with several specific areas:

   **a. Your Personal Folder:** Navigate to your home directory. Use this private space to store your data files and analyses. You can create sub-folders for better organization.

   **b. Shared With Me:** Click on this folder to view items that other users have shared with you. This collaboration feature is crucial for team projects and shared research initiatives.

   **c. Community Data:** Explore data shared publicly by other CyVerse users. This repository can contain valuable resources for your research.

   **d. Trash:** View recently deleted items. You may have the option to restore files from here if necessary.


<summary>expand</summary></details>
   
# MANAGING THE DATA

## CyVerse Data Store

The CyVerse Data Store is an integrated data management solution, ensuring data remains FAIR - Findable, Accessible, Interoperable, Reusable. Access your files across all CyVerse platforms, utilizing features that maintain data integrity and value.

For detailed information and explorative blogs regarding Cyverse Health Data Stores written by researchers, visit https://cyverse.atlassian.net/wiki/spaces/DS/pages and https://cyverse.org/data-store

## Navigating Data Transfer Options

Different projects require different data transfer methods. Whether using the Discovery Environment's web interface, Cyberduck desktop app, or command-line tools like iCommands, CyVerse provides multiple ways to move your data securely and efficiently.

* **Discovery Environment (DE):**

  <ins>Web-based:</ins> Simple, no-installation approach.
  <ins>Data Limit:</ins> Up to 2GB per file for uploads, unlimited for import.
  
* **Cyberduck:**

  <ins>Desktop Application:</ins> Requires installation.
  <ins>Data Limit:</ins> Ideal for files larger than 10GB.

* **iCommands:**

  <ins>Command-line Interface:</ins> For tech-savvy users; installation required.
  <ins>Data Limit:</ins> Optimal for files exceeding 10GB, offering precise control.

* **SFTP Clients:**

  <ins>Versatile Access:</ins> Desktop and command-line accessibility.
  <ins>Data Limit:</ins> Preferred for transfers over 10GB.

* **GoCommands:**

  <ins>Developer-Friendly:</ins> Command-line based, necessitates installation.
  <ins>Data Limit:</ins> Handles files larger than 10GB efficiently.

<ins>**Choosing a Method:** </ins> Consider file size, technical comfort, and specific project needs. <ins>*For larger files,*</ins> prefer Cyberduck, iCommands, or SFTP. <ins>*For simplicity*</ins>, use the DE or Cyberduck. <ins>*For automation or programming environments*</ins>, opt for iCommands or GoCommands.

## 1. Managing the Data - In Discovery Environment

<details>

The Discovery Environment (DE) interface is a user-friendly, web-based portal designed for seamless management of your data within the CyVerse Data Store. This chapter provides a detailed guide on utilizing DE for various data management tasks.

* **Data Lifecycle Management:** Perform a variety of tasks like uploading, metadata addition, analysis, sharing, and publication.

* **Seamless Integration:** The Data Store is ubiquitous across CyVerse, allowing effortless file access and management from any platform.


**Remember:** The Data Store isn't a separate entity but a foundational service across CyVerse, granting you universal access to your data.

### a. Uploading Files/Folders

**Navigating to Data View:** 

* Once logged in to the DE, the 'Data' view offers a comprehensive directory-style layout of your Data Store contents.
* Select an existing folder for your uploads or create a new one by clicking the 'Folder' button. By default, uploads go to /iplant/home/<your_username>.

**Uploading Files:**

* Click 'Upload' and choose 'Browse Local' to select files from your computer.
* For files via URL, select 'Import by URL,' paste the link, and click 'Import'.
* An automated notification confirms your upload is in the queue. To check progress, click 'Upload' > 'View Upload Queue.'

**Special Notes:** Direct browser uploads are limited to files <2GB. For larger transfers, consider Cyberduck or iCommands.

**Drag-and-Drop Feature:** Alternatively, drag files from your computer directly into the DE browser window. This action also initiates the upload process.

**Background Uploading:** You're free to navigate away or log out during URL imports; a notification will inform you upon completion.

<ins>Example Scenario: Uploading a README.md File </ins>

* Create and save a README.md on your local computer, detailing contents like the 'ept2copc.json' file information.
* In DE, navigate to 'tutorial_folder,' click 'Upload,' then 'Browse Local.' Find and select your README.md file.
* Refresh your page if the uploaded file doesn’t appear immediately.


### b. Downloading Data

**Locating Files:**

* Log into DE and click the 'Data' icon. Your username indicates your personal space, while 'Community Data' houses shared files.
* Navigate to the desired directory (e.g., /usda/usfs/r3/coconino/training_data/mahan/).

**Downloading:**

* Select your file(s) by clicking the adjacent checkbox.
* Click 'More Actions' > 'Download' to save to your local machine.

  Important: Direct downloads via DE are suitable for files <2GB. For larger data, use Cyberduck, GoCommands, or iCommands.

**Access Points for Data Retrieval:**

Various paths access the same Data Store:
iCommands or GoCommands: /iplant/home/shared/usda/usfs/r3/coconino/training_data/mahan/
Discovery Environment: https://de.cyverse.org
WebDav Interface: https://data.cyverse.org

### c. Organizing Data: Creating Directories

* In your 'home,' click the 'folder+' icon to create 'tutorial_folder.'
* Inside it, establish sub-folders like 'raw_data/' and 'results/' for future use.

### d. Deleting Files/Folders

**Selection for Deletion:**

* From 'Data' view, mark files/folders by clicking their checkboxes.
* For bulk actions, use the master checkbox.

**Performing Deletion:**

* Click 'More Options' (ellipsis) and select 'Delete.'
* A notification confirms the deletion.

**Trash Management:** Deleted items move to 'Trash.' They remain recoverable until you empty the 'Trash' folder, which then reflects on your storage quota.

### e. Advanced Data Management

* To use the Advanced Search, run a query in the Search menu, then select "Advanced Search Options".

* The Discovery Environment also supports advanced data management tasks such as organizing your datasets, search, adding metadata to data, requesting a Digital Object Identifier (DOI), and importing or submitting data to/from NCBI SRA.

<summary>expand</summary></details>

## 2. Transferring Data with Cyberduck

<details>

Cyberduck is a versatile third-party tool that facilitates easy transfer of data between your local computer and the CyVerse Data Store. It's especially useful for transferring large or multiple files and offers functionalities like file renaming and browsing through shared or public Data Store locations.

### a. Setting Up Cyberduck

**Downloading and Installing Cyberduck:** 
* Go to the Cyberduck website and download the application compatible with your operating system.
* Install Cyberduck following the provided instructions.

**Configuring Cyberduck for CyVerse:**
* Download the CyVerse connection profile for Cyberduck.
* Double-click the downloaded profile to automatically open Cyberduck with the pre-configured settings.
* In the Cyberduck configuration window, enter your CyVerse username in the 'iPlant username' field.
* Under 'Advanced Options', set 'Transfer Files' to 'Open Multiple Connections'. Your settings will be saved once you close this window.

**Connecting to the Data Store:**
* In Cyberduck, double-click the Data Store bookmark.
* When prompted, enter your CyVerse credentials to establish the connection.
* You should now see your home directory in the Cyberduck window.
**Tip:** Use 'Go to folder' from the 'Go' menu to navigate to any Data Store location that is public or shared with you.


### b. Transferring Data Using Cyberduck

**Uploading to the Data Store:**
* Double-click the Data Store bookmark to connect.
* Drag files/folders from your local machine into the Cyberduck window. You can also create a new folder via the 'File' menu.
* The 'Transfers' window will display the progress. Wait until the upload is complete.
**Warning:** Avoid using spaces or special characters in file/folder names. Use underscores (_) instead of spaces.

**Downloading from the Data Store:**
* Connect to the Data Store using the bookmark.
* Drag files/folders from the Cyberduck window to a local directory.
* The 'Transfers' window will show the progress. Monitor until the download finishes.
**Caution:** Manage the number of connections to avoid overloading the system. Set a maximum of five connections in the 'Transfers' window.
**Tip:** Explore additional functionalities under Cyberduck's 'File' menu, such as moving files without drag-and-drop and synchronizing folders.

### Upload Example with Cyberduck:

**Preparing Files for Upload:**
* Create a README.md or any file on your local machine to be uploaded.
* Make sure the file name does not contain spaces or special characters.

**Uploading Files:**
* Locate the 'tutorial_folder/raw_data' in your home directory within Cyberduck.
* Drag and drop DE_sample_plants.fas (or any intended file) into the 'raw_data' folder.
* Check the upload status in the 'Transfers' window until it completes.

**Verifying the Upload in the Discovery Environment:**
* Log in to the Discovery Environment and navigate to the 'raw_data' folder within 'tutorial_folder'.
* Confirm that the DE_sample_plants.fas file appears, indicating a successful upload.

### Conclusion:
With Cyberduck configured and connected to the CyVerse Data Store, you can now upload and download files with ease. Always ensure you follow naming conventions and monitor your transfer connections for optimal performance.

For any further details, refer to the [Cyverse Cyberduck manual](https://learning.cyverse.org/ds/cyberduck/) for additional guidance and troubleshooting tips.

<summary>expand</summary></details>

## 3. CyVerse Data Store: iCommands User Manual

<details>

### Introduction to iCommands:

iCommands is a comprehensive suite of command-line tools provided by the iRODS project, designed for flexible interaction with the CyVerse Data Store. This guide will cover the basics of installing and using iCommands for efficient data transfer.

### iCommands Installation:

**1. For Linux Systems:**

**CentOS:**
1. Install epel-release and configure iRODS repositories:
* sudo yum install epel-release
* sudo rpm --import https://packages.irods.org/irods-signing-key.asc
* wget -qO - https://packages.irods.org/renci-irods.yum.repo | sudo tee /etc/yum.repos.d/renci-irods.yum.repo

2. Lock iRODS packages to version 4.2.8:
* sudo yum versionlock add irods-*-4.2.8

3. Install iCommands:
* sudo yum install irods-icommands

**Ubuntu 18.04 & 20.04:**

1. Configure repository and pin iCommands version:
* wget -qO - https://packages.irods.org/irods-signing-key.asc | sudo apt-key add -
* echo "deb [arch=amd64] https://packages.irods.org/apt/ $(lsb_release -sc) main" | sudo tee /etc/apt/sources.list.d/renci-irods.list
* Set pin priority for version 4.2.8 in /etc/apt/preferences.d/irods

2. Install iCommands:
* sudo apt-get update
* sudo apt install irods-icommands

**Arm64/Aarch64 (e.g., Raspberry Pi):**

1. Use the community-compiled i-commands:
* wget https://github.com/jmscslgroup/libpanda/raw/master/scripts/irods-icommands-debs.tgz
* tar zxvf irods-icommands-debs.tgz
* cd irods-icommands-debs/
* ./install.sh

**2. For Mac OS X:**

* **Installation Steps:**
1. Download CyVerse-specific Mac OS iCommands from the provided link- https://cyverse.atlassian.net/wiki/download/attachments/241869823/cyverse-icommands-4.1.9.pkg?version=3&modificationDate=1472820029000&cacheVersion=1&api=v2
2. Open the installer via Finder and bypass security warnings in 'System Preferences' > 'Security & Privacy'.
3. Follow the installation prompts; administrator password required.
Post-installation, add iCommands to PATH in .zshrc or .bashrc file if needed.

### iCommands Configuration

**First-time Setup:**
* Open a terminal and type iinit to start the configuration process.
* Enter the following details when prompted:
  * Host name: data.cyverse.org
  * Port #: 1247
  * Username: <CyVerse UserID>
  * Zone: iplant
  * Password: <CyVerse Password>

**Verifying Installation:**
* Use ils to list contents of your Data Store home directory.
* Example: ils /iplant/home/<your_home_directory>

**Anonymous Access:**
* Username: anonymous
* Password: leave blank

### Uploading and Downloading Data

**1. Uploading Data:**
* General Steps:
1. Use iput for uploading files and folders.
2. Syntax: iput [options] /local_directory /iplant/home/<username>/destination_folder
3. Common options: -r (recursive), -P (progress), -f (force), -T (renew connection)

**2. Downloading Data:**
* General Steps:
1. Use iget for downloading files and folders.
2. Syntax: iget [options] /iplant/home/<username>/target_file /local_destination
3. Similar options as iput.
**Note:** Avoid using spaces or special characters in file and folder names.

### Additional iCommands and Tips

* **NetCDF iCommands:** For Linux, there are additional commands for NetCDF operations.

* **Frequently Used Commands:**
ihelp: Information about iCommands
ipwd: Print current iRODS directory
imkdir: Create a directory in iRODS
icd: Change iRODS directory
irsync: Sync local and iRODS directories

**Conclusion:** iCommands offers a robust and flexible way to interact with the CyVerse Data Store, especially for users comfortable with command-line tools. Ensure to follow version compatibility guidelines and handle file naming conventions carefully for seamless data management. For more detailed usage, refer to the iRODS documentation (https://packages.irods.org/) and CyVerse resources (https://docs.irods.org/master/icommands/user/#iget).

<summary>expand</summary></details>

## 4. Transferring Data with GoCommands and Command Line

<details>

### Introduction to GoCommands

GoCommands is a versatile command-line tool developed by CyVerse, designed for flexibility and ease of use. It stands out for its portability, eliminating the need for installation, and is compatible with a variety of modern operating systems including macOS, Linux, and Windows.

**Key Points About GoCommands**
  Command Line Operation: GoCommands is operated through a terminal or command line interface.
  
  Windows Compatibility: For Windows users, it's accessible via PowerShell or Command Prompt.
  
  Authentication: A valid CyVerse account or another iRODS Zone account is required for authentication.

**For detailed instructions and more information on using GoCommands, please refer to the [GoCommands User Guide](https://learning.cyverse.org/ds/gocommands/).**

<summary>expand</summary></details>


## 5. HTTP Access with WebDAV

<details>

### Overview of WebDAV

WebDAV, an extension of the HTTP protocol, facilitates remote file management and editing. CyVerse's integration of WebDAV with the Data Store enables users to access their home and public folders directly from their local computers. This integration allows for simple file transfers using web browsers and WebDAV-enabled applications like common file managers.

### Limitations of WebDAV

**File Size Considerations:**

* While there is no strict file size limit, WebDAV is optimal for files not exceeding 1 GiB. Larger files, up to 10 GiB, might still work but with varied performance.
* For handling large files or datasets, iCommands or Cyberduck are recommended for better performance.

### Accessing CyVerse Data via WebDAV Services

**1. Anonymous, Read-Only Access:**
URL: https://data.cyverse.org/dav-anon/
This service provides access to all data visible to the anonymous user, except for directories like /iplant/home and individual user home directories.

**2. Authenticated Access:**
URL: https://data.cyverse.org/dav/
After authenticating with CyVerse credentials, users can access any file or folder according to their permission levels.

**3. Access via Web Browser:**
Navigate to https://data.cyverse.org/ to access WebDAV through a browser interface.
This portal provides direct links and guidance for both anonymous and authenticated access modes.

**4. Using WebDAV in File Managers:**
WebDAV can be integrated into file managers of common operating systems, enabling drag-and-drop functionality and seamless file copying between the Data Store and local folders.

**5. Command Line Tools:**
WebDAV services can also be accessed using command line tools for users who prefer terminal-based interactions.
For more detailed instructions, tips, and troubleshooting for using WebDAV with the CyVerse Data Store, please refer to the comprehensive [WebDAV Access Guide](https://learning.cyverse.org/ds/webdav/).

<summary>expand</summary></details>

## 6. Transferring Data with SFTP via a Command Line Tool and Desktop Apps

<details>

### Overview of SFTP

Secure File Transfer Protocol (SFTP) is a widely adopted protocol for securely transferring data. CyVerse has integrated SFTP into the Data Store through SFTPGo, enhancing data accessibility across diverse computing environments. Users can interact with their home and public folders in the CyVerse Data Store using any SFTP-enabled application, including command-line tools and popular desktop applications like Cyberduck and FileZilla.

### Key Features of SFTP in CyVerse

**Secure Transfers:** SFTP provides a secure channel for transferring files, ensuring data integrity and confidentiality.

**Wide Compatibility:** SFTP can be accessed through various operating systems' built-in command-line tools, as well as third-party applications.

**Ease of Use:** The familiar interface of SFTP clients like Cyberduck and FileZilla offers a user-friendly experience for managing file transfers.

For comprehensive instructions on setting up and utilizing SFTP for data transfer with the CyVerse Data Store, including specific guidelines for popular SFTP clients, please refer to the detailed [SFTP Transfer Guide] (https://learning.cyverse.org/ds/sftp/).

<summary>expand</summary></details>

## Adding Metadata to Data in the CyVerse Discovery Environment

<details>

### Introduction

Metadata plays a crucial role in quality research, aligning with the FAIR Principles. CyVerse provides robust features in the Discovery Environment (DE) to facilitate the association of metadata with raw data. This guide will cover the process of adding metadata to files and folders, individually or in bulk, using the DE.

### 1. Adding Metadata to a Single File/Folder

**Accessing Metadata:**
  * Log into the DE and click on the Data Icon.
  * Select (checkbox) the file/folder you want to annotate.
  * Under the More Actions menu, choose 'Metadata'.

**Editing Metadata:**
  * View existing metadata displayed in Attribute, Value, Unit (AVU) format.
  * To add new metadata, click "+ Add Metadata".
  * Use the "pencil" icon to edit or the "trash can" icon to delete an entry.
  * Save your changes by clicking 'Save'.

**Note:** Write or own permission is required to edit metadata.

### 2. Adding Metadata to Multiple Files/Folders

**Using CyVerse Templates:**

  * Log in and select the file/folder in the Data window.
  * Click on Metadata, then choose View in Template.
  * Either select a template to apply and edit within the DE, or download a .csv template for external editing.

**Editing a Downloaded Template:**

  * Templates include 'blank.csv' for data entry and 'guide.csv' for instructions.
  * Fill in 'blank.csv' with file names and metadata. If using full file paths, ensure the correct directory structure is followed.
  * Save the edited template in CSV format.

**Applying Bulk Metadata:**

  * Upload the completed metadata CSV file to the appropriate folder in the Data window.
  * Select the folder containing the target files, click More Actions, and choose 'Apply Bulk Metadata'.
  * Select your uploaded metadata file to apply.

**Tips:**
  * Use absolute file paths for convenience.
  * Check the metadata application status via the notification bell in the DE.


**Additional Resources:** For more templates and resources on metadata standards, visit FAIRsharing.org.

### Conclusion:
Efficiently managing metadata in the Discovery Environment enhances the quality and accessibility of your research data. Remember to use appropriate templates and follow the guidelines for editing and applying metadata. This process not only ensures compliance with FAIR principles but also facilitates easier data sharing and publishing. For more detailed instructions or specific scenarios, refer to the Discovery Environment's [comprehensive user guide](https://learning.cyverse.org/ds/metadata/#adding-metadata-to-multiple-filesfolders-in-the-discovery-environment).

<summary>expand</summary></details>

## Detailed Guide to Sharing Data in the CyVerse Discovery Environment

### 1. Sharing a File with a Public Link

  Objective: Quickly share individual files using a Discovery Environment Public Link.

  Note: Best for small files. Avoid using for sensitive/private data.

**Steps:**

a. Login to Discovery Environment:

  * Access the Discovery Environment.
  
b. Select File for Sharing:

  * In the Data window, check the box next to the file(s) you want to share.

c. Creating a Public Link:

  * Click 'More actions'.

  * Select 'Public Link(s)'.

  * Copy the URL from the pop-up window. This link can be shared for direct file download.

d. Deactivating a Public Link:

* To deactivate, reselect the shared file(s).

* Go to 'Details' > 'Permissions'.

* Edit permissions for "cyverse-anonymous@cyverse.org" to remove the public link.

### 2. Sharing Data with Another CyVerse User or Group

  Objective: Share data with specific CyVerse users or groups with controlled permissions.

**Steps:**

a. Selecting Data for Sharing:

  * In the Data window, check the box(es) next to the file(s) or folder(s) you wish to share.

b. Granting Access:

  * Click on 'Share'.

  * Enter the CyVerse username, email, or group name of the recipient(s).

  * Under 'Permissions', select 'read', 'write', or 'own'.

  * Confirm by clicking 'Done'.

  Tip: Use 'Add to Bag' for sharing multiple items at once.

c. Sharing with the Public Community

  Objective: Make your data accessible to the public CyVerse community or the open internet.

**Steps:**

a. Granting Public Access:

  * In the Data window, select the file(s) or folder(s).

  * Under 'Share', type 'public' or 'anonymous'.

  * Assign 'read' permission only for safety.

b. Accessing Shared Public Data:

  * Go to CyVerse Data Store WebDav.

  * Use /dav for authenticated access (requires CyVerse login).

  * Use /dav-anon/ for anonymous public access (no login needed).

  Important: Never grant 'write' or 'own' permissions to 'anonymous' or 'public' users.

### Conclusion:

Sharing data in the CyVerse Discovery Environment is straightforward and allows for diverse collaboration and public contribution. Whether sharing with specific users, groups, or publicly, it's crucial to manage permissions appropriately to ensure data security and integrity. For more advanced sharing techniques or support, consult the comprehensive CyVerse User Guides.

# Analyses in the Discovery Environment (DE)

### Introduction

The Discovery Environment (DE) serves as an all-encompassing data science workbench, catering to various research computing needs. It is suitable for both interactive, small-scale research applications and large-scale projects utilizing High Throughput and High Performance Computing.

### Understanding Types of Analyses in DE

**Small Analysis:**

  Cores: 1 to 16
  
  RAM: 2 GB to 64 GB
  
  Use Cases: This category is well-suited for small-scale applications and services, teaching purposes, and analyses that require extended runtime.
  
**Moderate Analysis:**

  Cores: 32 to 256
  
  RAM: 128 GB to 1 TB
  
  Use Cases: Designed for larger applications and services that demand more computational power than what is typically available on a standard laptop.

**High Performance Computing (HPC):**

  Cores: Ranges from 1 to several thousand
  
  RAM: 2 GB to several TBs
  
  Use Cases: Ideal for tasks that are computationally intensive, such as simulations and complex data analyses.

**High Throughput Computing (HTC):**

  Cores: Hundreds to hundreds of thousands
  
  RAM: Variable, depending on the task
  
  Use Cases: Primarily focused on executing a large number of tasks efficiently, emphasizing throughput over the speed of individual tasks.

**Computing Clusters:**

  Cores and RAM: Vary depending on the specific cluster
  
  Use Cases: These clusters provide services like Jupyter/Rstudio notebook environments to multiple users, facilitating collaborative research and data analysis.

### Benefits of Using DE

* Access to a wide array of data: personal, shared, and community released/published.

* Ability to download/stream internet-accessible data into analyses.

* Scalable resources for different needs, from small to moderate tasks and beyond.

* User convenience with automated notifications for task completion.

### Step-by-Step Guide to Conducting Analyses in DE

1. Accessing DE:

  * Visit the DE portal and log in with your CyVerse credentials.

2. Selecting Analysis Type:

  * Choose the appropriate analysis type based on your project requirements. Refer to the types of analyses mentioned above for guidance.

3. Data Management:

  * Use the Data Icon to access and manage your datasets.
  * Import data from external sources or use data already available in your account.

4. Launching Analyses:

  * Select the desired application or tool based on your analysis type.
  * Configure the necessary parameters and settings for your specific analysis.

5. Monitoring and Managing Tasks:

  * Track the progress of your analyses within the DE interface.
  * Utilize the automated email notifications for updates on task completions.

6. Accessing Results:

  * Once completed, access and download your results directly from the DE.
  * Utilize DE's tools for further data exploration or analysis if needed.

### Conclusion

The CyVerse Discovery Environment provides a versatile and user-friendly platform for a wide range of research computing needs. Whether you are conducting small-scale analyses or engaging in extensive computational research, DE’s tools and resources are designed to facilitate and enhance your research process. For more detailed information or specific use-case guidance, refer to the CyVerse DE documentation and support resources.


## Logging in to the Discovery Environment (DE) of CyVerse

**1. Accessing the Discovery Environment:**

  * Open the Discovery Environment (DE) by visiting its website. You'll be greeted by the Home Dashboard.

**2. Exploring the Home Dashboard:**

  * The Home Dashboard displays links to News, recent YouTube Videos, and Featured Apps.

**3. Navigating the DE:**

  * The left side navigation menu, which can be expanded by clicking on the three bars at the top left, provides icons for different parts of the DE.

**4. Signing In:**

  * Sign in from the upper right corner by clicking the profile icon or the Login link.
  * If you're accessing the Data Store or launching an App without being logged in, a sign-in pop-up will appear.

**5. Authentication Process:**

  * Upon clicking to sign in, you'll be redirected to the Authentication Service.
  * Enter your CyVerse username and password.
  * For new users or those who forgot their password, create an account or reset your password at CyVerse User Portal.

**6. Returning to DE:**

  * After logging in, you'll be directed back to the Home Dashboard.
  * If you were on the Apps or Data pages during login, you will return to that specific page.

**7. Taking the DE Tour:**

  * For a quick overview of the DE's features, click on the help icon in the left sidebar and select "Product Tour".


## Using Apps in the CyVerse Discovery Environment (DE)

### Introduction
The Discovery Environment (DE) offers a vast selection of applications (apps) for data analysis. These apps range from simple utilities to complex analysis tools, catering to diverse research needs.

### Launching Apps in DE
Automated Notifications: After starting an app, you can log out or navigate elsewhere; you'll receive an email notification when the task completes.

### Browsing Apps

**Accessing Apps:** 
  * Click the Apps icon in the DE's left sidebar. If prompted, log in to view the apps.
  * Once logged in, you'll see a screen displaying various apps.

### Sorting and Filtering Apps

**Sorting Apps:**
* Sort apps in ascending or descending order by app name, integrator, or average rating by clicking the column headings.

**Navigating Apps:**

* Move between pages and adjust the number of apps per page using the < or > controls at the page's bottom.

**Featured and Public Apps:**

* By default, "Featured Apps" (interactive) are displayed.
* All "Public Apps" are available for your use.

### Selecting App Subsets

**Choosing App Subsets:**

  * Select different app subsets from the primary filter in the upper left corner of the Apps view.
  * The selected subset is highlighted in gray.

**Types of App Subsets:**

  * Apps under development, Favorite apps, My public apps, Shared with me, High-Performance Computing apps, and Browse All Apps.

### Applying Filters

**Filter Types:**

* Choose from app filters like HPC, DE, VICE, and OSG in the Filter control (upper right corner).

### Viewing App Details

**Accessing Details:**

  * Select an app by clicking its checkbox. Click 'Details' for more information, including descriptions and usage statistics.

**Interacting with Details:**

  * Add to favorites with the Heart icon.
  
  * Share the app using the Link icon.
  
  * Rate the app using the Stars icon.
  
  * View tools used by the app under "Tools used by this App".

### About VICE Apps

  * Interactive Apps: VICE apps include GUIs or IDEs like Jupyter, RStudio, and remote desktops.
  
  * Access Requirements: Request and gain approval for VICE app access via the CyVerse User Portal.

### Advanced Features

  * Integration and Containers: DE supports integrating various apps, creating and running containers.
  
  * API Usage: Use Application Programming Interfaces for backend access to CyVerse services.
  
  * Additional Resources: Consult the Developer Manuals, Extending VICE Apps, and Powered By documentation for detailed guidance.


## Managing Analyses in the CyVerse Discovery Environment (DE)

### Overview
An analysis in DE is the outcome of an executed app, containing details like a unique ID, launch date, input files, and more. DE keeps a record of all your analyses for easy tracking and management.

### Browsing and Checking Analysis Status

**Accessing Analyses:**

  * Open the Analyses view by clicking the analyses icon on the left sidebar.
  * The most recent analyses appear at the top of the list.

**Sorting Analyses:**

  * Sort analyses by Name, Start date, End date, or Status by clicking on the respective column headers.

**Understanding Analysis Status:**

  Submitted: Queued for execution.
  Running: Currently processing. For VICE apps, access your interactive app via the notification icon or the link-out icon.
  Completed: Finished with logs and results stored in the data store.
  Canceled: Analysis stopped by the user.
  Failed: Encountered an error during execution.
  
**Filtering Analyses:**

  * Filter by user (‘My analyses’ or ‘Shared with me’) and app type (HPC, DE, VICE, OSG) using dropdown menus.

**Accessing Outputs:**

  * Click the output folder icon next to an analysis to view its results.

### Relaunching an Analysis

**Procedure:**

  * Select an analysis from history.
  
  * Click the relaunch icon.
  
  * Modify any parameters as needed and launch the app again.

### Viewing Analysis Details

  * Click 'Details' or the information icon to view parameters and other specific details of an analysis.

### Sharing an Analysis

  * Use the 'Share' or 'Add To Bag' buttons to share an analysis and its results with another CyVerse user.

### Additional Analysis Actions

  * More Actions: Includes options to view output folder, relaunch, rename, update comments, view interactive analyses, extend time limit, terminate, delete, and add to a bag for sharing.

### Using CPUs Efficiently: Best Practices

1. Requesting Fewer CPUs:

  * Modify the "Maximum CPU Cores" in "Advanced Settings" during analysis submission.

  * Default is 4 CPUs. Choose 1 for single-threaded apps or more based on the app's requirements.

2. Terminate Completed Analyses:

  * Promptly terminate an analysis once completed to conserve CPU hours.

  **Note:** Inactive but running analyses consume CPU hours quickly.

  
## Interactive Analysis in the CyVerse Discovery Environment (DE) Using VICE

### Overview
VICE (Visual Interactive Computing Environment) is a key component of CyVerse's DE, providing access to various interactive applications including Terminal Access, Integrated Development Environments (IDEs), Virtual Desktop Environments, and Web Server Applications.

### Categories of Interactive Applications in VICE

1. Terminal Access: Direct command line access for advanced users.

2. Integrated Development Environments (IDEs): Environments like Jupyter, RStudio, Visual Studio Code.

3. Virtual Desktop Environments:

    Kasm Based: Browser-based desktops.
    
    Xpra Based: Lightweight desktops.
    
    Geospatial (QGIS/GRASS-GIS): Specialized for geospatial data.

4. Web Server Applications: Includes StreamlitApps, ShinyApps, WebGL, HTML5, etc.

### Getting VICE Access

  Requirement: Must have an email address from an educational or government organization.
  
  Request Process: Go to the User Portal and Services, find DE VICE, and click REQUEST ACCESS. Provide non-technical details of your intended use.

### Launching Applications in VICE

1. Instant Launching:

  * Pre-configured apps with a single click launch.
  
  * Default settings: 4-cores, 16 GB RAM.

2. Steps to Launch an App:

  * Log in to the Discovery Environment.
  
  * Navigate to Apps and select a Featured App.
  
  * Adjust settings in "Analysis Info" and "Advanced Settings".
  
  * Launch the application.

3. Monitoring:

  * Check the Analyses view for status updates.

4. Accessing Data in VICE:

  * Use methods like curl or direct access to Data Store paths (work/home/cyverse_username/ and work/home/shared/).

5. Working with Files:

  * For many small files, consider keeping data compressed in the Data Store and using cp to copy to ~/work.

6. Using Git and GitHub:

  * Use GitHub CLI for repository management.
  
  * Recommended to clone repositories into ~/work.

### Instant and Quick Launches

  * Instant Launches: Single-click launches available from the Home tab.

  * Quick Launches: Direct URLs for sharing pre-configured apps.


### Conclusion

Interactive Analysis in DE using VICE provides a versatile and user-friendly platform for a wide range of computing needs, from development to data analysis. With various applications and easy access methods, VICE enhances the research capabilities within the CyVerse ecosystem.


## Sharing and Using Bags in the CyVerse Discovery Environment

The CyVerse Discovery Environment (DE) offers robust features for sharing data, apps, and analyses. Central to this is the "bag" feature, a versatile tool for compiling and sharing multiple resources with other CyVerse users. Whether you're collaborating on a project or distributing your findings, the DE makes it easy and efficient. For detailed instructions on how to effectively use this feature, click [here] (https://learning.cyverse.org/de/bags/#using-a-bag-to-share-or-download-in-the-discovery-environment) to access a comprehensive guide.

# Quick Reference and Additional Resources

As you delve into the diverse functionalities and capabilities of the CyVerse Discovery Environment, you might find these additional resources and sections beneficial for further exploration and learning:

Quick Starts: Ideal for getting up to speed with essential features and tools. [Explore Quick Starts](https://learning.cyverse.org/vice/quick-rstudio/)

Cloud Services: Learn about integrating and utilizing cloud-based services in your projects. [Discover Cloud Services](https://learning.cyverse.org/cloud/)

For the Classroom: Tailored resources for educators and students to incorporate into classroom settings. [Access Classroom Resources](https://learning.cyverse.org/vice/teaching/)

Develop: A section dedicated to developers interested in extending and enhancing CyVerse tools. [Explore Development Tools](https://learning.cyverse.org/de/create_apps/)

Science Tutorials: Comprehensive tutorials covering a wide range of scientific applications and scenarios. [Browse Science Tutorials](https://learning.cyverse.org/tutorials/)

CyVerse Workshops: Information and materials from past and upcoming CyVerse workshops. [Join CyVerse Workshops](https://learning.cyverse.org/workshops/)

Reference: A repository of detailed documentation and reference materials. [Access Reference Materials](https://learning.cyverse.org/workshops/)
