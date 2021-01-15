# Reverse-Image-Search-Engine

This project uses transfer learning to find similar images. In simple words, the process entails passing the images through a pretrained convolutional neural network like ResNet-50,extracting the features, and then using a metric to calculate the error rate like the Euclidean distance.

<h2>Learning objectives:</h2>
<ul>
<li>1. Perform feature extraction and similarity search on Caltech101 and Caltech256 datasets </li>
<li>2. Learn how to scale to large datasets</li>
<li>3. Make the system more accurate and optimized</li>
<li>4. Analyze case studies to see how these concepts are used in mainstream products.</li>
</ul>
Find the dataset at https://drive.google.com/file/d/137RyRjvTBkBiIfeYBNZBtViDHQ6_Ewsp/view

<h2>Future Work:</h2>
Instead of brute force algorithm as the baseline for nearest neighbors, try to implement the project using approximate nearest-neighbor(ANN) libraries like Spotify's Annoy, FLANN, Facebook's Faiss, Yahoo's NGT and NMSLIB.
