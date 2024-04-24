# CustomerClassifier

The automotive industry is dynamic and highly competitive, with manufacturers and dealerships constantly seeking innovative ways to attract and retain customers. This project focuses on leveraging data-driven techniques to analyze automobile sales data and extract valuable insights to inform decision-making and drive business growth. The dataset used comprises historical automobile sales data, providing a comprehensive view of customer interactions with the dealership. By employing RFM segmentation combined with machine learning algorithms, we aim to understand customer behavior, optimize marketing efforts, and maximize profitability in the automotive sales industry.

## Prerequisites

Before running CustomerClassifier, make sure you have the following requirements:

- Python 3.9 or higher
  

## Google Colab


## Local Installation

To get started with CustomerClassifier, follow these steps:

### **1. Open a shell and clone this repo**

```bash
git clone https://github.com/jacquesbilombe/CustomerClassifier
```

### **2. Create CustomerClassifier environment.**

#### **2.1 Install make.**
* **For Windows:**

  1- Open PowerShell (Windows + x)

  2- Install Chocolatey

```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

  3- Verify Chocolatey install

```bash
choco
```

  4- Make install

```bash
choco install make
```

* **For Linux:**

  1- Make install

```bash
sudo apt install make
```

#### **2.2 Install Anaconda**
 
If you don't have Anaconda, see how to install it here https://docs.anaconda.com/anaconda/install/linux/

### **3. Conda Torus environment creation.**

Go to CustomerClassifier/ folder and run the following code in Anaconda Prompt to create and install all pre-requirements

```bash
cd CustomerClassifier
make setup
```
Finally, activate the conda environment

```bash
conda activate RFM
```
### **4. Run FashionClassifier**

```bash
python main.py FLAG "database.csv"
```

Terminal Example:

```bash
python main.py 0 "dataset.csv"
```

Obs: 
- FLAG: 0 to use the trained ML model and 1 to train the ML model again. 
- Dataset (Yours): if the line is empty "", the code will use the project dataset

------------
### All

- [ ] Token for automation.
