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
