# pet_face_detection
Compare CNN architectures for pet face detection (image bounding box regression)

This project assesses performace of different CNN architectures for single object detection in images.

All architectures have the same number of convolutional and FC layers, however, they all differ in placement of dropout layers, and padding used.

Objective is to assess the effect of different dropout layer placements and padding layers on the task of bounding box regression.

=========================================

Notebook directory:

generate flipped images.ipynb : Creates flipped images for dataset augmentation.

pet_face_boxes.ipynb : Loads images and defines, trains, and compares different CNN architectures for bounding box regression.

=========================================

Required Project Directory Structure:

Project
- images (folder containing all image data) <br>
- annotations <br>
- - xmls (folder containing all bounding box xml annotations) <br>
- generate flipped images.ipynb <br>
- pet_face_boxes.ipynb <br>

==========================================

Link to dataset- https://www.robots.ox.ac.uk/~vgg/data/pets/



