# 🧙‍♂️ Invisibility Cloak using OpenCV

Make yourself disappear—just like Harry Potter!  
This project uses OpenCV to detect a red-colored cloth (cloak) and replaces it with the background, creating the illusion of invisibility.

---

## 🧠 How It Works

This project captures the static background first, then:
- Detects red-colored pixels in the video feed
- Replaces those red pixels with the previously captured background
- Combines both to make it look like the cloak is invisible

---

## 🔧 Technologies Used

- Python
- OpenCV
- NumPy

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/parr129/invisibility-cloak-opencv.git
cd invisibility-cloak-opencv
