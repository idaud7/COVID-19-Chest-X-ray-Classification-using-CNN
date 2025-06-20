## COVID-19 Chest X-ray Classification

A compact TensorFlow/Keras project that:

- **Loads & organizes** a 2,000-image dataset (COVID vs. Normal; optionally Pneumonia)
- **Preprocesses & augments** images (rotations, shifts, flips)
- **Trains** a 3-layer CNN for binary and 3-class classification (5 epochs, Adam)
- **Evaluates** on held-out test sets with accuracy and loss reporting
