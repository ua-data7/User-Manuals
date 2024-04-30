![](../assets/cover.png){width="340"}

---

# **The Secure Research Enclave and HPC Cluster**

This user manual will guide you through the high-performance computing (HPC) features and functionalities of Soteria. The HPC cluster is equipped with multiple compute nodes (CPU) and two GPU nodes available for specific needs.

To access Soteria, you can utilize the OnDemand graphical user interface, which provides a user-friendly interface for seamless interaction with the enclave.

We hope this manual assists you in making the most of Soteria's capabilities while ensuring the confidentiality and security of your research data.

---

## Prerequisites: Accessing Soteria and Cluster Resources

### Accessing the Soteria Enclave

!!! Info "*Please refer to the [Obtaining Soteria Access via VPN](access_vpn.md) for Soteria access details.*"

**Trainings**: Once your Soteria request form has been reviewed and approved, you will receive an email with the subject "*UA Soteria Access Request Approved*". This email will contain the next steps to take, including detailed instructions to get Soteria access and establish a VPN connection.

!!! Warning "Required Trainings"

    The trainings that Soteria requires completion of are:

    - HIPAA Essentials
    - UA Information Security Awareness Training
    - Insiders Threat Training

        These can be accessed at [uaccess.arizona.edu](https://uaccess.arizona.edu/) or [edgelearning.arizona.edu](https://edgelearning.arizona.edu/).

**Access to Soteria**: After completing the required trainings, you will be notified via email when you have been granted access to the Soteria VPN. The Soteria VPN is crucial for maintaining HIPAA compliance and distinguishes Soteria usage from standard HPC clusters. Please note that Soteria access can only be established when connected to the VPN. 

- [Obtaining the Cisco VPN](access_vpn.md/#downloading-cisco-vpn) 
- [Connecting to the Soteria enclave](access_vpn.md/#connecting-to-the-soteria-enclave)

!!! Info "Additional Instructions" 
    
    Ensure that the computer you will use to access Soteria services meets the following requirements:

    - Keep your Operating System and applications updated.
    - Use strong passwords (easy to remember, multiple character, letter, number combinations).
    - Do not use a shared computer with other users.
    - Maintain up-to-date antivirus software.

### Cluster Resources

Please refer to the regular [HPC documentation](https://uarizona.atlassian.net/wiki/spaces/UAHPC/overview) to learn how to use the HPC system. During the early testing phase, the time and space allocations will be similar to those of the HPC clusters, with a time allocation of 150,000 hours.

The Soteria cluster consists of the following resources:

- **Compute**:
    - 4 Standard CPU nodes (`r1u26n1`, `r1u27n1`, `r1u28n1`, `r1u29n1`)
        - Each CPU node has 94 cores and 512GB RAM memory available.
    - 2 GPU Nodes (`r1u30n1`, `r1u32n1`)
        - Each GPU node has access to 94 cores and 512GB RAM memory available.
        - Access to 4 V100 GPUs.
- **Storage**: 
    - Your Soteria account will come with space available in the `/home` and `/groups` directories, where you can store your research data. Currently, these directories do not have a quota limit.

---

## Accessing the HPC Soteria Enclave and GUI Applications

!!! Info "*To access the HPC Soteria enclave, please ensure that you are connected to the Soteria VPN as explained in the previous section.*"

To access GUI applications, follow these steps after connecting to the Soteria VPN:

1. Open your preferred web browser.
2. Visit the following URL: [**https://ondemand-hipaa.hpc.arizona.edu**](https://ondemand-hipaa.hpc.arizona.edu/). Log in using your UA credentials.
3. The available GUI applications on Soteria are **:simple-rstudio: RStudio**, **:material-chart-bell-curve: Matlab**, **:simple-jupyter: Jupyter** and **:material-apps-box: Stata**.

??? Warning "First time logging in? Home directory not found?"

    If this is your first logging onto the OnDemand Soteria service, it is likely that you're going to be greeted with the following message:

    <figure markdown="span">
        ![](../assets/HPC/hpc-00.png){width="650"}
    </figure>
    If that is the case, follow the onscreen instructions:

    1. Open the shell (which will automatically create your home folder).
    2. Reload the page.

    Once that is done, you should be greeted with the OnDemand home page.

    <figure markdown="span">
        ![](../assets/HPC/hpc-01.png){width="650"}
    </figure>

### :simple-rstudio: RStudio

1. Once you access the OnDemand interface, navigate to the "Interactive Apps" dropdown menu.
2. Select "RStudio server" from the options.
    <figure markdown="span">
        ![](../assets/HPC/hpc-02.png){width="650"}
    </figure>
3. Choose the necessary resources and enter your PI's accounting group in the "PI Group" field.
    <figure markdown="span">
        ![](../assets/HPC/hpc-03.png){width="700"}
    </figure>
4. Connect to the requested node by clicking "Connect to RStudio Server".
    <figure markdown="span">
        ![](../assets/HPC/hpc-04.png){width="700"}

### :material-chart-bell-curve: Matlab

To access Matlab on Soteria via the Open OnDemand interface, follow these steps:

1. Once you access the OnDemand interface, navigate to the "Interactive Apps" dropdown menu.
5. Select "Interactive Desktop" from the options.

  <p align="center">
<img src="https://github.com/ua-data7/User-Manuals/blob/main/images/HPC/1.jpg?raw=true" width="650">
</p> 

6. Choose the required resources and enter your PI's accounting group in the "PI Group" field.

<p align="center">
<img src="https://github.com/ua-data7/User-Manuals/blob/main/images/HPC/3.jpg?raw=true" width="650">
</p>

7. After your session is assigned to a compute node, click on "Launch Interactive Desktop."
<p align="center">
<img src="https://github.com/ua-data7/User-Manuals/blob/main/images/HPC/4.jpg?raw=true" width="650">
</p>

8. A Mate Terminal icon will be displayed. Click on it to open the terminal.

<p align="center">
<img src="https://github.com/ua-data7/User-Manuals/blob/main/images/HPC/5.jpg?raw=true" width="650">
</p>

9. In the terminal, enter the following commands:

   **`module load matlab`** - This command loads the Matlab module.

   **`matlab`** - This command starts the Matlab software.


<p align="center">
<img src="https://github.com/ua-data7/User-Manuals/blob/main/images/HPC/6.jpg?raw=true" width="650">
</p>

10. Please note that the initial loading of Matlab may take some time as it involves loading various files. Subsequent uses of Matlab will load more quickly.


<p align="center">
<img src="https://github.com/ua-data7/User-Manuals/blob/main/images/HPC/7.jpg?raw=true" width="650">
</p>

<p align="center">
<img src="https://github.com/ua-data7/User-Manuals/blob/main/images/HPC/8.jpg?raw=true" width="650">
</p>

By following these steps, you will be able to launch Matlab on Soteria using the Open OnDemand interface and access its functionality for your research needs.


   #### **Jupytor Notebooks and Python:**

To access Jupyter Notebooks and Python on Soteria via the Open OnDemand interface, you can follow these steps:

1.  Connect to the Soteria VPN as mentioned earlier.

2.  Open your preferred web browser.

3.  Go to the following URL: [**https://ondemand-hipaa.hpc.arizona.edu**](https://ondemand-hipaa.hpc.arizona.edu/)

4.  Once you are on the OnDemand interface, follow the steps to open a Mate Terminal session:
   
      a. Navigate to the "Interactive Apps" dropdown menu.
  
      b. Select "Interactive Desktop" from the options.
  
      c. Choose the required resources and enter your PI's accounting group in the "PI Group" field.
  
      d. Click on "Launch Interactive Desktop" to start the session.
  
      e. Open the Mate Terminal as instructed earlier.

5. In the Mate Terminal, enter the following commands:
   
   **`module load python/3.9`** - This command loads the Python 3.9 module.
   
   **`jupyter-notebook`** - This command starts the Jupyter Notebook server.


<p align="center">
<img src="https://github.com/ua-data7/User-Manuals/blob/main/images/HPC/10.jpg?raw=true" width="650">
</p>

6. After running the **`jupyter-notebook`** command, you will see the server starting and displaying a URL in the terminal. Copy the URL and paste it into your web browser.

<p align="center">
<img src="https://github.com/ua-data7/User-Manuals/blob/main/images/HPC/9.jpg?raw=true" width="650">
</p>


7. The Jupyter Notebook interface will open in your browser, allowing you to create, edit, and run Python notebooks.

By following these steps, you will be able to launch Jupyter Notebooks with Python 3.9 on Soteria.

For more specific instructions on accessing GUI applications, including Matlab and Jupyter Notebooks with Python, please refer to the detailed instructions provided in the [link](https://public.confluence.arizona.edu/display/UAHPC/Secure+HPC#soteria-access-gui-access).

Please note that the provided link may contain comprehensive instructions tailored specifically to Soteria, ensuring a seamless GUI access experience.

### **Command Line Access:**

\
To access Soteria through the command line, you can use SSH (Secure Shell) with the following instructions:

1.  Open your preferred terminal application on your local machine.

2.  Use the SSH command to connect to Soteria. The hostname for Soteria command line access is: **`shell.cougar.hpc.arizona.edu`**

    Enter the following command, replacing **`your_netid`** with your actual NetID:

    ```         
    rubyCopy code
    ```

    `$ ssh your_netid@shell.cougar.hpc.arizona.edu`

3.  You will be prompted to enter your password. Please provide your password associated with your NetID.

    Note: Make sure you have authorized access to use Soteria. All user activity may be monitored and reported.

4.  After successfully logging in, you will see a message similar to the following:

    ```         
    sqlCopy code
    ```

    `Last login: Tue Nov 29 06:18:33 2022 from ans-02.hpc.arizona.edu Authorized uses only. All activity may be monitored and reported. netid@taub:~ $`

    The **`taub`** is a login node, and it provides the same functionality and follows the same policies as other HPC clusters.

5.  Please note that modules are available on Soteria's compute nodes but not on the login node. You can use the **`interactive`** command to request a session on a compute node, and jobs can be submitted using the standard **`sbatch`** command.

    For more detailed information on running jobs with SLURM and utilizing Soteria's capabilities, please refer to the documentation or guidelines provided in the section titled "Running Jobs with SLURM."

By following these steps, you can access Soteria through the command line using SSH and utilize the available functionalities and resources for your research and computational tasks.\

## Transferring and Accessing Data

### Globus:

Globus is a recommended tool for efficiently transferring data to and from the Soteria environment. It provides a reliable and secure data transfer mechanism. To learn more about using Globus, please refer to the following link: [**Globus Documentation**](https://public.confluence.arizona.edu/display/UAHPC/Transferring+Data#TransferringData-GridFTP/Globus)

Soteria Endpoint for Globus: UA HPC HIPAA Filesystems

**File Paths:** When working with Soteria, you can access your files using the following file paths:

1.  Filexfer Nodes:

    -   **`/hipaa/groups/<pi_netid>`**: This path allows access to the shared group directories associated with your PI's NetID.

    -   **`/hipaa/home/uxx/<your_netid>`**: This path provides access to your personal home directory under your NetID.

2.  When connected to a Soteria login or compute node:

    -   **`/groups/<pi_netid>`**: This path corresponds to the shared group directories associated with your PI's NetID.

    -   **`/home/uxx/<your_netid>`**: This path corresponds to your personal home directory under your NetID.

By utilizing these file paths, you can efficiently access and manage your data within the Soteria environment.
