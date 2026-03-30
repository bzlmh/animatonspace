### Enhancing the Expressive Power of Text by Animating Paired Infographic Charts

---

## 📌 Abstract

Infographic charts are widely used alongside textual content to enhance information communication in real-world scenarios (e.g., digital newspapers). In such contexts, animations are often employed to guide the audience’s attention toward chart regions relevant to the accompanying text. 

While numerous automatic animation generation methods have been proposed to reduce the time and effort required for creating such animations, most are designed for simple charts and fail to capture the complex animation patterns inherent in infographic charts (e.g., nested and coordinated animations).

To address this limitation, we collected a dataset of **1,082 infographic chart animations** from reputable sources. Through in-depth analysis with domain experts, we constructed a comprehensive design space consisting of four key dimensions: **Message**, **Scene**, **Character**, and **Plot**, which effectively characterize infographic animation patterns.

Based on this design space, we propose **InfoDirector**, an interactive system for generating infographic chart animations conditioned on input text. To support accurate element parsing, we further annotated **2,827 infographic charts** and fine-tuned a pretrained detection model, achieving **state-of-the-art performance**.

Finally, a comprehensive user study involving **60 participants** demonstrates that our approach significantly outperforms baseline methods in terms of **data comprehension**, **expressiveness**, and **visual attractiveness**.

---

## ✨ Key Contributions

- **Design Space for Infographic chart Animation**
  - Introduced a structured design space with four dimensions:
    - **Message**
    - **Scene**
    - **Character**
    - **Plot**
  - Captures complex animation patterns specific to infographic charts

- **InfoDirector System**
  - Developed an interactive system for generating animations from textual descriptions
  - Bridges the gap between semantic understanding and visual storytelling
- **User Study**
  - Evaluated with **60 participants**
  - Demonstrates clear advantages in:
    - Data comprehension  
    - Expressiveness  
    - Visual attractiveness  

---

## 🖥️ Features

- Text-driven infographic animation generation  
- Fine-grained semantic alignment between text and visual elements  
- Support for complex and nested infographic structures  
- Interactive workflow for animation design and refinement  

---

## 🚧 Project Status

This project is currently under active development.

The source code, demo system, and dataset will be publicly released upon publication.
