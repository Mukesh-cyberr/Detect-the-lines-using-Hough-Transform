#  Lane Detection

##  Aim

To implement a basic lane detection pipeline using OpenCV by completing missing code segments at specified locations.

---

## Learning Objective

* Understand each stage of image processing
* Learn how to build a complete computer vision pipeline
* Practice writing code in guided sections

**Important Instruction:**
👉 Write code **ONLY in places marked as `# Your Code Here`**
👉 Do NOT modify any other part of the code

---

##  Software Used

* Anaconda – Python 3.7
* Jupyter Notebook / VS Code
* OpenCV (cv2)
* NumPy
* Matplotlib

---

##  Algorithm & Explanation

---

###  Step 1: Import Libraries

```python
import cv2
import numpy as np
import matplotlib.pyplot as plt
```

---

###  Step 2: Read the Image

```python
# Read the image using OpenCV

image = cv2.imread('Qn_7_.jpg')  # Replace 'image.jpg' with your image path

```

---

###  Step 3: Convert to Grayscale

```python
# Convert to grayscale.

gray_image = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)
```

---

###  Step 4: Display Images

```python
plt.imshow(cv2.cvtColor(image, cv2.COLOR_BGR2RGB))  # Convert image to RGB for displaying
plt.title("Input Image")
plt.axis('off')
print("Mukesh Raj D")
print("212224100038")
```

---

###  Step 5: Gray Scale

```python
plt.imshow(gray_image, cmap='gray')
plt.title("Grayscale Image")
plt.axis('off')
print("Mukesh Raj D")
print("212224100038")
```


### Step 6: Edge Detection (Canny)

```python
# Perform Edge Detection
plt.imshow(edges, cmap='gray')
plt.title("Canny Edge Detector")
plt.axis('off')
print("Mukesh Raj D")
print("212224100038")
```

###  Step 7: Hough Transform

```python

plt.imshow(cv2.cvtColor(image, cv2.COLOR_BGR2RGB))  # Image with lines drawn
plt.title("Result of Hough Transform")
plt.axis('off')
print("Mukesh Raj D")
print("212224100038")
```


##  Expected Output

* Original image

  <img width="637" height="525" alt="image" src="https://github.com/user-attachments/assets/d8055fd0-9d40-43d0-9071-9d5bf9c7a83c" />

* Grayscale image

  <img width="769" height="520" alt="image" src="https://github.com/user-attachments/assets/c593944e-0a2b-4e00-b945-1f18230c23cc" />

* Edge detected image

  <img width="645" height="530" alt="image" src="https://github.com/user-attachments/assets/a51abe64-f3ab-48f5-b1c9-d19a1bb09d73" />

* Detected lines

  <img width="689" height="531" alt="image" src="https://github.com/user-attachments/assets/32ebb440-d90b-43ef-81fb-0eddad175e3b" />


---

##  Instructions

* Fill ONLY in `# Your Code Here` sections
* Do NOT change existing code
* Run step-by-step
* Verify outputs

---

## Result

Thus, the lane detection pipeline is successfully implemented by completing the missing code sections. The system detects and highlights lane lines effectively.

---

##  Developed By

* **Name:** Mukesh Raj D
* **Register No:** 212224100038
