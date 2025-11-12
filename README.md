# 🕶️ Meta-Glasses-Photo-Maker

[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)] (LICENSE)

## ✨ Project Purpose

This application is a standalone GUI tool designed to simply modify the **EXIF metadata** of any JPEG image.

When platforms like Instagram or Facebook detect specific camera manufacturer (`Meta AI`) and model (`Ray-Ban Meta Smart Glasses`) tags in an image's metadata, they automatically display the **“Ray-Ban META glasses”** tag in stories and posts.

This application allows your photos to appear as if they were taken with Meta smart glasses by adding this required metadata to your existing photos.

## 🚀 Key Features

* **Standalone GUI:** Simple and easy-to-use interface built with Tkinter.
* **DATA Injection:** Directly writes the required `Maker` and `Model` tags.
* **Timestamp:** Sets the EXIF capture date/time to the current time of processing.
* **Save As:** Never modifies the original file; always saves a new, tagged copy.
* **Zero Dependency (After Compilation):** Once compiled as an EXE, does not require Python to be pre-installed on the user's computer.

## 🛠️ Installation

### 1. Requirements

Python 3.x must be installed on your computer.

To install the required libraries, use the provided `requirements.txt` file and run the following command:
