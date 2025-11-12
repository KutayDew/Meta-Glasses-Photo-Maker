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

To install the required libraries, use the provided `requirements.txt` file and run the following command:

# ⚙️ Project Dependencies and Required Libraries

This application relies on minimal but critical Python libraries to perform the Meta Glasses EXIF injection process and provide a powerful graphical user interface (GUI).

The following libraries are **absolutely required** for running the application with its source code (`.py` file) or compiling it with PyInstaller.

## 🚀 List of Main Dependencies

| Library Name | Recommended Version | Role and Importance |
| :--- | :--- | :--- |
| **Pillow (PIL)** | `>= 9.0.0` | 🖼️ **Image Processing Engine.** Used to open JPEG files, manage data streams, and save files after EXIF data is written. It forms the basis of image format compatibility. |
| **piexif** | `Latest Version` | 🏷️ **EXIF Manipulation Expert.** Performs reading, modifying, and rewriting operations on the metadata (EXIF) structure of JPEG files. It is critical for successfully injecting Meta Glasses tags. |

---

## 🛠️ Installation Instructions

To install these dependencies with a single command, please use the `requirements.txt` file located in your project's root directory.

### Terminal Command

Run the following command in your Terminal/Command Prompt window:

```bash
pip install -r requirements.txt
```
## My Contact Information
[Link](https://www.instagram.com/kutaydew.support) My Instagram Support Account
