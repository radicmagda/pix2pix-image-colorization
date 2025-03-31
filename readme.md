# Pix2Pix GAN for Image Colorization 🎨🖼️

This project was developed as part of the **[Deep Generative Modeling (Deep Learning 2)](https://www.fer.unizg.hr/en/course/deelea2)** course. It involves training a **Pix2Pix GAN** for the task of **image colorization**.

## Project Structure 📂
- **`src/train.ipynb`** – Notebook for training the GAN(s) 🏋️‍♂️.
- **`src/evaluate.ipynb`** – Notebook for evaluating model performances on different metrics 📊.
- **`results/visualisation.ipynb`** – Notebook for generating graphs and visualizations 📈.
- **`results/`** – Folder containing saved graphs and other outputs 🗂️.
- **`results/report-cro.pdf`** – A detailed report (in Croatian 🇭🇷) explaining the methodology and results 📄.
- **`training_logs/`** – Folder containing losses and colorization attempts troughout the epochs. ⏳📉🖼️

## Dependencies 📦
Ensure you have all required dependencies installed:

```bash
pip install -r requirements.txt
```
## Report
For a comprehensive explanation of the project, refer to [report-cro.pdf](./results/report-cro.pdf)

## Results Examples
Here are some colorization examples on historical black-and-white photographs achieved using our LS-GAN model:
<div style="display: flex; gap: 10px;">
  <img src="results/example_results/kumice.png" width="30%" />
  <img src="results/example_results/kumice_c.png" width="30%" />
</div>
<br>


<div style="display: flex; gap: 10px;">
  <img src="results/example_results/stari_zg.png" width="30%" />
  <img src="results/example_results/stari_zg_c.png" width="30%" />
</div>

<br>

<div style="display: flex; gap: 10px;">
  <img src="results/example_results/nama.png" width="30%" />
  <img src="results/example_results/nama_c.png" width="30%" />
</div>

<br>

And here are some examples taken from the COCO dataset:
<div style="display: flex; flex-direction: column; align-items: center; gap: 20px;">
   <figure style="display: block; text-align: center;">
    <img src="results/example_results/bw.png" width="50%" />
    <figcaption style="display: block;">Black and White</figcaption>
  </figure>
   <figure style="display: block; text-align: center;">
    <img src="results/example_results/lsgan.png" width="50%" />
    <figcaption style="display: block;">Colorized</figcaption>
  </figure>
   <figure style="display: block; text-align: center;">
    <img src="results/example_results/gt.png" width="50%" />
    <figcaption style="display: block;">Ground Truth</figcaption>
  </figure>
</div>