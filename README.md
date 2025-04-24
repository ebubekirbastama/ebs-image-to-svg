🖼️ EBS IMAGE TO SVG CONVERTER
=============================

Convert any image (JPG, PNG, etc.) to a compressed SVG format with run-length encoding,
and also export it as BMP and PNG. This tool is optimized for speed and simplicity, ideal
for visual analysis, image compression research, and archival purposes.

------------------------------------------------------------
✨ FEATURES
------------------------------------------------------------
- ✅ Convert image to compressed SVG (run-length encoding)

- 📤 Export to BMP and PNG formats

- 📏 Shows image dimensions and processing time

- 🧾 Command-line support for input/output

- 📂 Auto-create output directory if missing

- 🧠 Written in Python with OpenCV

------------------------------------------------------------
📦 REQUIREMENTS
------------------------------------------------------------

- 🐍 Python 3.6 or higher

- 🧰 OpenCV (`cv2` module)

Install OpenCV via pip:

    📥 pip install opencv-python

------------------------------------------------------------
⚙️ USAGE
------------------------------------------------------------
Run the script like this:

    ▶️ python ebs-image_to_svg_converter.py -i path/to/image.jpg -o output_folder

🧩 Arguments:

🔹 -i, --input   → Path to input image (required)  
🔹 -o, --output  → Output folder (default: "output")

------------------------------------------------------------
🔍 EXAMPLE
------------------------------------------------------------

    ▶️ python ebs-image_to_svg_converter.py -i example.jpg -o results

🎉 Output files will be:

✅ output_compressed.svg  
✅ output_bitmap.bmp  
✅ output_compressed.png

------------------------------------------------------------
📁 OUTPUT PREVIEW
------------------------------------------------------------

results/

- ├── 🖼️ output_compressed.svg

- ├── 🖼️ output_bitmap.bmp

- └── 🖼️ output_compressed.png

------------------------------------------------------------
📝 LICENSE
------------------------------------------------------------
📜 This project is licensed under the MIT License.  
See the LICENSE file for more info.

------------------------------------------------------------
👨‍💻 CREDITS
------------------------------------------------------------
👤 Developed by: Ebubekir Bastama  
🌐 GitHub: https://github.com/ebubekirbastama  
🔧 Part of the EBS Tools Collection  
🙏 Thanks to the Python and OpenCV communities!

------------------------------------------------------------
💡 FUTURE IDEAS
------------------------------------------------------------
🗂️ [ ] Batch image conversion (folder-wide support)  
🖱️ [ ] GUI version with drag & drop  
⚙️ [ ] Custom SVG optimization levels
