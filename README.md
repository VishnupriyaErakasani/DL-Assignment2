QUESTION1 
What We Learned :

Successful Transliteration Model: We built and trained a sequence-to-sequence (seq2seq) model using architectures like LSTM/GRU/RNN for transliterating Latin script into Devanagari (Hindi).
The model achieved good accuracy and generated readable Devanagari outputs for most test cases, indicating successful learning.
Importance of Preprocessing: Data cleaning, character tokenization, and use of start/end tokens played a crucial role in helping the model learn proper sequence mapping.
Model Performance: LSTM generally performed better than basic RNNs due to its ability to capture long-term dependencies in sequences.
Accuracy on the test set (e.g., ~80–90%) showed the model can generalize well to unseen inputs.
Practical Application: This system can be integrated into real-world applications like Indic input tools, multilingual keyboards, and digital archiving of low-resource languages.

What next to learn :

Use Transformer-Based Models: Upgrade to transformer architectures (like BERT, GPT, or specifically mBART) which have shown state-of-the-art results for sequence-to-sequence tasks.
Bidirectional Encoder + Attention Mechanism: Add attention to better focus on relevant parts of the input while decoding — this often improves output quality.
Use bidirectional LSTM encoders for more contextual understanding.
Character-Level and Subword Tokenization: Try subword tokenization like Byte Pair Encoding (BPE) to better handle rare or unseen words.
Train with More Languages: Extend the system to handle multilingual transliteration by training it on multiple scripts (e.g., Bengali, Tamil, Telugu) from the Dakshina dataset.
Handle Noisy Input and Mixed Scripts: Real-world user input is noisy and might mix English and native scripts. Improve robustness with augmented training data.
Deploy as a Web API or Mobile App: Package the trained model with a REST API for easy integration into text editors, messaging apps, or educational tools.
Evaluate with BLEU Score / Character-Level F1: Use more advanced evaluation metrics beyond accuracy, such as BLEU or edit distance, to assess transliteration quality more precisely.

QUESTION2 
What We Learned :

Smart Start: Using a computer brain that already knows language (like GPT-2) makes learning to write lyrics much easier.
Learns the "Song Vibe": The computer can pick up on common themes and styles in songs.
Good Data = Good Lyrics: The better and more varied the song examples we give it, the better the lyrics it writes.
Tweaking Matters: Adjusting the computer's "learning settings" is important for good results.
Starting Point Helps: Giving the computer a first line really guides what it writes next.
It Can Be Creative (Sort Of): The computer can come up with new combinations of words that sound like lyrics.
Not Quite Human: Its lyrics can sometimes be a bit odd or lack real emotion.

What next to learn :

Teach it to rhyme and have rhythm.
Make it write in different song styles.
Help it be more original.
Maybe even connect the lyrics to music.
Figure out how to judge if computer-written lyrics are actually good.
Think about whether this is fair to human songwriters.
