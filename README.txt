UCLASS Annotations
======================
Queen's University

Tedd Kourkounakis
tedd.kourkounakis@queensu.ca
======================


1. General information
----------------------
This is a collection of 25 time-aligned orthographic transcriptions and
stutter classification labels for 6 stutter types derived from the 
original UCLASS Release One dataset conversations. It was created for the
 use of classification of stuttered speech.


2. Structure
----------------------
Each annontation CSV file contains information pertaining to the corresponding
WAV file of the same name, provided in the UCLASS Release One dataset.

Eg. The 'F_0101_10y4m_1.csv' provides annotations for the 'F_0101_10y4m_1.wav' audio
file.

Each row in each annotation file pertains to a single word or sound utterance, and
its corresponding timing and labels. The information for each row is as follows.
Individual stutter types have been labelled manually.

Column 1: 	Transcriptions as provided by the UCLASS Release One dataset.

Column 2: 	Transcriptions generated through time-alignment. Note any missing 
		values or values containing '<unk>' indicate that these utterances 
		were not time-aligned automatically, and were in turn manually aligned.

Column 3:	Time (in seconds) when utterance begins.

Column 4:	Time (in seconds) when utterance ends.

Column 5:	Binary label pertaining to whether the utterance countains a stutter.
	TRUE:	The utterance contains a stutter.
	FALSE:	The utterance does not contain a stutter.	

Column 6:	Binary label pertaining to whether the utterance countains an
		interjection stutter.
	TRUE:	The utterance contains an interjection stutter.
	FALSE:	The utterance does not contain an interjection stutter.	

Column 7:	Binary label pertaining to whether the utterance countains a stutter
		that is not an interjection stutter.
	TRUE:	The utterance contains a stutter that is not an interjection stutter.
	FALSE:	The utterance is clean, or an interjection stutter.	

Column 8:	Label classifying utterance as clean speech, or one of 6 stutter types.
	0: 	clean
	1: 	interjection
	2: 	sound repetition
	3: 	part-word repetition
	4: 	word repetition
	5: 	phrase repetition
	6: 	revision
	7: 	prolongation