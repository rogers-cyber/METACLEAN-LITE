# METACLEAN LITE – Simple Offline Metadata Cleaner v1.0.0

METACLEAN LITE v1.0.0 is a lightweight desktop application designed to remove EXIF metadata and hidden image information safely and completely offline. It helps users protect privacy by stripping GPS coordinates, camera details, timestamps, and embedded metadata from images while preserving visual quality.

Built for photographers, journalists, privacy-conscious users, researchers, and everyday workflows, METACLEAN LITE focuses on simplicity, speed, and safe offline image processing with an easy-to-use modern interface.

------------------------------------------------------------
WINDOWS DOWNLOAD (EXE)
------------------------------------------------------------

Download the latest Windows executable from GitHub Releases:

https://github.com/rogers-cyber/METACLEAN-LITE/releases

- No Python installation required
- Standalone Windows executable
- Fully offline processing
- Lightweight and beginner-friendly
- Drag & drop support included

------------------------------------------------------------
DISTRIBUTION
------------------------------------------------------------

METACLEAN LITE is distributed as a lightweight desktop utility.

This repository/documentation may include:

- Python source code
- Windows executable builds
- Commercial upgrade references

Python is only required for running the source code version.

------------------------------------------------------------
FEATURES
------------------------------------------------------------

CORE CAPABILITIES

- 🖼 Remove EXIF metadata from images
- 📍 Strip GPS and location information
- 🔒 Fully offline image privacy cleaning
- ⚡ Fast batch image processing
- 🧠 Preserve image orientation automatically
- 🗂 Supports folder imports recursively
- 🖱 Drag & drop image support
- 📊 Real-time progress tracking
- 🧹 Safe export of cleaned images
- 💻 Lightweight modern desktop interface

SUPPORTED IMAGE FORMATS

- PNG
- JPG / JPEG
- WEBP
- BMP
- TIFF

METADATA PREVIEW SYSTEM

- View detected EXIF metadata before cleaning
- Inspect camera and device metadata
- Read timestamps and embedded information
- Live metadata preview panel

USER INTERFACE

- Modern ttkbootstrap interface
- Drag & drop workflow
- Image list preview
- Metadata inspection panel
- Progress bar and status system
- Simple one-click metadata removal
- Minimal learning curve

------------------------------------------------------------
INSTALLATION (SOURCE CODE)
------------------------------------------------------------

1. Clone the repository:

git clone https://github.com/rogers-cyber/METACLEAN-LITE.git

cd METACLEAN-LITE

2. Install required dependencies:

pip install pillow ttkbootstrap tkinterdnd2

3. Run the application:

python METACLEAN_LITE.py

------------------------------------------------------------
BUILD WINDOWS EXECUTABLE
------------------------------------------------------------

You can create a standalone Windows executable using PyInstaller.

1. Install PyInstaller:

pip install pyinstaller

2. Build the application:

pyinstaller --onefile --windowed --icon=logo.ico METACLEAN_LITE.py

The compiled executable will appear in:

dist/METACLEAN_LITE.exe

------------------------------------------------------------
USAGE GUIDE
------------------------------------------------------------

1. Add Images  
Click "Add Images" to import files individually.

2. Add Folder  
Click "Add Folder" to scan folders recursively for supported images.

3. Drag & Drop  
Drag image files or folders directly into the application window.

4. Preview Metadata  
Select any image from the list to inspect existing EXIF metadata.

5. Start Cleanup  
Click "REMOVE METADATA" and select an output folder.

6. Export Clean Images  
Cleaned files are saved with:

filename_clean.extension

Example:

photo_clean.jpg

------------------------------------------------------------
METADATA REMOVAL DETAILS
------------------------------------------------------------

METACLEAN LITE removes common embedded metadata including:

- GPS coordinates
- Camera information
- Device information
- EXIF tags
- Timestamps
- Hidden metadata fields

The application rebuilds images safely while preserving image quality and orientation.

------------------------------------------------------------
LOGGING & ERROR HANDLING
------------------------------------------------------------

METACLEAN LITE includes safe error handling:

- Prevents duplicate file imports
- Handles unsupported image files safely
- Displays processing progress live
- Continues batch operations even if one file fails
- Prevents application crashes during cleanup

------------------------------------------------------------
REPOSITORY STRUCTURE
------------------------------------------------------------

METACLEAN-LITE/

├── METACLEAN_LITE.py  
├── logo.ico  
├── README.md  
├── LICENSE  

Generated at runtime:

├── Cleaned image exports (output folder)

------------------------------------------------------------
DEPENDENCIES
------------------------------------------------------------

Python 3.10+

Libraries used:

- Pillow
- ttkbootstrap
- tkinter
- tkinterdnd2
- pathlib
- os
- sys

Optional:

- tkinterdnd2 (drag & drop support)

------------------------------------------------------------
INTENDED USE
------------------------------------------------------------

METACLEAN LITE is ideal for:

- Privacy-focused image cleanup
- Removing hidden metadata before sharing images
- Cleaning social media uploads
- Preparing professional photo deliveries
- Offline secure image processing
- Batch metadata removal workflows

Optimized for speed, simplicity, and offline privacy protection.

------------------------------------------------------------
UPGRADE TO PRO
------------------------------------------------------------

Upgrade to METACLEAN PRO for advanced privacy workflow features:

- Advanced metadata analysis
- Backup systems
- Export reports
- Bulk automation workflows
- Advanced batch processing
- Logging systems
- Metadata reporting dashboards
- Enterprise-scale workflows

Website:

https://matetools.gumroad.com

------------------------------------------------------------
ABOUT
------------------------------------------------------------

METACLEAN LITE is developed by Mate Technologies, focused on building professional offline desktop tools for privacy, productivity, and creative workflows.

Website:

https://matetools.gumroad.com

© 2026 Mate Technologies  
All rights reserved.

------------------------------------------------------------
LICENSE
------------------------------------------------------------

METACLEAN LITE is distributed as commercial software.

License terms:

- Personal and commercial usage allowed
- Redistribution or resale as a competing product is prohibited
- Repackaging or rebranding for resale is prohibited
- Source modifications allowed for internal/private use
- Compiled executable usage permitted under license

For commercial licensing or enterprise deployment, contact the developer.

## 📷 Preview

<img alt="METACLEAN-LITE" src="https://github.com/rogers-cyber/METACLEAN-LITE/blob/main/METACLEANLITE%20-%20Main%20Interface.png" />

<img alt="METACLEAN-LITE" src="https://github.com/rogers-cyber/METACLEAN-LITE/blob/main/METACLEANLITE%20-%20Preview%20Metadata.png" />

<img alt="METACLEAN-LITE" src="https://github.com/rogers-cyber/METACLEAN-LITE/blob/main/METACLEANLITE%20-%20Cleanup%20Complete.png" />

---