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

**Choosing a Method:** Consider file size, technical comfort, and specific project needs. <ins>*For larger files,*</ins> prefer Cyberduck, iCommands, or SFTP. <ins>*For simplicity*</ins>, use the DE or Cyberduck. <ins>*For automation or programming environments*</ins>, opt for iCommands or GoCommands.

## Managing Data in the Discovery Environment

The Discovery Environment (DE) offers a comprehensive solution for data management tasks within CyVerse, from initial upload to final publication.

* **Data Lifecycle Management:** Perform a variety of tasks like uploading, metadata addition, analysis, sharing, and publication.

* **Seamless Integration:** The Data Store is ubiquitous across CyVerse, allowing effortless file access and management from any platform.


**Remember:** The Data Store isn't a separate entity but a foundational service across CyVerse, granting you universal access to your data.
