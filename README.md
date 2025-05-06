
# StyleGAN3-IDS: IoT Intrusion Detection with Enhanced Generative Adversarial Networks

This repository contains the source code and dataset used for the research paper titled:

**"StyleGAN3-IDS: IoT Intrusion Detection with Enhanced Generative Adversarial Networks"**  
Authored by: Vijaya Vardan Reddy S P and Jaison B  
Affiliation: R.M.K. Engineering College, Tamil Nadu, India  

## 📌 Project Overview

StyleGAN3-IDS is a novel deep learning-based intrusion detection framework for Internet of Things (IoT) networks. It leverages StyleGAN3 to generate synthetic network traffic that augments real IoT traffic data, thereby improving the performance of anomaly detection systems.

The proposed model:
- Enhances training diversity with synthetic data generation
- Reduces false positives and false negatives
- Outperforms traditional IDS methods like SVM, CGAN, and BigGAN

## 🗃️ Contents

- `IoT_Intrusion_detection.ipynb`: Jupyter Notebook containing the full implementation of StyleGAN3-IDS
- `IoTID20.csv`: Dataset used for training and evaluation (IoTID20)
- `README.md`: Project documentation
- `requirements.txt`: Dependencies for environment setup (to be added if needed)

## 📊 Dataset

**IoTID20**  
- 225,744 records | 79 features  
- Binary labels: `Normal` / `Anomaly`  
- Includes various IoT attack types (e.g., DDoS, Port Scanning)

📁 File: `IoTID20.csv`

## ⚙️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stylegan3-ids.git
   cd stylegan3-ids
   ```

2. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the notebook:
   ```bash
   jupyter notebook IoT_Intrusion_detection.ipynb
   ```

## 📈 Performance Metrics

| Metric       | StyleGAN3-IDS |
|--------------|----------------|
| Accuracy     | 95.4%          |
| Precision    | 92%            |
| Recall       | 93%            |
| F1 Score     | 92.5%          |
| ROC-AUC      | 0.99           |

## 🧠 Architecture

- Generator: StyleGAN3
- Discriminator: Deep CNN
- Training: Adversarial (Minimax)
- Inference: Discriminator-based anomaly scoring

## 📎 Citation

If you use this code or dataset in your research, please cite the original paper:

```
@article{stylegan3ids2025,
  title={StyleGAN3-IDS: IoT Intrusion Detection with Enhanced Generative Adversarial Networks},
  author={Vijaya Vardan Reddy S P and Jaison B},
  journal={In Submission},
  year={2025}
}
```

## 📬 Contact

For any queries or collaboration:
- 📧 Email: spr.ece@rmkec.ac.in | bjn.cse@rmkec.ac.in
