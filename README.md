![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)

## ASR with Google Web Speech API

[![ru](https://img.shields.io/badge/README_на_русском-2A2C39?style=for-the-badge&logo=github&logoColor=white)](README.ru.md)

> A graphics accelerator is not required to run the code.

We will use this [dataset](https://www.kaggle.com/datasets/bryanpark/russian-single-speaker-speech-dataset), which is located on **Kaggle**, as our dataset. To use this dataset, you need to register on **Kaggle**. The metrics we will use are **WER (Word Error Rate)** and **CER (Character Error Rate)**. The paper provides a rationale for using these metrics, a general conclusion on the code's performance, and a comparative analysis based on 5 examples.

 **Google Web Speech API** is a ready-made cloud-based ML model for speech recognition and synthesis, allowing you to add voice features to your applications without training your own models.

 > The magic is performed by the **SpeechRecognition** library. A more detailed code analysis is provided in the paper itself!