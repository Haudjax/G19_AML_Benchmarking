# G19 — AML Benchmarking

A benchmarking project for **tabular machine learning datasets** used in the **AML 2025** context.

---

## 📦 Repository Setup

Follow the steps below to clone the repository, add the required datasets, and set up the environment.

---

## 🔹 1. Clone the Repository

```bash
git clone https://github.com/Haudjax/G19_AML_Benchmarking.git
cd G19_AML_Benchmarking
```

---

## 🔹 2. Add Required Dataset Folder

Make sure the following folder exists **inside the repository root**:

```text
aml-2025-benchmarking-tabular-ml-datasets/
```

> ⚠️ **Important:** The code will not run correctly unless this folder is present and correctly named.

---

## 🔹 3. Create the Conda Environment

Create the environment using the provided `environment.yml` file:

```bash
conda env create -f environment.yml
```

---

## 🔹 4. Activate the Environment

```bash
conda activate tblr_bnch
```

---

## ✅ You're Ready to Go

Once the environment is activated and the dataset folder is in place, you can start running the benchmarking code.

---

## 🛠 Troubleshooting

* Ensure you are using **Conda** (not `pip`) to create the environment
* Double-check the dataset folder name and location

---

## 📁 Project Structure (Overview)

```text
G19_AML_Benchmarking/
├── aml-2025-benchmarking-tabular-ml-datasets/
├── environment.yml
├── README.md
└── ...
```

---
