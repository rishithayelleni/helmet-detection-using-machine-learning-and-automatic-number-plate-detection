
# Helmet Detection and License Plate Recognition System

## Project Overview

This project is an AI-based traffic monitoring system that detects whether motorcyclists are wearing helmets and identifies vehicle license plates of riders violating helmet rules. The system helps improve road safety and supports automated traffic law enforcement.

## Features

* Detects motorcycles and riders in images/videos
* Identifies helmet and non-helmet riders
* Extracts vehicle license plates automatically
* Uses OCR to read license plate numbers
* Supports real-time video surveillance
* Improves traffic monitoring efficiency

## Technologies Used

* Python
* YOLO (You Only Look Once)
* OpenCV
* CNN (Convolutional Neural Networks)
* OCR (Optical Character Recognition)
* NumPy

## Project Workflow

1. Capture image or video input
2. Detect motorcyclists using YOLO
3. Classify helmet usage
4. Identify helmet violations
5. Extract license plate region
6. Apply OCR to read plate number
7. Store violation details

## Installation

1. Clone the repository:

```bash
git clone <repository-link>
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the project:

```bash
python main.py
```

## Applications

* Smart traffic management
* Road safety monitoring
* Automated fine generation
* Law enforcement assistance

## Future Enhancements

* Cloud database integration
* Mobile application support
* Higher OCR accuracy
* Real-time alert notifications

## Conclusion

This project provides a scalable and cost-effective solution for detecting helmet violations and automating license plate recognition, contributing to safer roads and smarter traffic systems.
