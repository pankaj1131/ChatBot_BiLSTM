# ChatBot_BiLSTM

This project implements a chatbot using the Bi-Directional LSTM(Long-short Term Memory) units for both encoder and decoder, following a seq2seq architecture.

The Dataset use is Cornel movie dialogues dataset, which can be found in the Link provided below:

http://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html

## Installation step:

All the dependencies are provided in the requirements.txt file, which can be installed using (for pip users):

```
pip install -r requirements.txt
```

## Steps to run the code:
1. Update the file location of the corresponding files present in the Cornell movie dialogue dataset in the file mentioned below:

```
config.py
```
2. Run jupyter notebook:
  Open jupyter notebook
  ```
  jupyter notebook
  ```
3. Run each cells in the pre_processing notebook.

Note: This may take some time to run.

When this notebook is run successfuly you will notice a data.pickle file being formed in the directory.

4. Run each cells in the chatbot notebook file.

Note : Training the model will take some time, depending on the GPU used : for this project Nvidia GTX 1050Ti was used.

## Author
Pankaj Singh (MSc. Artifcial Intelligence, Cork institute of technology)

## Acknowledgements:
1. https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1174/reports/2760230.pdf
2. https://www.researchgate.net/publication/13853244_Long_Short-term_Memory
3. https://www.aclweb.org/anthology/D16-1084.pdf
4. https://medium.com/@david.campion/text-generation-using-bidirectional-lstm-and-doc2vec-models-1-3-8979eb65cb3a
