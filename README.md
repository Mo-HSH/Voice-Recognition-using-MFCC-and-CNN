# Voice Recognition using MFCC and CNN

This project focuses on building a voice recognition model using the concept of Mel-frequency cepstral coefficients (MFCC) and a Convolutional Neural Network (CNN). The process involves extracting MFCC features from a dataset containing labeled audio samples, followed by training a CNN model for voice detection.

## Dataset
It should be a collection of audio files in various formats, labeled with their respective categories or classes.

## MFCC Extraction
MFCCs are a set of features widely used in audio and speech processing. They provide a compact representation of the spectral characteristics of audio signals. The `num_mfcc` parameter specifies the number of coefficients to extract. The `n_fft` parameter represents the interval used to apply the Fast Fourier Transform (FFT), measured in the number of samples. The `hop_length` parameter defines the sliding window for FFT, also measured in the number of samples. The signal is divided into `num_segments` segments for processing.

## Model Training
After extracting the MFCCs, a CNN model is trained on the dataset to recognize and classify voice samples. The specifics of the CNN architecture and training procedure are not mentioned in the provided code snippet.

## JSON File
The extracted MFCCs, along with their corresponding labels, are saved in a JSON file specified by the `json_path` parameter. This file serves as a convenient storage format for the processed data, allowing easy retrieval and reuse for future analysis or model training.

## Usage
To run the project, follow these steps:
1. Install the required dependencies.
2. Set the `dataset_path` variable to the path containing your audio dataset.
3. Set the `json_path` variable to the desired path for storing the MFCCs in JSON format.
4. Modify the values of `num_mfcc`, `n_fft`, `hop_length`, and `num_segments` as per your requirements.
5. Execute the code to extract MFCCs and save them in the JSON file.
6. Implement the CNN model for voice recognition using the saved MFCCs.
7. Train the model using appropriate techniques.
8. Evaluate the model's performance and fine-tune if necessary.

## Conclusion
This project demonstrates the use of MFCCs and a CNN model to build a voice recognition system. By extracting MFCC features from audio samples and training a CNN model, it becomes possible to classify and identify different voices accurately. This technology finds applications in various domains such as speech recognition, speaker verification, and voice-controlled systems.

Feel free to explore and modify the provided code to suit your requirements and further enhance the voice recognition capabilities.
