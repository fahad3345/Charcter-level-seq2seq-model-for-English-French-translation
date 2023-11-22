# Project Name: Character-Level Sequence-to-Sequence Model for English-French Translation

Aim of the Project:
Implement a character-level recurrent sequence-to-sequence model for translating short English sentences into French sentences, character by character.

Approach:

Utilize encoder-decoder architecture with LSTM (Long Short-Term Memory) networks.
Train the model using input sequences (English sentences) and corresponding target sequences (French sentences).
Employ "teacher forcing" during training, where the decoder is trained to predict the next character in the sequence based on the input and previous characters.
In inference mode, decode unknown input sequences by sampling predictions character by character until the end-of-sequence character is generated.
Models and Libraries Used:

TensorFlow and Keras for model implementation.
Encoder: LSTM network for input sequence encoding.
Decoder: LSTM network for target sequence decoding, with a Dense layer for output.
Training: RMSprop optimizer, categorical crossentropy loss.
Result:

Achieved successful training with specified configuration parameters (batch size, epochs, latent dimensionality).
Saved the trained model for future use.
Inference mode demonstrated successful decoding of translated sentences.
