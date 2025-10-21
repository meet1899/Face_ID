# Face Recognition app
Build a facial recognitioni app to authenticate into an application. Implemented a model using deep learning with tensorflow, shown in paper titled Siamese Neural Network for One-shot Image Recognition and integrated it into a kivy app. 

### 1. Setup 

- Install Dependencies: Tensorflow, opencv-python, matplotlib

- Import Dependencies:

- Insteasd of Tensorflow's sequential api in this project functional api was used as Functional api is more flexible with intensive deep learning model.

- Siamese Neural Network for One-shot Image Recognition mode is used fro this project.

- Set GPU Growth

- Create Folder Structures

### 2. Collect Positives and Anchors

- Untar Labelled Faces in the Wild Dataset
- Collect Positive and Anchor Classes
- New - Data Augmentation

### 3. Load and Preprocess Images

- Get Image Directories
- Preprocessing - Scale and Resize
- Create Labelled Dataset
- Build Train and Test Partition

### 4. Model Engineering

- Build Embedding Layer
- Build Distance Layer
- Make Siamese Model

### 5. Training

- Setup Loss and Optimizer
- Establish Checkpoints
- Build Train Step Function
- Build Training Loop
- Train the model

### 6. Evaluate Model

- Import Metrics
- Make Predictions
- Calculate Metrics
- Viz Results

### 7. Save Model

### 8. Real Time Test

- Verification Function
- OpenCV Real Time Verification
