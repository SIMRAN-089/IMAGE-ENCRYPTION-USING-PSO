# 🔐 Image Encryption Using PSO (Particle Swarm Optimization)

This project implements an image encryption technique using **Particle Swarm Optimization (PSO)** to generate highly random and secure encryption keys. The encryption scheme enhances traditional XOR-based encryption by integrating optimized key generation via metaheuristic algorithms.

---

## 📌 Features

- Grayscale image encryption using XOR and PSO
- High entropy & low pixel correlation for strong encryption
- Performance metrics: Histogram, Entropy, NPCR, UACI
- Decryption restores original image with high accuracy
- Streamlit-based web interface for demo and testing

---

## 📚 Technologies Used

- **Python**
- **OpenCV** for image processing
- **NumPy** for matrix operations
- **Matplotlib** for visualization
- **Streamlit** for web deployment

---

## ⚙️ How It Works

### 🔐 Encryption Process
1. **Preprocessing**: Convert image to grayscale and matrix format.
2. **PSO Key Generation**: Use PSO to generate optimized encryption key.
3. **XOR Encryption**: Apply XOR between image and key matrix.
4. **Decryption**: Use the same XOR operation with the key to restore the image.

---

## 🧪 Performance Metrics

| Metric           | Value                     |
|------------------|---------------------------|
| **Entropy**      | ~7.99                     |
| **NPCR**         | 99.3%                     |
| **UACI**         | 33.5%                     |
| **Encryption Time** | ~0.85 seconds         |
| **Decryption Time** | ~0.82 seconds         |

---

