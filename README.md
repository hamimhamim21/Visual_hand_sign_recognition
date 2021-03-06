# Visual hand sign recognition

In this work, we train a neural network on images that I recorded of my hand, to identify how many fingers I am holding up - resulting in an almost 100% accuracy. This is then used for a localisation script, which finds an image of my hand in a larger image. This can be generalised to multiple pictures of hands in one image.

- `CCTV_cloud.ipynb`: Main Jupyter notebook, with brief walkthrough of code.

- `CCTV_gathering_data.ipynb`: Supplementary notebook, for collecting images from a webcam.

![Finger detection](/graphs_outputs/ident.png)

<br>

![Localisation](/graphs_outputs/local.png)
