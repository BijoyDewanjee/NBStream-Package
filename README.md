# NBStream-Package

[![PyPI version](https://img.shields.io/pypi/v/NexusViewPro.svg)](https://pypi.org/project/NexusViewPro/)
[![Python versions](https://img.shields.io/pypi/pyversions/NexusViewPro.svg)](https://pypi.org/project/NexusViewPro/)
[![License](https://img.shields.io/pypi/l/NexusViewPro.svg)](https://github.com/entbappy/NexusViewPro/blob/main/LICENSE)

**NBStream** is a lightweight Python library designed for Data Scientists and Jupyter Notebook users. It enables you to seamlessly render live websites and embed YouTube videos directly inside your `.ipynb` environment (Jupyter Notebook, JupyterLab, Google Colab).

🚀 No more tab switching—view everything right beside your code!

## ✨ Features

- **🌐 Website Rendering:** Render any HTTPS website directly in an output cell.
- **▶️ YouTube Integration:** intelligent parsing of YouTube URLs to embed the video player automatically.
- **📏 Customizable:** easily adjust width, height, and alignment of the viewport.
- **⚡ Lightweight:** Zero heavy dependencies; built on top of standard IPython display tools.


## 📦 Installation

You can install NBStream via pip:

```bash
pip install NBStream
```

```python
from NBStream.youtube import render_youtube_video

render_youtube_video("https://www.youtube.com/watch?v=h25pePMdoPA&t=712s")
```

```python
from NBStream.site import render_site

render_site("https://www.google.com")
```


# How to Install this package in Your System

```bash
conda create -n nbstream_env python=3.8 -y
```

```bash
conda activate nbstream_env
```

```bash
pip install -r requirements_dev.txt
```

## 📁 Project Structure

<pre class="overflow-visible! px-0!" data-start="1772" data-end="1982"><div class="relative w-full mt-4 mb-1"><div class=""><div class="relative"><div class="h-full min-h-0 min-w-0"><div class="h-full min-h-0 min-w-0"><div class="border border-token-border-light border-radius-3xl corner-superellipse/1.1 rounded-3xl"><div class="h-full w-full border-radius-3xl bg-token-bg-elevated-secondary corner-superellipse/1.1 overflow-clip rounded-3xl lxnfua_clipPathFallback"><div class="pointer-events-none absolute end-1.5 top-1 z-2 md:end-2 md:top-1"></div><div class="pe-11 pt-3"><div class="relative z-0 flex max-w-full"><div id="code-block-viewer" dir="ltr" class="q9tKkq_viewer cm-editor z-10 light:cm-light dark:cm-light flex h-full w-full flex-col items-stretch ͼ5 ͼj"><div class="cm-scroller"><div class="cm-content q9tKkq_readonly"><span>NBStream/</span><br/><span>│</span><br/><span>├── site.py                # Render websites</span><br/><span>├── youtube.py            # Render YouTube videos</span><br/><span>├── logger.py             # Logging utilities</span><br/><span>├── custom_exception.py   # Custom error handling</span></div></div></div></div></div></div></div></div></div><div class=""><div class=""></div></div></div></div></div></pre>

---

## 💡 Why NBStream?

* Perfect for **Data Science workflows**
* Great for **learning & tutorials inside notebooks**
* Improves **productivity by reducing context switching**

---

## 🌍 Supported Environments

* Google Colab
* Jupyter Notebook
* JupyterLab
* Any IPython-based notebook interface

---

## 👤 Author

**Bijoy Dewanjee**

* PyPI: [Bijoy07]()
* GitHub: [https://github.com/BijoyDewanjee](https://github.com/BijoyDewanjee)

---

## 📄 License

This project is licensed under the  Apache License .

Feel free to use, modify, and distribute it in your projects.

---



## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo, open issues, or submit pull requests.

---


## ⭐ Acknowledgement

If Anyone find **NBStream**  useful, consider giving the repository a ⭐ on GitHub—it helps the project grow!
