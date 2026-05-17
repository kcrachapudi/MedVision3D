# DICOM Basics
## The Foundation of Medical Imaging Systems

# What Is DICOM?

DICOM stands for:

Digital Imaging and Communications in Medicine

DICOM is BOTH:

1. medical image file format
2. medical imaging communication standard

# DICOM Hierarchy

Patient
  └── Study
       └── Series
            └── Instance

# Study

Represents an imaging exam.

Example:

CT Chest with Contrast

# Series

A study may contain multiple series.

Examples:

- axial slices
- contrast-enhanced series
- bone reconstruction
- lung reconstruction

# Instance

Usually a single image slice.

Hundreds of instances form a 3D volume.

# Important Metadata

## Patient Metadata

- PatientName
- PatientID
- PatientSex

## Imaging Metadata

- SliceThickness
- PixelSpacing
- ImagePositionPatient
- ImageOrientationPatient

# Common Modalities

- CT
- MR
- US
- PT
- XA
- DX

# PACS

PACS = Picture Archiving and Communication System

PACS stores and distributes DICOM studies.

# Typical Workflow

Scanner
→ DICOM images
→ PACS
→ radiology workstation
→ radiologist review
→ report
