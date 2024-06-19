![](../assets/cover.png){width="340"}

<br>

![cy_h-banner](../assets/Cyverse_Health/CyVerse_Health_Banner.png)

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

Once logged in, take a moment to view the main dashboard. This central hub provides a snapshot of the tools and features at your disposal within the **Discovery Environment (DE)**.

1. Locate the *Search Bar* positioned at the top of the page. Here, you have the ability to perform integrated searches across different data points:
    1. Click on the dropdown menu adjacent to the search bar to filter your search criteria by *Data*, *Apps*, or *Analyses*.
    2. Enter your query into the search field and press *Enter* to execute the search. Review the returned results, accessible by navigating through the tabs corresponding to the categories mentioned above.
2. Familiarize yourself with the quick access icons, often found near the search bar:
    1. Look for a 'bag' or cart icon, symbolizing a space where you can aggregate items for download or sharing. It functions similarly to an online shopping cart, allowing you to organize data or apps you wish to further interact with.
    2. The 'notifications' bell icon is your go-to for updates on the platform. Clicking this will show you a history of your activities, including analysis statuses, data sharing updates, and general account activity.
3. Navigating the Sidebar Menu:
    1. Shift your attention to the left-hand sidebar, known as the **DE Menu**. This is your primary navigation tool for the platform's various sections. If the sidebar is collapsed, you can expand it for more detailed descriptions by clicking the expand button (three line icon).
4. Explore the following key areas by clicking on each respective icon or text:

  ![DE Menu](../assets/Cyverse_Health/cyverse_health_04.png){width="200", align=left} 
    
  - ![](../assets/Cyverse_Health/de/menu_items/homeIcon.svg){width=20} **Home/Dashboard:** Your main control panel that may display summary widgets, quick links to recent activities, or educational content such as tutorials and webinars.
  - ![](../assets/Cyverse_Health/de/menu_items/dataIcon.svg){width=20} **Data:** This interface connects you to the Data Store. Here, you can manage your files, including uploading, downloading, organizing, and sharing data. You'll have access to your personal storage space and shared directories.
  - ![](../assets/Cyverse_Health/de/menu_items/appsIcon.svg){width=20} **Apps:** Discover various applications, including VICE (Visual Interactive Computing Environment) apps for interactive computing sessions. You can browse, search, and launch these applications based on your research needs.
  - ![](../assets/Cyverse_Health/de/menu_items/analysisIcon.svg){width=20} **Analyses:** View and manage your computational tasks. This section logs your history of analysis jobs, allowing you to monitor current processes, review completed ones, and access resulting data.
  - ![](../assets/Cyverse_Health/de/menu_items/webshellIcon.svg){width=20} **Cloud Shell:** Access a Linux shell environment directly within the DE. This feature enables advanced users to perform command-line operations without leaving the platform.
  - ![](../assets/Cyverse_Health/de/menu_items/teamsIcon.svg){width=20} **Teams:** Create and manage collaboration groups. Teams allow you to group together with other users for easier sharing of data, analyses, and other collaborative efforts.
  - ![](../assets/Cyverse_Health/de/menu_items/bank.svg){width=20} **Collections:** Explore public collections of data and apps curated by other users or the CyVerse team. This resource can be invaluable for finding information relevant to your studies.
  - ![](../assets/Cyverse_Health/de/menu_items/helpIcon.svg){width=20} **Help:** Access various support materials, including FAQs, guides, and contact information for direct assistance from the CyVerse support team.

   
## Data Management

### CyVerse Data Store

The CyVerse **Data Store (DS)** is an integrated data management solution, ensuring data remains FAIR - Findable, Accessible, Interoperable, Reusable. Access your files across all CyVerse platforms, utilizing features that maintain data integrity and value.

Return to the ![](../assets/Cyverse_Health/de/menu_items/dataIcon.svg){width=20} **Data** section from the DE Menu to explore further. Within this space, you'll interact with several specific areas:

