<p align="center">
<img src="https://user-images.githubusercontent.com/49370231/167702286-d07ba28a-470b-464a-a78b-cfa8d31676ad.png" width="750">
</p>

This is an interactive educational tool intended to help illustrate the concept of convolution kernels used in convolutional neural networks.

## Installation
Download the repository as a zip file and extract "convolutional-tetris-example.html" and "convolve.js" to the same folder. The html file should run directly in the browser as long as the js file is also in the same directory. Alternatively, the two files can also be uploaded to an existing webserver (for example: https://pitt-photonics.github.io/convolution_example/).

## Usage
This simple interactive tool is designed to help students understand the basic mathematics of how a convolution kernel can be used to identify features in an image. A randomly generated image with tetris blocks is created when the page loads or when the "Create New Tetris Image" button is clicked. Students can edit the values of the 3x3 convolution kernel and then click "Compute Convolution" to see the effect of convolving the kernel across the tetris image. The resulting image on the right displays the output of the convolution operation. For a visual example of how the convolution works to accompany the webpage, check out the [convolutional tetris teaching slides](https://github.com/pitt-photonics/Convolutional-Tetris-Example/files/8664374/convolutional.tetris.teaching.slides.pdf).

A few fun kernels to try:

**Identity:**
| 0 | 0 | 0 |
|--|--|--|
|**0**|**1**|**0**|
|**0**|**0**|**0**|

**Sharpen:**
|-1|-1|-1|
|--|--|--|
|**-1**|**8**|**-1**|
|**-1**|**-1**|**-1**|

**Laplace:**
|1|1|1|
|--|--|--|
|**1**|**-8**|**1**|
|**1**|**1**|**1**|

**Blur:**
|1|1|1|
|--|--|--|
|**1**|**1**|**1**|
|**1**|**1**|**1**|

**Vertical lines:**
|-1|2|-1|
|--|--|--|
|**-1**|**2**|**-1**|
|**-1**|**2**|**-1**|

**Horizontal lines:**
|-1|-1|-1|
|--|--|--|
|**2**|**2**|**2**|
|**-1**|**-1**|**-1**|
