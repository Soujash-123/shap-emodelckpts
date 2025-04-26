# Cap3D Text-to-3D Fine-Tuning

This repository contains code and resources for **Cap3D Text-to-3D Fine-Tuning**.
Due to the size of the models and datasets (greater than 1GB), **we are using Google Drive and Google Colab** instead of hosting them directly on GitHub or HuggingFace, since both platforms have limitations even with Git LFS.

## 📂 Resources

- **Google Drive Link (Models & Datasets):**  
  [Download from Google Drive](https://drive.google.com/file/d/1GQOZFfAMJ4parzt6Amjvy-5Wzqb5CpxC/view?usp=share_link)

- **Google Colab Notebook (Code & Execution):**  
  [Open Colab Notebook](https://colab.research.google.com/drive/1tjvLwHo2LO3KW7ulThWIEF1l3jft4G3j?usp=sharing)

## 🚀 Summary of the Notebook

1. **Clone Repository:** Clones the Cap3D GitHub repository.
2. **Setup Environment:** Checks Python version, installs required libraries like Gradio.
3. **Download Models:** Uses `gdown` to download large model files from Google Drive.
4. **Model Preparation:** Moves model checkpoints to appropriate folders and cleans up.
5. **Load Models:** Loads Shap-E pre-trained models (`text300M` and `transmitter`) and saves their state_dicts.
6. **Fine-tuning/Inference Setup:** Prepares configuration for sampling 3D meshes from text prompts.

## 📰 Screenshots

| Screenshot 1 | Screenshot 2 | Screenshot 3 |
|:------------:|:------------:|:------------:|
| ![Screenshot 1](Screenshot1.jpeg) | ![Screenshot 2](Screenshot2.jpeg) | ![Screenshot 3](Screenshot3.jpeg) |

## ⚠️ Note

- Make sure you have access permission to the shared Google Drive link.
- Ensure sufficient free space in your Google Drive if you copy the resources.

## 📄 License

[Specify your project's license here]

---

Feel free to open an issue if you face any problems!

