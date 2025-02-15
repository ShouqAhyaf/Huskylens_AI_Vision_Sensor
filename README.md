# Huskylens AI Vision Sensor
The Huskylens AI Vision Sensor is an intuitive and powerful tool designed to bring artificial intelligence (AI) into your projects seamlessly. Whether you're a beginner or an experienced developer, this smart sensor makes object and face recognition simple and accessible. With built-in machine learning capabilities, Huskylens can detect faces, objects, and even colors in real-time, offering endless possibilities for robotics, smart devices, and more.

A standout feature of Huskylens is its Face Recognition system. It assigns a unique Face ID to each face it detects, storing the ID for future recognition. When the same face appears again, Huskylens retrieves the stored ID and can easily identify the person. This feature also allows you to assign custom names to Face IDs for easier recognition, making it perfect for use in security systems, robotics, and interactive applications.

## Key Features:
- **Real-time Object and Face Recognition:** Instantly detects faces, objects, and colors, ideal for a wide range of applications such as robotics and smart cameras.
- **User-Friendly:** No advanced programming knowledge is required. Huskylens simplifies AI integration, making it easy for anyone to get started.
- **Flexible Compatibility:** Works with development platforms like Arduino, Micro:bit, and more, allowing for versatile project possibilities.
- **Compact and Lightweight:** Its small design is perfect for portable projects or those with space constraints.
- **Built-in Machine Learning:** Huskylens comes pre-trained with AI models, so you can use face and object recognition features without any complex setup.

# 🚀 Project: Face Recognition using Huskylens (Arduino)

## Requirements: 
### 🛠️ Hardware:
- Huskylens AI Camera
- Arduino Uno (or compatible board)
- Jumper wires (for I2C connection)

### 💾 Software:
- Arduino IDE
- Huskylens Library (install via Library Manager)

🔧 **Wiring Huskylens to Arduino (I2C)**  
| Huskylens | Arduino |
|-----------|---------|
| VCC       | 5V      |
| GND       | GND     |
| SDA       | 10      |
| SCL       | 11      |

## 🎯 How Face Recognition Works?
1. Huskylens detects a face and assigns it a unique Face ID.
2. The Face ID is stored in memory for future use.
3. When the same face is detected, Huskylens retrieves the stored ID, recognizing the individual.
4. You can assign custom names to specific Face IDs for easier identification.

## 🖼️ Huskylens Output
![image](https://github.com/user-attachments/assets/506341d2-3908-4dae-8082-ee41233338c0)

## Troubleshooting
🔹 Huskylens Issues
- Ensure Huskylens is properly wired and trained for recognition.
- Make sure the device is in Face Recognition Mode for accurate results.



With Huskylens, you can easily implement face and object recognition into your projects, making it ideal for smart devices, robots, and security applications. Its ease of use and versatile capabilities open up endless possibilities, allowing you to dive into the world of AI without the complexity of traditional programming.
