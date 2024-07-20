### Project Description: Image Similarity Measurement using ORB Feature Matching and Percentage Calculation

#### Objective:
The objective of this project is to develop a system that compares two images and determines their similarity as a percentage. This is achieved by using feature extraction and matching techniques to identify common visual elements between the images.

#### Overview:
This project utilizes the Oriented FAST and Rotated BRIEF (ORB) algorithm, a robust and efficient method for detecting keypoints and computing descriptors. By preprocessing the images, extracting features, and measuring the similarity between these features, we can quantify the similarity between the images.

#### Key Steps:
1. **Preprocessing:**
   - **Resize Images:** Standardize the size of the input images to ensure uniformity and reduce computational complexity.
   - **Grayscale Conversion:** Convert images to grayscale to simplify the feature extraction process.

2. **Feature Extraction:**
   - **ORB Algorithm:** Detect keypoints and compute descriptors for each image using the ORB algorithm. ORB is chosen for its efficiency and robustness in handling various image transformations.

3. **Feature Matching:**
   - **Brute Force Matcher:** Use a Brute Force Matcher with Hamming distance to match the descriptors of the two images. This step identifies common features between the images.

4. **Similarity Measurement:**
   - **Match Percentage Calculation:** Calculate the match percentage by comparing the number of matches to the total number of keypoints. This provides a quantitative measure of the similarity between the images.

#### Applications:
- **Image Retrieval Systems:** Enhance the accuracy of image search engines by identifying similar images.
- **Duplicate Detection:** Identify duplicate or near-duplicate images in large datasets.
- **Quality Assurance:** Compare images in manufacturing processes to ensure product consistency.

#### Tools and Libraries:
- **OpenCV:** An open-source computer vision library used for image processing and feature extraction.

#### Conclusion:
This project demonstrates a practical approach to measuring image similarity using advanced feature extraction and matching techniques. The resulting match percentage provides a clear and intuitive measure of how similar two images are, enabling a wide range of applications in various fields.

#### Implementation:
The implementation is done using Python and OpenCV, with a straightforward workflow that includes preprocessing, feature extraction, feature matching, and similarity measurement. The provided code serves as a foundation for further enhancements and customization based on specific requirements.

This project is ideal for those looking to explore computer vision techniques and apply them to real-world problems involving image comparison and similarity measurement.

## SAMPLE IMAGES - LINK
https://drive.google.com/drive/folders/1L921lIv1_isNw-qpl_3fBECCp68TMusQ?usp=sharing
