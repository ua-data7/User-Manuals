<img align="right" src="https://user-images.githubusercontent.com/131712709/235216212-9be492ec-eba0-41c0-b643-863eee12199b.png" width="350">

<div id="user-content-toc">
  <ul>
    <summary><h1 style="display: inline-block;">CYVERSE HEALTH- USER MANUAL</h1></summary>
  </ul>
</div>
&nbsp; 

<p align="center">
<img src="https://github.com/ua-data7/User-Manuals/blob/main/images/Cyverse_Health/Titlepic.png?raw=true" width="360">
 </p>
 
<p align="center">
<img src="https://github.com/ua-data7/User-Manuals/blob/main/images/Cyverse_Health/cover%202.jpg" width="1080">
</p>
&nbsp;  

# OVERVIEW

## Soteria: A Comprehensive Overview

Soteria stands as a pivotal innovation in secure data analysis, providing a robust platform specifically designed for research involving Personally Identifiable Information (PII) and Protected Health Information (PHI). Recognizing the critical importance of privacy and security, Soteria offers a specialized enclave that champions compliance, control, and confidentiality throughout the research process.

Key features of Soteria include its stringent access protocols, ensuring that only authorized researchers can engage with the sensitive data within. This is overseen by the Soteria Access & Governance Committee, a dedicated body ensuring adherence to legal and ethical standards. The platform's unique blend of resources and tools, including the cutting-edge Soteria HPC, External Data Transfer, and Posit Connect Health, are customized to meet the demands of secure, efficient, and collaborative research.

By encapsulating all these features, Soteria emerges as more than just a platform; it's a safeguard for sensitive information, a facilitator of interdisciplinary research, and a beacon of trust in the realm of data security.

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


# Getting Started with CyVerse Health

Before diving into the specific features and capabilities of CyVerse Health, users must first gain access to the overarching Soteria platform. Below, we outline the necessary steps to establish this foundational access.

## Request Access to Soteria

<details>
<summary>Instructions to get access</summary>

1.  Establish a primary PI or sponsoring faculty member and have them indicate that you are a team member on Soteria.
2.  Open <https://soteria.arizona.edu/> and click **Request Access**.


<p align="center">
<img src="https://user-images.githubusercontent.com/131712709/235225922-d1a9630b-2dac-4abf-afc0-64c80a1cd435.png" width="380">
</p>


