# Authenticator-System
A secure authenticator powered by Computer Vision, featuring face ID, liveness checks, and gesture-based input.
# Biometric Authenticator System

A work-in-progress, multi-factor authentication system being built with Python and Computer Vision.

## About This Project

This repository documents the journey of building a secure, multi-layered biometric authentication system from the ground up. The final goal is to create an application that uses a combination of facial recognition, liveness detection, and gesture-based input to verify a user's identity.

Follow along as this project develops from basic modules to a fully integrated system.

---

## 🗺️ Project Roadmap

This project is being built in distinct phases. The current progress is tracked below. As each phase is completed, this list will be updated.

* [ ] **Phase 1: Face Detection**
    * **Goal:** Implement a basic module to detect human faces in a real-time video stream using OpenCV.

* [ ] **Phase 2: Face Recognition**
    * **Goal:** Add the ability to recognize and identify pre-registered users from the video stream.

* [ ] **Phase 3: Liveness Check**
    * **Goal:** Implement eye-blink detection to ensure the subject is a live person and not a static photo.

* [ ] **Phase 4: Air Digit Writer**
    * **Goal:** Develop a gesture recognition module using MediaPipe to allow users to enter a PIN by writing digits in the air.

* [ ] **Phase 5: Final Integration**
    * **Goal:** Combine all completed modules into a single, cohesive application with a simple user interface.

---

## 🛠️ Proposed Tech Stack

The primary technologies I plan to use for this project are:

* **Language:** Python 3.x
* **Libraries:**
    * **OpenCV:** For core computer vision tasks like reading video streams and image processing.
    * **MediaPipe:** For advanced tasks like real-time hand tracking and facial landmark detection.
    * **dlib:** A powerful toolkit for facial landmark detection, crucial for the liveness check.
    * **face_recognition:** A simple yet effective library for face identification.
    * **NumPy:** For efficient numerical calculations and array manipulation.

---

## 🚀 Getting Started (0.0.0)

To run the current, in-development version of this project on your local machine, please follow these steps.

### Prerequisites

* Python 3.8 or higher
* Git

### Fututre Installation Steps

1.  **Clone the repository:**
    ```sh
    git clone [Clone it](https://github.com/Sachinpd-1703/Authenticator-System)
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd Authenticator-System
    ```

3.  **Create and activate a virtual environment (recommended):**
    * On macOS/Linux:
        ```sh
        python3 -m venv venv
        source venv/bin/activate
        ```
    * On Windows:
        ```sh
        python -m venv venv
        .\venv\Scripts\activate
        ```

4.  **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

---

## 💻 How to Run

To run the main script of the application, execute the following command in your terminal:

```sh
python main.py
