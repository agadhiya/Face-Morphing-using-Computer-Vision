# Face-Morphing-using-Computer-Vision

## Introduction

Face morphing is a technique used to seamlessly transform one face into another by blending images. This project explores the implementation of such an algorithm, demonstrating the potential of image processing in creating realistic morphing effects.

## Implementation Details:

The implementation involves several key steps:
1. **Facial Feature Detection**: Utilizing the dlib library, corresponding points on the faces are detected, including facial landmarks and additional points to improve alignment.
2. **Delaunay Triangulation**: Triangulating the detected points to create a mesh of triangles over the faces, which aids in warping and blending.
3. **Image Warping**: Warping the source and target images to align the triangles, ensuring smooth transitions between features.
4. **Alpha Blending**: Blending the warped images using alpha blending to create the final morphed image.

## Software/Package Requirement:

- Python (version 3.11)
- OpenCV
- NumPy
- dlib library
- Matplotlib (for visualization)


## Results:

The resulting morphed images showcase well-aligned facial features, demonstrating the effectiveness of the implemented algorithm. Additional points can be manually added to fix misalignments in non-facial regions for better results.

## References:

- [Image Morphing: A Literature Study](https://www.researchgate.net/publication/280929662)
- [Comparative Study of Triangulation based and Feature based Image Morphing](https://www.researchgate.net/publication/270018791)
- [Image Morphing Techniques: A Review](https://www.researchgate.net/publication/369905336)
