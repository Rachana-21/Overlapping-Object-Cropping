# Overlapping-Object-Cropping


Detect and crop hand regions(primary object(occluding part)) that overlap or occlude faces using RGB images and binary masks.

---

##  Objective

To detect hand regions(primary object) overlapping with faces and crop only those parts using computer vision techniques like face detection and contour overlap.

---

##  How It Works

1. Mount Google Drive and extract dataset.
2. Read RGB images and hand masks.
3. Detect faces using Haar Cascade.
4. Detect hands from binary masks.
5. Crop hand region if it overlaps with a face.
6. Save and display the cropped outputs.

---



