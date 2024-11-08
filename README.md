# Face-Swap-using-Stable-Diffusion-Inpainting
This project implements a face-swapping technique using the Stable Diffusion Inpainting Pipeline and OpenCV for face detection. The approach combines face detection and image inpainting to transfer a face from a source image onto a target image, using deep learning models for seamless blending.
# Features
* **Face Detection with OpenCV:** Automatically detects faces in the target image, leveraging OpenCV's Haar cascades.
* **Face Alignment and Resizing:** Adjusts the source face to fit the detected face region on the target image.
* **Stable Diffusion Inpainting:** Uses Stable Diffusion to blend the face onto the target image naturally, handling textures and colors smoothly.
* **Customizable Prompts:** Allows input of prompts to guide Stable Diffusion's inpainting process, enhancing blending results.
# Requirements
* Python 3.8 or higher
* Compatible with CUDA-enabled GPUs for faster processing.
# Future Enhancements
* Improve face detection accuracy for complex images.
* Enhance inpainting prompts for better realism.
* Add support for multiple faces in target images.
