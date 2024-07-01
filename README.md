#  Image Blurring refers to making the image less clear or distinct. It is done with the help of various low pass filter kernels. Advantages of blurring:
It helps in Noise removal. As noise is considered as high pass signal so by the application of low pass filter kernel we restrict noise.
It helps in smoothing the image.
Low intensity edges are removed.
It helps in hiding the details when necessary. For e.g. in many cases police deliberately want to hide the face of the victim, in such cases blurring is required.

# Important types of blurring:
Gaussian Blurring:
Gaussian blur is the result of blurring an image by a Gaussian function. It is a widely used effect in graphics software, typically to reduce image noise and reduce detail. It is also used as a preprocessing stage before applying our machine learning or deep learning models. 

Median Blur:
The Median Filter is a non-linear digital filtering technique, often used to remove noise from an image or signal. Median filtering is very widely used in digital image processing because, under certain conditions, it preserves edges while removing noise. It is one of the best algorithms to remove Salt and pepper noise.

Bilateral Blur:
A bilateral filter is a non-linear, edge-preserving, and noise-reducing smoothing filter for images. It replaces the intensity of each pixel with a weighted average of intensity values from nearby pixels. This weight can be based on a Gaussian distribution. Thus, sharp edges are preserved while discarding the weak ones.

# Sample Image
![download](https://github.com/RidhiSood22/Image-preprocessing---Image-Blur/assets/142926361/b49f5f42-ae31-4f2d-b189-bea00be320af)