3.  Fill out the form with your user and project information. Once the form has been submitted, you will receive an automated email indicating completion of the request.
4.  Once approved, you will receive a secondary automated email, UA Soteria Access Request Approved indicating required trainings. Log into Edge Learning (<https://edgelearning.arizona.edu/>) to sign up and complete all of the required trainings.

### Download and Set up Cisco VPN

1.  Download the VPN software by following the link (<https://vpn.arizona.edu/+CSCOE+/logon.html#form_title_text>) . You will be prompted to log in. Use the default connections. Enter your NetID, Password and NetID +Method (ex: "push").

<p align="center">
<img align="center" src="https://user-images.githubusercontent.com/131712709/235227282-ac99a356-c4ec-4fe4-819d-50adffddec75.png" width="330">
</p>

2.  Follow the prompts to download and install Cisco AnyConnect VPN.

<p align="center">
<img align="center" src="https://user-images.githubusercontent.com/131712709/235227654-0ef0b5b4-a804-420b-a224-9d1201fe2da8.png" width="168">
</p>

<p align="center">
<img align="center" src="https://user-images.githubusercontent.com/131712709/235511927-5b353b56-1c23-43aa-bec3-e65d7ffb2028.png" width="600">
</p>

3.  Open Cisco AnyConnect VPN on your desktop.
4.  The first connection must be to: vpn.arizona.edu. Type into the pop-up and click **connect**.

<p align="center">
<img align="center" src="https://user-images.githubusercontent.com/131712709/235229386-dc171283-9707-4e97-ba2d-e9fdc3750877.png" width="350">
</p>

5.  Sign in as before, using the default group. Enter your NetID, Password and NetID +Method (ex: "push").

<p align="center">
<img align="center" src="https://user-images.githubusercontent.com/131712709/235229698-895b0740-954d-40f3-bcb8-d2a717439126.png" width="350">
</p>

6.  Click **Disconnect**

<p align="center">
<img align="center" src="https://user-images.githubusercontent.com/131712709/235229897-48add640-9da0-4ebd-864a-b0f44f9bd959.png" width="350">
</p>

You are now ready to connect to your Soteria VPN.

### Connect to Soteria VPN

1.  If it does not auto-populate, connect to the Soteria VPN using: vpn.arizona.edu/soteria. Again, enter your NetID, Password and NetID +Method (ex: "push") to sign in.

<p align="center">
<img align="center" src="https://user-images.githubusercontent.com/131712709/235230138-0aa04bd3-7b8f-4a3f-bf1d-076766e8db94.png" width="350">
</p>

2.  Accept the pop-up notification. The Cisco Icon in the system tray (bottom right) of your desktop, will now display a lock, indicating a successful connection.

</details>

## Setting Up and Accessing Your CyVerse Health Account

### Step 1: Creating Your CyVerse Account

1. Navigate to the [CyVerse User Portal](https://user.cyverse.org/).
2. Click the "Sign Up" button to initiate the registration process.
<p align="center">
<img align="center" src="https://github.com/ua-data7/User-Manuals/blob/main/images/Cyverse_Health/Signup1.png" width="650">
</p>
3. You will be prompted to enter personal and contact information, as well as your intended use for CyVerse's services. For expedited approval, use an institutional email address (e.g., addresses ending in .edu, .org, or .gov).
<p align="center">
<img align="center" src="https://github.com/ua-data7/User-Manuals/blob/main/images/Cyverse_Health/profileindo.png" width="650">
</p>

4. Complete the registration form and submit it.Ensure that JavaScript is enabled in your browser and any pop-up blockers are disabled to avoid interruptions in the process.

5. Check your email inbox for a confirmation message from CyVerse. Click the link in the email to confirm your account.

6. Add your ORCID to your CyVerse User Profile. If you don’t have an ORCID, visit https://orcid.org to create one

<p align="center">
<img align="center" src="https://github.com/ua-data7/User-Manuals/blob/main/images/Cyverse_Health/orcid.png" width="650">
</p>

**Important:** The account confirmation email should arrive shortly after you submit your registration. If it doesn't appear in your inbox, ensure you check your spam folder.

### Step 2: Registering for Specific CyVerse Health Services

1. Log in to your account on the CyVerse User Portal.
2. Navigate to the dashboard and locate the "My Services" section.
3. Click the 'Request Access' button adjacent to the specific service(s) you need, such as VICE.
4. Fill in any required information, including non-technical details about your intended use of the services. Providing links to external resources (e.g., a workshop or lab website) or mentioning a funding agency can be beneficial.
5. Submit your request. You will receive an email notification when access to the service is granted, which may take up to 24 hours.

**Note:** VICE access requires additional verification due to its vulnerability to cryptocurrency miners. Ensure you use an institutional email address and provide detailed information about your intended use.

### Step 3: Beginning Your Work on CyVerse Health

Once your account is set up, and you have access to the necessary services, you can start your projects on CyVerse. Utilize the Learning Center for helpful guides and tutorials on using different tools and services effectively. These resources are designed to assist you in understanding specific tasks or in-depth functionalities of CyVerse platforms.

**Remember:** Keep your account details secure, and ensure you log out from shared or public computers to maintain the security of your data.

## Getting Started with the Discovery Environment Interface

<details>

### Registration and Login:

1. Open your web browser and navigate to the CyVerse Discovery Environment website.

2. If you're a first-time user, locate and click on the 'Sign Up' button. Fill in the required details, including your email address, desired username, and password, following any provided guidelines to ensure account security. Once registered, verify your account as instructed in the confirmation email you receive.

3. For returning users, click the 'Login' button on the homepage. Enter your username and password in the respective fields and click 'Submit' to access your account.

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

