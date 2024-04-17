# CustomerClassifier

CustomerClassifier is a Python project to classify buyers into various categories such as t-shirts, blazers, dresses, and more. It utilizes machine learning algorithms to analyze and recognize patterns in the dataset, allowing for accurate classification. This project provides a convenient solution for automating the categorization of customers based on historical purchase behavior, which can be useful in various applications such as e-commerce platforms, fashion analysis, and inventory management or even for advanced CRM (Customer Relationship Management) analysis.

## Prerequisites

Before running CustomerClassifier, make sure you have the following requirements:

- Python 3.9 or higher
  

## Google Colab


## Local Installation

To get started with FashionClassifier, follow these steps:

### **1. Open a shell and clone this repo**

```bash
git clone https://github.com/jacquesbilombe/CustomerClassifier
```

### **2. Create FashionClassifier environment.**

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

Go to FashionClassifier/ folder and run the following code in Anaconda Prompt to create and install all pre-requirements

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
python main.py FLAG "train_folder" "teste_folder" "images_label_and_id.csv"
```

Terminal Example:

```bash
python main.py 0 "/compressed_images" "/original_images" "images.csv"
```

Obs: 
- FLAG: 0 to use the trained ML model and 1 to train the ML model again. 
- train_folder && teste_folder && images_label_and_id: if the line is empty "", the code will use the project dataset

------------
### All

- [ ] Token for automation.
