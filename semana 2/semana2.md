```python
# First of all, generate the histogram for the original image (with BGR colors)

color = ('b', 'g', 'r')
for i in imgs_urls:
    fig, (ax1,ax2,ax3) = plt.subplots(1, 3, figsize=(20, 10))

    ax1.set_title("Original Image")
    ax1.imshow(i)

    ax2.set_title("Histogram of all the pixels in the image")
    ax2.hist(i.ravel(), bins = 256, range = [0,256])

    ax3.set_title("Histogram of R,G,B channels")
    for idx, col in enumerate(color):
        ax3.hist(i[:, :, idx].ravel(), bins = 256, range = [0,256], color=col, label = col, alpha=0.5)
        ax3.set_xlim([0,256])


    ax3.legend()
    fig.suptitle('Images and its histogram')
    plt.tight_layout()
    plt.show()



```
