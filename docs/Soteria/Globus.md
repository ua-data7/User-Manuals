
## Overview

Welcome to the Globus Data Transfer with GridFTP, specifically tailored for the Soteria environment. Within Soteria's UA HPC HIPAA Filesystems, data movement becomes a breeze with the powerful capabilities of Globus and GridFTP.

In this manual, we'll explore how GridFTP, an extension of the standard File Transfer Protocol (FTP), elevates data transfer to new heights. Its focus on high-speed, reliable, and secure transmission perfectly complements the demands of Soteria's environment. With Globus as your platform of choice, you'll find endpoints to be the key to effortless data transfers.

Whether you're involved in research, data analysis, or IT management, understanding the benefits of GridFTP through Globus will empower you to handle large-scale data transfers with ease. Say goodbye to complex transfer processes and embrace a seamless approach to sharing data across all clusters in the shared storage.

Let's embark on this journey of efficient data transfer within the Soteria environment, where GridFTP and Globus come together to make your data management tasks a whole lot smoother.

## Accessing Globus

Follow the [link](https://public.confluence.arizona.edu/display/UAHPC/Globus) for a detailed step by step guide to access globus.\
\
This will take you through the standard university WebAuth login process. Once you successfully log in, you will be placed in a File Manager window. The various steps for setting up endpoints, initiating transfers, and viewing a transfer's progress can be found in the sections below.\
\

## Globus Connect Personal

To transfer files to/from your personal computer with Globus, you'll need to have a local endpoint set up. In case of Soteria, the endpoint is: **UA HPC HIPAA Filesystems**.\
\
This can be achieved using Globus Connect Personal. Official documentation on how to install the relevant software and configure a local endpoint can be found in [Globus' offical how-to documentation](#0){style="font-size: 11.4pt;"}. An overview is shown [here](https://public.confluence.arizona.edu/display/UAHPC/Globus) for Mac, Linux, and Windows below.

## Accessing HPC Storage Endpoint

To access the HPC Storage Endpoint in the Soteria environment, follow these steps:

[**Step 1:**]{.underline} Locate the Collections Tab After logging into Globus, navigate to the "Collections" tab.

[**Step 2:**]{.underline} Search for UA HPC Filesystems In the search field, type "UA HPC Filesystems" and select the relevant result.

![](images/Globus/1.PNG){fig-align="center"}

**S[tep 3:]{.underline}** Open the HPC Storage Endpoint Click "Open in File Manager" to access your HPC files. The default location will be your "/home" on HPC.

![](images/Globus/2.PNG){fig-align="center"}

[**Step 4:**]{.underline} Navigating HPC Files Navigate through directories by double-clicking on folders or by entering a full path in the Path search bar and hitting "Enter." This method allows access to any "/xdisk" or "/groups" directories you have permissions for.

![](images/Globus/3.PNG){fig-align="center"}

## Making Data Transfers

To initiate data transfers between endpoints using the File Manager window, follow these steps:

[**Step 1:**]{.underline} Access the File Manager Tab Go to the "File Manager" tab in the Globus web application. Ensure you have dual-panel mode enabled (click the upper right-hand corner with the red arrow) to open two endpoints simultaneously.

![](images/Globus/4.PNG){fig-align="center"}

[**Step 2:**]{.underline} Open the First Endpoint Click the Search bar on the left-hand side and search for your first endpoint (e.g., UA HPC Filesystems). Click the result to open it.

![](images/Globus/5.PNG){fig-align="center"}

[**Step 3:**]{.underline} Open the Second Endpoint To open a second connection, click the Search bar on the right-hand side. Search for your next endpoint (e.g., a personal endpoint) or access recently used endpoints and collections under the "Recent" and "Your Collections" tabs. Click the result to open the second endpoint.

![](images/Globus/6.PNG){fig-align="center"}

![](images/Globus/7.PNG){fig-align="center"}

[**Step 4:**]{.underline} Start the Transfer Select the item(s) you want to transfer from the first endpoint, then click the "Start" button to initiate the transfer to the second endpoint.

![](images/Globus/8.PNG){fig-align="center"}

## Monitoring Your Transfers

After initiating a transfer, a green box will appear confirming the request. To monitor your transfers:

[**Step 1:**]{.underline} Access the Activity Panel On the left-hand side of the page, access the "Activity" panel. This will display active and past transfers along with their status.

![](images/Globus/9.PNG){fig-align="center"}

[**Step 2:**]{.underline} View Transfer Details To view additional details about your transfers, click the "\>" symbol next to the target task on the right-hand side. This will provide more information about the ongoing or completed transfer.

![](images/Globus/10.PNG){fig-align="center"}

[**Step 3:**]{.underline} Cancel a Transfer If needed, you can cancel a transfer by clicking the "×" symbol on the right.

[**Step 4:**]{.underline} Receive Transfer Status Email Once your transfer is completed, you will receive an email with its status.

Congratulations! You have now learned how to access the HPC Storage Endpoint and perform data transfers using Globus. With this powerful tool, managing data within the Soteria environment becomes efficient and straightforward. Happy data transferring!
