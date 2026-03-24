<h1 align="center">🔢 DigitGen – VAE Latent Space Explorer</h1>

<p align="center">
Interactive Generative AI Web App using Variational Autoencoder (VAE)
</p>

<hr>

<h2>🧠 Overview</h2>
<p>
DigitGen is a generative AI project that uses a Variational Autoencoder (VAE)
to generate handwritten digits from latent space representations.
</p>

<p>
Users can interactively manipulate latent variables and observe how they affect generated outputs.
</p>

<hr>

<h2>🚀 Features</h2>
<ul>
  <li>Generate handwritten digits using VAE</li>
  <li>Interactive latent space sliders</li>
  <li>Real-time image generation</li>
  <li>Lightweight Streamlit web app</li>
</ul>

<hr>

<h2>🛠 Tech Stack</h2>
<ul>
  <li>Python</li>
  <li>PyTorch</li>
  <li>Streamlit</li>
  <li>NumPy</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>
<pre>
digitgen-vae/
│
├── app.py
├── train.py
├── vae.pth
├── requirements.txt
└── README.md
</pre>

<hr>

<h2>▶️ Run Locally</h2>
<pre>
pip install -r requirements.txt
python train.py
streamlit run app.py
</pre>

<hr>

<h2>🧪 How It Works</h2>
<ul>
  <li>Encoder maps input images into a latent space</li>
  <li>Latent vectors are sampled using the reparameterization trick</li>
  <li>Decoder generates new images from latent vectors</li>
</ul>

<hr>

<h2>📊 Concepts Covered</h2>
<ul>
  <li>Variational Autoencoders (VAE)</li>
  <li>Latent Space Representation</li>
  <li>Probabilistic Modeling</li>
  <li>Deep Learning Deployment</li>
</ul>

<hr>

<h2>📌 Future Improvements</h2>
<ul>
  <li>Latent interpolation animation</li>
  <li>Conditional VAE (digit control)</li>
  <li>Save generated images</li>
  <li>Deploy on Streamlit Cloud</li>
</ul>

<hr>

<p align="center">
Built with ❤️ for AI Engineering Portfolio
</p>
