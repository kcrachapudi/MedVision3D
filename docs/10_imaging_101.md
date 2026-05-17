# Imaging 101
## Medical Imaging Fundamentals for Software Engineers

# What Is Medical Imaging?

Medical imaging is the process of generating visual representations of internal body structures for:

- diagnosis
- treatment planning
- surgical guidance
- disease monitoring
- biomedical research
- AI analysis

Medical imaging transforms physical signals into digital image data.

Examples:

- X-rays
- magnetic signals
- ultrasound waves
- radioactive tracers

become:

- 2D images
- 3D volumes
- functional maps
- anatomical reconstructions

# Main Imaging Modalities

## X-Ray

Dense tissues absorb more radiation.

- bone = bright
- air = dark
- soft tissue = gray

## CT (Computed Tomography)

CT uses rotating X-ray acquisition from multiple angles.

Key concepts:

- slice
- voxel
- spacing
- orientation
- HU values
- window/level

### Hounsfield Units

- Air ≈ -1000
- Water ≈ 0
- Bone ≈ +1000

## MRI (Magnetic Resonance Imaging)

MRI uses:

- strong magnetic fields
- radio-frequency pulses
- signal relaxation physics

MRI is excellent for:

- brain imaging
- spinal cord
- soft tissue
- tumors

## Ultrasound

Uses high-frequency sound waves.

## PET

Uses radioactive tracers to visualize metabolic activity.

# Core Concepts

## Pixel

2D image element.

## Voxel

3D pixel.

## Slice

Single cross-sectional image.

## Volume

Complete 3D imaging dataset.

# Imaging Planes

## Axial

Top-to-bottom slices.

## Coronal

Front-facing slices.

## Sagittal

Side-facing slices.

# Window / Level

Controls brightness and contrast visualization.

# Why This Matters

Without these concepts:

- 3D Slicer becomes confusing
- segmentation becomes confusing
- DICOM becomes confusing
