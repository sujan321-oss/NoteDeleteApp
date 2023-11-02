# NoteDeleteApp
During exam time, we all download various handwritten notes, and deleting them afterward can be quite a hassle. That's why I've automated this process using Python and deep learning.

# Here's how I did it:

1> Data Scraping: I collected a diverse range of handwritten notes from different websites.

2> Deep Learning Expertise: I employed Python and ResNet models, removing the top layer and adding a Global Max Pooling layer.

3> Feature Extraction: I extracted unique features by flattening the weights from the model's last layer.

4> Nearest Neighbors: Using the k-Nearest Neighbors algorithm, I measured the distance between the downloaded images and those in the directory.

5> Smart Deletion: Images with a distance of less than 0.83 (after rigorous testing) are automatically deleted by the app.