![data_dropdown](../assets/Cyverse_Health/cyverse_health_05.png){width="200", align=left} 

  1. :material-home: **Your Personal Folder:** Navigate to your home directory. Use this private space to store your data files and analyses. You can create sub-folders for better organization.
  2. :material-folder-account: **Shared With Me:** Click on this folder to view items that other users have shared with you. This collaboration feature is crucial for team projects and shared research initiatives.
  3. :octicons-people-16: **Community Data:** Explore data shared publicly by other CyVerse users. This repository can contain valuable resources for your research.
  4. :fontawesome-solid-trash: **Trash:** View recently deleted items. You may have the option to restore files from here if necessary.

### Obtaining Data from the Community Data Folder

![comm_folder](../assets/Cyverse_Health/cyverse_health_06.png){width="300", align=left}

The **Community Data** folder is not only where you can find public data, more importantly, the **Community Data folder is where you are gonig to find data shared with you and your team from official sources such as <u>[Banner Health](https://www.bannerhealth.com/patients/patient-resources/privacy)</u>, the <u>[UArizona Cancer Center](https://cancercenter.arizona.edu/)</u> and <u>[UArizona's Center for Biomedical Informatics and Biostatistics (CB2)](https://cb2.uahs.arizona.edu/)</u>.** 

!!! warning "Data and folders originating from the above distributors (e.g., Banner Health) will be visible and available to specific recepients only once recepients gain approval from the [IRB](https://research.arizona.edu/compliance/human-subjects-protection-program/about-the-irb)."

!!! failure "CAUTION: please <u>DO NOT</u> make copies of the raw data originating from the above distributors."

### Navigating Data Transfer Options

There are a number of ways to transfer data in and out of the Data Store.

- [![deIcon](../assets/Cyverse_Health/de/logos/deIcon.svg){width=20} **Discovery Environment (DE):**](#data-transfer-discovery-environment)
    - Web-based: Simple, no third-party installation
    - Data Limit: Up to 2GB per file for uploads, unlimited for import.
- [:material-duck: **Cyberduck:**](#data-transfer-cyberduck)
    - Desktop Application: Requires installation and SFTP setup.
- [:material-console-network: **SFTP Clients:**](#data-transfer-sftp)
    - Command-Line based, can be used to transfer data from the computer to the DE or between HPC and the DE.
- **iCommands and GoCommands:**
    - Support for iCommands and GoCommands to be available soon.

!!! note ""

    #### <h4 style="color:#0a71ac">![deIcon](../assets/Cyverse_Health/de/logos/deIcon.svg){width=20} Data Transfer: Discovery Environment</h4>

    The Discovery Environment (DE) interface is a user-friendly, web-based portal designed for seamless management of your data within the CyVerse Data Store. This chapter provides a detailed guide on utilizing DE for various data management tasks.

    **1. Creating Folders**
    
    1. Navigating to *Data* 
    2. create a new one by clicking the :material-folder-plus: *Folder* button. 
    
    **2. Uploading Files:**

    1. Click :material-upload: *Upload* and choose 'Browse Local' to select files from your computer.
    2. For files via URL, select 'Import by URL,' paste the link, and click 'Import'.
    3. An automated notification confirms your upload is in the queue. To check progress, click 'Upload' > 'View Upload Queue.'

    !!! warning "Direct browser uploads are limited to files <2GB. For larger transfers, consider using SFTP."

    !!! tip "Tips"
        
        - **Drag-and-Drop:** Alternatively, drag files from your computer directly into the DE browser window. This action also initiates the upload process.
        - **Background Uploading:** You're free to navigate away or log out during URL imports; a notification will inform you upon completion.

    **3. Downloading Data**

    1. Locate and select the file(s) to download by clicking the adjacted checkbox(es).
    2. Click 'More Actions' > 'Download' to save to your local machine.

    !!! warning "Direct downloads via DE are suitable for files <2GB. For larger transfers, consider using SFTP."

    **4. Deleting Data**

    1. Selection file(s) for Deletion by clicking the adjacted checkbox(es).
    2. Click 'More Options' (ellipsis, on the right) and select 'Delete.'
    3. A notification confirms the deletion.

    !!! :warning: **Warning**  Deleted items move to 'Trash.' They remain recoverable until you empty the 'Trash' folder, which then reflects on your storage quota.


!!! warning ""

    #### <h4 style="color:#f5b822">:material-duck: Data Transfer: Cyberduck</h4>

    !!! warning "Access to the CyVerse Health Data Store through Cyberduck is only possible once connected to the Soteria VPN."
    
    Cyberduck is a versatile third-party tool that facilitates easy transfer of data between your local computer and the CyVerse Data Store. It's especially useful for transferring large or multiple files and offers functionalities like file renaming and browsing through shared or public Data Store locations.

    **1. Setting Up Cyberduck**

    - **Downloading and Installing Cyberduck:** 
        - Go to the [Cyberduck website](https://cyberduck.io/download/) and download the application compatible with your operating system.
        - Install Cyberduck following the provided instructions.
    - **Configuring Cyberduck for CyVerse Health using SSH:**
        - Open CyberDuck and click the "Open Connection" button
        - Select "SFTP (SSH File Transfer Protocol)"
        - In the "Server" field, add `data.soteria.arizona.edu`
        - Add your UAarizona username and password
        - Click "connect"
        - You should now be able to access your files and view the DS contents from Cyberduck 

    **2. Transferring Data Using Cyberduck**
    
    - **Uploading to the Data Store:**
        - Double-click the Soteria Data Store bookmark (`data.soteria.arizona.edu) to connect.
        - Drag files/folders from your local machine into the Cyberduck window. You can also create a new folder via the 'File' menu.
        - The 'Transfers' window will display the progress. Wait until the upload is complete.
        - :warning: **Warning:** Avoid using spaces or special characters in file/folder names (e.g., `~ `` ! @ # $ % ^ & * ( ) + = { } [ ] | : ; " ' < > , ? / \`).
    - **Downloading from the Data Store using Cyberduck**
        - Double-click the Soteria Data Store bookmark (`data.soteria.arizona.edu) to connect.
        - Drag files/folders from the Cyberduck window to a local directory.
        - The 'Transfers' window will show the progress. Monitor until the download finishes.
        - :warning: **Caution:** Manage the number of connections to avoid overloading the system. Set a maximum of five connections in the 'Transfers' window.
        - :fire: **Tip:** Explore additional functionalities under Cyberduck's 'File' menu, such as moving files without drag-and-drop and synchronizing folders.

!!! example ""
    ####  <h4 style="color:#7C4DFF">:material-console-network: Data Transfer: SFTP</h4>
    
    !!! warning "Access to the CyVerse Health Data Store through SFTP is only possible once connected to the Soteria VPN."

    [Secure File Transfer Protocol (SFTP)](https://en.wikipedia.org/wiki/SSH_File_Transfer_Protocol) is a widely adopted protocol for securely transferring data. CyVerse has integrated SFTP into the Data Store through SFTPGo, enhancing data accessibility across diverse computing environments. Users can interact with their home and public folders in the CyVerse Data Store using any SFTP-enabled application, including command-line tools and popular desktop applications like Cyberduck and FileZilla.

    - **Key Features of SFTP in CyVerse**

        - **Secure Transfers:** SFTP provides a secure channel for transferring files, ensuring data integrity and confidentiality.
        - **Wide Compatibility:** SFTP can be accessed through various operating systems' built-in command-line tools, as well as third-party applications.
        - **Ease of Use:** The familiar interface of SFTP clients like Cyberduck and FileZilla offers a user-friendly experience for managing file transfers.

    - **Connecting via SFTP**

        - Users can connect via SFTP by opening a Terminal whilst connected to the soteria VPN and executing the following command `sftp <UA username>@data.soteria.arizona.edu`
        - The prompt should now change from `$` to `sftp>`
          ```
          $ sftp cosi@data.soteria.arizona.edu
          cosi@data.soteria.arizona.edu's password:
          Connected to data.soteria.arizona.edu.
          sftp>
          ```
        - Useful SFTP commands:
          - `ls`: _lists_ the contents of a directory
          - `cd <dir>`: change directory (`<dir>` = name of directory; use `..` to change directory to directory above)
          - `put <xxx>`: uploads a folder/file from your local computer to the CyVerse Health DS (replace `<xxx>` with the folder name)
          - `get <xxx>`: download a folder/file to your local computer from the CyVerse Health DS (replace `<xxx>` with the folder name)
---

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
