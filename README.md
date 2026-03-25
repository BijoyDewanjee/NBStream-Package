# NBStream-Package 

## 📌 Overview

**NBStream** is a lightweight Python library designed for Data Scientists and Jupyter Notebook users. It enables seamless rendering of live websites and embedding of YouTube videos directly within your `.ipynb` environment (Jupyter Notebook, JupyterLab, Google Colab).

🚀 No more tab switching—view everything right beside your code!

---

## ✨ Features

* 🌐 Website Rendering: Render any HTTPS website directly in an output cell
* ▶️ YouTube Integration: Intelligent parsing of YouTube URLs to embed videos automatically
* 📏 Customizable: Easily adjust width, height, and alignment
* ⚡ Lightweight: Built on top of standard IPython display tools

---

## 📦 Installation

```bash
pip install NBStream
```

---

## 🚀 Usage

### ▶️ YouTube Video Rendering

```python
from NBStream.youtube import render_youtube_video

render_youtube_video("https://www.youtube.com/watch?v=h25pePMdoPA&t=712s")
```

---

### 🌐 Website Rendering

```python
from NBStream.site import render_site

render_site("https://www.google.com")
```

---

## ⚙️ Local Development Setup

```bash
conda create -n nbstream_env python=3.8 -y
conda activate nbstream_env
pip install -r requirements_dev.txt
```

---

## 📁 Project Structure

```bash
NBStream/
│
├── site.py                # Render websites
├── youtube.py            # Render YouTube videos
├── logger.py             # Logging utilities
├── custom_exception.py   # Custom error handling
```

---

## 💡 Why NBStream?

* Perfect for Data Science workflows
* Great for learning and tutorials inside notebooks
* Improves productivity by reducing context switching

---

## 🌍 Supported Environments

* Google Colab
* Jupyter Notebook
* JupyterLab
* Any IPython-based notebook

---

## 👤 Author

**Bijoy Dewanjee**

* GitHub: [https://github.com/BijoyDewanjee](https://github.com/BijoyDewanjee)

---

## 📄 License

This project is licensed under the Apache License.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

---

## ⭐ Acknowledgement

If anyone finds **NBStream** useful, consider giving the repository a ⭐ on GitHub—it helps the project grow!
