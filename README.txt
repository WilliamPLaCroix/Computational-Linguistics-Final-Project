README

## Directory Structure
.
├── README.txt
├── Final Project - William LaCroix - 7038732.ipynb
├── Project Report - William LaCroix - 7038732.pdf
└── data .
	   ├── full_hsk_sentences.txt
	   ├── hsk_word_lists.tsv
	   ├── hsk1_sentences_filtered.txt
	   ├── hsk2_sentences_filtered.txt
	   ├── hsk3_sentences_filtered.txt
	   ├── hsk4_sentences_filtered.txt
	   ├── hsk5_sentences_filtered.txt
	   ├── hsk6_sentences_filtered.txt
	   └── save .
			├── full_hsk_sentences_preprocess.p
			├── full_hsk_sentences_trained_rnn.p
			├── hsk1_sentences_filtered_preprocess.p
			├── hsk1_sentences_filtered_trained_rnn.pt
			├── hsk2_sentences_filtered_preprocess.p
			├── hsk2_sentences_filtered_trained_rnn.pt
			├── hsk3_sentences_filtered_preprocess.p
			├── hsk3_sentences_filtered_trained_rnn.pt
			├── hsk4_sentences_filtered_preprocess.p
			├── hsk4_sentences_filtered_trained_rnn.pt
			├── hsk5_sentences_filtered_preprocess.p
			├── hsk5_sentences_filtered_trained_rnn.pt
			├── hsk6_sentences_filtered_preprocess.p
			└── hsk6_sentences_filtered_trained_rnn.pt

## Versions
Python: 3.8.10
Pytorch: 1.13.1+cu117

## Project use:
Assuming the project is extracted with data and save folders, simply pressing "run all" in a Jupyter notebook should load the models and generate text.
The intention is that if some of the save files are missing or deleted, the program should be able to regenerate all of the preproccessed 
files and trained rnn files on its own in order to then load and generate text, but this is occasionally gives funky models that predict
the input as the output and error out.

Feel free to adjust the text_length parameter in the final cell in order to generate texts of various lengths

Thank you so much for a great semester,
and have yourself a damn fine day!
 - Herr LaCroix