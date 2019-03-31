# Image Segmentation

This notebook introduces some basic techniques for image segmentation, such as the use of *k-means* -a simple yet extremely popular clustering algorithm (also considering its iterative version)- and superpixels algorithm such as *SLIC*, for applying the *Normalized Cut* to the obtained Region Adjacency Graph.

You can download the sample dataset [here](http://download.microsoft.com/download/A/1/1/A116CD80-5B79-407E-B5CE-3D5C6ED8B0D5/msrc_objcategimagedatabase_v1.zip) (from microsoft website).

For more information on k-means implementation, check out [the scikit website](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html).

For further insight into SLIC (superpixeling algorithm), check out [the scikit-image implementation](http://scikit-image.org/docs/dev/api/skimage.segmentation.html#skimage.segmentation.slic), as well as the [original paper](https://ivrl.epfl.ch/research-2/research-current/research-superpixels/).

For additional details about the Normalized Cut algorithm, refer once again to the [original paper](https://people.eecs.berkeley.edu/~malik/papers/SM-ncut.pdf).
