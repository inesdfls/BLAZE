# BLAZE

## Objective
Develop a **non-invasive breast tumor detection system** using thermal images and artificial intelligence.  
The algorithm analyzes thermal images captured by an infrared (IR) camera, extracts **thermal signatures** based on the **Pennes bioheat equation**, and classifies tumors into:
- No tumor
- Benign tumor
- Malignant tumor (Grade 1, 2, or 3)

This project is a **collaborative initiative** between **Efrei Paris (France)** and the **Federal University of Rio de Janeiro (Brazil)**.

## Project Pipeline
1. **Capture thermal images** using an IR camera
2. **Extract thermal data matrices** (Tmax, Tenv, T(a))
3. **Generate thermal signatures** based on the Pennes equation
4. **Classify tumors** using AI (neural network / ML model)
5. **Develop a final prototype** integrating hardware and software

## Technologies
- Python
- Pennes bioheat equation (biothermal model)
- Infrared (IR) camera (thermal imaging)
