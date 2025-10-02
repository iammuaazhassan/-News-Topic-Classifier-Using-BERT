# 📰 News Topic Classifier Using BERT

## 📌 Objective
This project fine-tunes a transformer model (**BERT**) to classify **news headlines** into topic categories using the **AG News dataset**. It demonstrates dataset preprocessing, transfer learning, model evaluation, and deployment with **Gradio**.

---

## 📊 Dataset
The project uses the **AG News Dataset** from Hugging Face Datasets, containing **4 balanced categories**:
- 🌍 World
- 🏀 Sports
- 💼 Business
- 🔬 Sci/Tech

---

## 🚀 Training
Run the training script:
```bash
python train.py
```

---

## 📈 Results
The fine-tuned BERT model achieved strong performance on validation data:

| Epoch | Validation Loss | Accuracy | F1-Macro |
|-------|-----------------|----------|----------|
| 1     | 0.228           | 92.6%    | 0.923    |
| 2     | 0.285           | 92.0%    | 0.917    |

---

## 📊 Visualizations
The following visualizations were generated:
- Class distribution in the dataset
- Training vs Validation loss curves
- Accuracy and F1-score trends
- Confusion Matrix
- Probability distribution for sample inputs

---

## 🌐 Deployment
Run the Gradio app:
```bash
python app.py
```

### Example Inputs
- "UN approves new peacekeeping mission in Africa" → World
- "Manchester United secures dramatic victory in Champions League" → Sports
- "Tesla reports record profits in quarterly earnings" → Business
- "NASA announces discovery of water on Mars" → Sci/Tech

---

## 🛠️ Skills Gained
- NLP with Transformers
- Transfer learning & fine-tuning BERT
- Evaluation metrics (Accuracy, F1-score)
- Model deployment with Gradio
- Visualization of model performance

---

## 📜 License
This project is licensed under the **MIT License**.
