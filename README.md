Pytorch implementation of "Image Style Transfer Using Convolutional Neural Networks"
---

Pytorch implementation of the paper:
"Image Style Transfer Using Convolutional Neural Networks"

Leon A. Gatys, Alexander S. Ecker, Matthias Bethge

CVPR 2016

Dependencies
--
* Pytorch (version >= 0.4.0)

Usage
--

* Test example script

```
python main.py --cuda-device-no 0 --target-content-filename sample_images/content_images/chicago.jpg --target-style-filename sample_images/style_images/mondrian.jpg --save-filename stylized.png
```

Example images
--

* Content image: sample_images/content_images/chicago.jpg
* Style image: sample_images/style_images/mondrian.jpg

![test_result](https://github.com/tyui592/Neural_style/blob/master/sample_images/test_results/chicago_mondrian.png)

* Content image: sample_images/content_images/chicago.jpg
* Style image: sample_images/style_images/abstraction.jpg

![test_result2](https://github.com/tyui592/Neural_style/blob/master/sample_images/test_results/chicago_abstraction.png)

