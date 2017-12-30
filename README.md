# wide-viridis

A colormap inspired by matplotlib's viridis, but with wider luminance range.

![](wide-viridis.png) ![](wide-viridis-grayscale.png)

![](viridis.png) ![](viridis-grayscale.png)

Viridis is a popular choice among Matplotlib's perceptually uniform color maps
(which also include also Magma, Inferno and Plasma)
but, like Magma, it doesn't start with black, which may be undesirable to some.

After unsuccessful searches for existing Viridis variants with this property,
I took it upon myself to build such a colormap.
I installed [viscm](https://github.com/matplotlib/viscm) and played with the parameters
until I managed to approximate the tonal appearance of Viridis
while making the scale start at near zero luminance.

Here are some more images for comparison:

![](wide-viridis-demo1.png) ![](viridis-demo1.png)

![](wide-viridis-demo2.png) ![](viridis-demo2.png)
