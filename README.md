# StegLyser
🔒 StegLyser is a modern steganography analyzer tool that embeds and extracts hidden messages across images, audio, video, and archive files. Built with Python and CustomTkinter, it features LSB and metadata-based techniques, file metadata viewer, and a sleek GUI for secure communication and digital forensics.

I developed StegLyser, a modern steganography analyzer tool designed to embed and extract hidden messages across multiple file formats including images, audio, video, and archives.

Unlike traditional tools that focus only on one medium (e.g., just images), StegLyser provides a unified platform with a clean, modern GUI built using CustomTkinter, making it highly intuitive and user-friendly.

Key Features:

Multi-format support: Works with images (PNG, BMP, JPG), audio (WAV, AIFF, AU, FLAC, M4A, OGG, AAC), videos (MP4, MKV, AVI, MOV, etc.), and archive files (ZIP, RAR).

Steganography techniques:
   -LSB (Least Significant Bit) method for images and audio
   -Metadata-based embedding for formats like FLAC, M4A, and OGG
   -File Metadata & Quick Stats Viewer: Displays file information including size, type, resolution, duration, and EXIF data.
   -Report Generation: Allows saving extracted results and file analysis into a structured report.
   -Responsive GUI: Dark theme, modern design, and easy navigation.

Technologies Used:
   -Python (core language)
   -Pillow (PIL) – image handling
   -Stegano – image steganography (LSB)
   -Pydub & Mutagen – audio processing
   -OpenCV & FFmpeg – video analysis
   -CustomTkinter – modern GUI
   -Zipfile/Rarfile – archive handling

Impact:

StegLyser can be applied in cybersecurity, digital forensics, and secure communication where data confidentiality is crucial. It bridges the gap between academic research and practical usage by combining multi-format support in a single analyzer tool.

About Us:

This project was collaboratively developed by Muhammed Roshan KC and Surya Suresh during our postgraduate studies at Marwadi University. Together, we designed, implemented, and tested the tool from scratch, combining our skills in Python programming, GUI design, and cybersecurity concepts. Working as a two-member team allowed us to share responsibilities effectively and strengthen our practical understanding of steganography and digital forensics.
