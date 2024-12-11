# Plant Classification System

## Overview
The **Plant Classification System** is a project designed to detect and count the number of leaves in a plant image using image processing and machine learning techniques. This system aids in agricultural analysis by automating leaf detection, which can help monitor plant health and growth.

---

## Features
- Detect and count the number of leaves in a plant image.
- Preprocess images for better accuracy (filtering, normalization, and augmentation).
- Employ machine learning models for robust detection and classification.
- User-friendly interface for uploading images and viewing results.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - OpenCV (Image processing)
  - TensorFlow/Keras (Deep learning)
  - NumPy and Pandas (Data handling)
  - Matplotlib (Visualization)
- **Frameworks**:
  - Flask/Django (Web application, optional)

---

## Prerequisites
- Python 3.8 or above
- Install required dependencies:
  ```bash
  pip install -r requirements.txt
  ```

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nehaabhalerao/plant-classification-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd plant-classification-system
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage
1. Prepare the dataset:
   - Place plant images in the `data/images` directory.
   - Ensure each image is properly labeled (if supervised learning is used).

2. Run the preprocessing script:
   ```bash
   python preprocess.py
   ```

3. Train the model:
   ```bash
   python train_model.py
   ```

4. Test the system with sample images:
   ```bash
   python test_system.py --image path/to/image.jpg
   ```

5. (Optional) Launch the web application:
   ```bash
   python app.py
   ```
   Access the application at `http://localhost:5000`.

---

## Project Structure
- `data/`: Contains datasets (images and annotations).
- `models/`: Stores trained machine learning models.
- `scripts/`: Includes preprocessing, training, and testing scripts.
- `app.py`: Launches the web interface.

---

## Future Enhancements
- Improve model accuracy with larger datasets.
- Add support for multi-class plant classification.
- Deploy the system on cloud platforms for real-time usage.

---

## Contributors
- [Your Name](https://github.com/nehaabhalerao)

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

