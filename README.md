# Computer Vision and Data Annotation Portfolio

A practical portfolio documenting hands-on work in dataset preparation, data annotation, annotation quality assurance, and machine learning data workflows.

This portfolio is designed to demonstrate practical experience in preparing and annotating data for AI and machine learning applications, with projects covering different annotation tasks, tools, workflows, and data formats.

---

## About This Portfolio

This portfolio showcases practical projects completed as part of my development in AI training and data annotation.

Each project documents the complete annotation workflow, from working with source data and defining annotation classes to performing annotations, reviewing data quality, exporting datasets, and documenting the work.

The portfolio will continue to grow as I develop experience across additional areas of AI training and data preparation.

---

## Areas of Practice / Skills Demonstrated


Through completed projects, the portfolio currently demonstrates practical skills in:

- Image Data Annotation
- Object Detection
- Bounding Box Annotation
- Dataset Preparation
- Annotation Quality Assurance
- Custom Label Definition
- Annotation Review and Correction
- Annotation Dataset Organization
- COCO annotation export
- YOLO annotation export
- Technical documentation
- Version-controlled portfolio management

Future projects will expand into additional areas of computer vision and data annotation.

---

## Project / Annotation Types

### Currently Practiced

- Bounding Box Annotation
- Object Detection Annotation

### Future Projects / Future Practice 

- Image Classification
- Image Segmentation
- Video Annotation
- Polygon and Polyline Annotation 
- Keypoint and Skeleton Annotation
- Advanced Computer Vision Annotation
- 3D Bounding Boxes and Spatial Labelling 

The annotation types listed under future practice will be added to the portfolio as corresponding projects are completed.

---

## Tools & Technologies

### Annotation Tools

- CVAT (Computer Vision Annotation Tool)

### Data Formats

- COCO 1.0
- Ultralytics YOLO Detection 1.0

### Portfolio & Documentation

- GitHub
- Markdown

Additional tools and technologies will be added as the portfolio expands.

---

## Annotation Workflow

The projects in this portfolio follow a structured annotation workflow:

**Dataset Selection → Label Definition → Annotation → Quality Review → Correction → Export → Documentation**

### 1. Dataset Selection

Identify and prepare suitable image or other data sources for the annotation task.

### 2. Label Definition

Define the object or content categories required for the specific project.

### 3. Annotation

Apply the appropriate annotation type to the selected data using an annotation tool.

### 4. Quality Review

Manually review completed annotations to identify:

- Missed objects
- Incorrect labels
- Inaccurate bounding boxes
- Loose bounding boxes
- Inconsistent annotations

### 5. Correction

Correct identified issues and review the dataset again to improve annotation quality and consistency.

### 6. Export

Export the completed annotations into appropriate machine-learning data formats.

### 7. Documentation

Document the project, annotation methodology, quality-control process, dataset information, and exported files.

---

## Projects

### Project 01 — Street Scene Object Detection

**Status:** Completed

A practical image annotation project involving the annotation of 50 street-scene images using CVAT.


**[View Project 01 →](./Project-01-Street-scene-object-detection/)**

---

## Portfolio Development

This portfolio represents an ongoing learning and professional development journey in computer vision and data annotation.

Each completed project is intended to demonstrate not only the ability to perform an annotation task, but also an understanding of data quality, annotation consistency, structured workflows, dataset preparation, and documentation.

As new skills and projects are developed, this portfolio will be updated to reflect broader capabilities across the AI training lifecycle.

---

## Repository Structure

```text
AI-Data-Annotation-Portfolio
│
├── README.md
│
└── Project-01-Street-scene-object-detection
    │
    ├── README.md
    │
    ├── screenshots
    │   ├── Street-scene-object-detection-CVAT-workspace.PNG
    │   ├── Street-scene-object-detection-label-list.PNG
    │   ├── Street-scene-object-detection-annotation-example-01.PNG
    │   ├── Street-scene-object-detection-annotation-example-02.PNG
    │   └── Street-scene-object-detection-annotation-example-03.PNG
    │
    └── Annotations
        │
        ├── COCO
        │   └── COCO annotation file
        │
        └── YOLO
            ├── data.yaml
            │
            └── labels
                └── train
                    └── YOLO annotation files
