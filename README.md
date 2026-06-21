# Convolution and Its Applications
![Topic](https://img.shields.io/badge/Topic-Mathematical%20Analysis-blue)
![Field](https://img.shields.io/badge/Field-Signal%20%26%20Image%20Processing-purple)
![Domain](https://img.shields.io/badge/Domain-Functional%20Analysis%20-orange)
![Exhibition](https://img.shields.io/badge/Exhibition-Sapienza%2024-red)

This repository features the core theoretical concepts, equations, and diverse applied fields of **Convolution and Deconvolution**. This work was curated and presented as an academic poster at **Sapienza, the National Science Day Exhibition (March 2024)** at Mount Carmel College.

---

## 📊 View the Exhibition Poster
The full, high-resolution research poster can be found here:
📁 **[View Exhibition Poster (`Convolution.png`)](./Convolution.png)**

---

## 🧠 01. What is a Convolution?
In mathematics (specifically functional analysis), a **convolution** is a mathematical operation on two functions ($f$ and $g$) that produces a third function ($f * g$). The term refers to both the resulting function and the mathematical process of computing it.

## 📐 02. Mathematical Framework
The convolution of two functions involves integrating the product of one function reflected and shifted over the other, resulting in the convolution function:

$$C(u) = f(x) \otimes g(x) = \int_{\text{space}} f(x)g(u - x)dx$$

Due to the commutative property of convolution:

$$= g(x) \otimes f(x) = \int_{\text{space}} g(x)f(u - x)dx$$

---

## 🛠️ 03. Core Applications of Convolution
Convolution is a foundational cornerstone across physics, data science, and engineering hardware:
1. **Image Processing:** Used for spatial filtering operations like edge detection, sharpening, and blurring kernels.
2. **Artificial Neural Networks (ANNs & CNNs):** Forms the foundational forward-pass mechanics of Convolutional Layers to automatically extract local geometric features.
3. **Signal Filtering & Audio Processing:** Modifying the frequency dynamics of audio or data streams via continuous-time impulse responses.
4. **Polynomial Multiplication:** Streamlining mathematical operations by treating coefficients as discrete data arrays.
5. **Computed Tomography (CT) & Optics:** Reconstructing spatial volumetric maps from projected cross-sectional data paths.

---

## 🔄 04. Deconvolution & Deep Domain Applications
**Deconvolution** is the process of reversing a convolution operation, aiming to isolate and retrieve the original signals or inputs from a convolved/distorted output.

### Specialized Fields of Application:
* **Seismology & Synthesized Seismographs:** Separating source wavelet signatures from geological structural reflections.
* **Radio Astronomy:** De-blurring telescope point-spread functions to clear up deep-space imagery.
* **Absorption Spectra:** Resolving overlapping spectral data points to isolate distinct chemical compounds.
* **Biology & Medical Devices:** Enhancing microscopic focal plains and clarifying cellular imagery tracks.
