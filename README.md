# Installation Guide for REvolutionH-tl on Window from scratch

This guide outlines a four-step process for setting up the environment to use REvolutionH-tl, including the installation of Python, Diamond, BLAST, and REvolutionH-tl.

**Requirements:**
- Make sure Python >=3.7 is installed before proceeding.
- Either Diamond or BLAST is needed for sequence alignments.

## Step 1: Install Python
This tutorial will guide you through the steps to install Python 3 on Windows using the package distributor.

### Step 1.1: Download the Python Installer

1. Visit the official Python website at [python.org](https://www.python.org/).
2. Navigate to the Downloads section and choose the version of Python 3 you wish to install.
3. Click on the link for Windows and download the appropriate installer for your version of Windows (32-bit or 64-bit).

### Step 1.2: Run the Installer

1. Once the installer has been downloaded, double-click on it to start the installation.
2. Make sure to check the box that says "Add Python 3.x to PATH" to add Python to your system's PATH.
3. Click on "Install Now" to install Python with the default settings.

### Step 1.3: Verify the Installation

1. To verify that Python has been installed correctly, open the Command Prompt (you can search for 'cmd' in the Start menu).
2. Type `python --version` and press Enter.
3. If the installation was successful, you will see the version of Python you have installed.

Congratulations! You now have Python 3 installed on your Windows system.

## Step 2: Install Diamond
Diamond is a high-performance DNA sequence aligner. Follow these steps to install it on Windows:

### Step 2.1: Download the Latest Release
1. Visit the Diamond GitHub releases page at [Diamond Releases on GitHub](https://github.com/bbuchfink/diamond/releases) to download the latest version.
2. Select the version suitable for your Windows operating system, typically a `.exe` file.

### Step 2.3:  Run the Installer
1. Execute the downloaded file to install Diamond.
2. Follow the on-screen instructions to complete the installation.

### Step 2.4:  Verify the Installation
1. To verify that Diamond has been installed correctly, open Command Prompt.
2. Type `diamond --help` and press Enter.
3. If the installation was successful, you will see available options.

**Note:** For detailed instructions and troubleshooting, refer to the GitHub page and the software's help command.

## Step 3: Install BLAST
BLAST (Basic Local Alignment Search Tool) is a powerful tool for genomic and protein sequence analysis. Here's how you can install it on Windows:

### Step 3.1: Download BLAST+
1. Visit the [NCBI FTP site](https://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/LATEST/) to download BLAST+ installers and source code.
2. Click on the link for Windows and download the version of Windows (64-bit) a `.exe` file.

### Step 3.2: Install BLAST+
1. Run the installer you downloaded from the NCBI FTP site to install BLAST+ on your Windows system.
2. Follow the on-screen instructions to complete the installation.

**Note:** For detailed instructions and troubleshooting, consult the BLAST+ user manual available on the [NCBI website](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE_TYPE=BlastDocs&DOC_TYPE=Download).

## Step 4: Install REvolutionH-tl
After setting up Python, Diamond, and BLAST, you can proceed to install REvolutionH-tl.

PowerShell, the blue Windows terminal, will be used to run pip, Python, and `revolutionhtl`.

1. Open Command Prompt on your Windows system.
2. To install `revolutionhtl`, type the following command and press Enter:

    ```
    pip install revolutionhtl
    ```

    This command will download and install `revolutionhtl` from the Python Package Index (PyPI). You can find more information about it on: [revolutionhtl on PyPI](https://pypi.org/project/revolutionhtl/).

4. After the installation is complete, you can verify it by running a command specific to `revolutionhtl` or by checking its version.

Congratulations! You have successfully installed REvolutionH-tl.

