# wide-viridis

A colormap inspired by [matplotlib's viridis](https://matplotlib.org/users/colormaps.html),
but with a wider luminance range (i.e. starting at near black, like Magma and Inferno).

|                  | Full color                   | Grayscale                              |
| ---------------- | ---------------------------- | -------------------------------------- |
| **Wide Viridis** | ![](images/wide-viridis.png) | ![](images/wide-viridis-grayscale.png) |
| **Viridis**      | ![](images/viridis.png)      | ![](images/viridis-grayscale.png)      |

Viridis is a popular choice among Matplotlib's perceptually uniform color maps
(which also include also Magma, Inferno and Plasma)
but, like Magma, it doesn't start with black, which may be undesirable to some.

After unsuccessful searches for existing Viridis variants with this property,
I took it upon myself to build such a colormap.
I installed [viscm](https://github.com/matplotlib/viscm) and played with the parameters
until I managed to approximate the tonal appearance of Viridis
while making the scale start at near zero luminance.

Here are some the test images used by `viscm`, for comparison:

| Wide Viridis                       | Viridis                       |
|:----------------------------------:|:-----------------------------:|
| ![](images/wide-viridis-demo1.png) | ![](images/viridis-demo1.png) |
| ![](images/wide-viridis-demo2.png) | ![](images/viridis-demo2.png) |
