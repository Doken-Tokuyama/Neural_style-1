Pytorch implementation of "Image Style Transfer Using Convolutional Neural Networks"
---

Pytorch implementation of the paper:
"Image Style Transfer Using Convolutional Neural Networks"
Leon A. Gatys, Alexander S. Ecker, Matthias Bethge,
CVPR 2016

Dependencies
--
* Pytorch (version >= 0.4.0)

Usage example
--
```
python main.py --cuda-device-no 0 --target-content-filename sample_images/content_images/chicago.jpg --target-style-filename sample_images/style_images/mondrian.jpg --save-filename stylized.png
```
