# 💻 Laptop Price Predictor using Machine Learning

![image](https://github.com/user-attachments/assets/6c5f6c21-9710-4d2d-b7cf-0a20286b5c7b)
![image](https://github.com/user-attachments/assets/655b05f9-808e-40f2-9a60-5093aa10afb2)

This project is a machine learning-powered web application that predicts the price of a laptop based on various hardware specifications such as brand, type, RAM, storage (SSD/HDD), GPU, CPU, operating system, screen size, resolution, IPS technology, and touchscreen availability. Built using **Streamlit** for the frontend and **scikit-learn** for modeling, this app allows users to input their desired configuration and instantly receive an estimated laptop price. The model was trained on a real-world dataset and uses a pipeline with preprocessing and regression to ensure accurate predictions.

The backend ML pipeline (serialized using `pickle`) includes feature engineering steps such as calculating PPI (pixels per inch) from screen resolution and size, and transforming categorical inputs. The app interface is user-friendly and interactive, with dropdowns and sliders to select laptop features. This tool is ideal for students, professionals, and resellers looking to estimate market prices for custom configurations quickly and efficiently.
