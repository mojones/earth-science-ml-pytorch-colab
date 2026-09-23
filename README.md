# Plant seedlings: PyTorch classroom notebook

Open the [notebook in Google Colab](https://colab.research.google.com/github/mojones/earth-science-ml-pytorch-colab/blob/main/Deep%20learning%20and%20pytorch%20-%20Colab.ipynb), then select **Runtime → Change runtime type → GPU** and run cells from the top. The GPU is optional; without one, the image example uses fewer epochs. Colab provides `torch` and `torchvision` already.

The notebook automatically downloads the [small, 120-image dataset archive](https://github.com/mojones/earth-science-ml-pytorch-colab/releases/download/v1.0/plant-seedlings-120.zip) (44 MB) on a fresh runtime and checks its SHA-256 digest. It is an 8-training/2-validation-images-per-species teaching demonstration, not a benchmark. The full course notebook and original 1.6 GB `plants/` folder are **not** included here. The matching source notebook lives in the course materials and defaults to CPU; switch the two commented device lines to use Colab/GPU.

## Dataset attribution and license

Original Plant Seedlings Dataset: © 2014 Mads Dyrmann, Peter Christiansen, University of Southern Denmark, and Aarhus University. Images and annotations are licensed under **Creative Commons BY-SA**. The teaching subset contains unmodified images sampled from the source collection; class names and filenames are retained. The archive includes `LICENSE-DATA.txt` and a selection manifest. [Original dataset and full license](https://vision.eng.au.dk/plant-seedlings-dataset/); [dataset paper: Giselsson et al., “A Public Image Database for Benchmark of Plant Seedling Classification Algorithms”](https://arxiv.org/abs/1711.05458). Cite the paper when reusing the data and retain CC BY-SA on redistributed image adaptations.

ResNet18's ImageNet weights are downloaded separately from PyTorch on first use. Google Colab free GPU access is not guaranteed.
