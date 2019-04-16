# MachineReading

## Introduction
This project is an effort to make the tribal community aware of the rights they hold. Often a majority chunk of such communities are illiterate and hence reading the rights from documents is not feasible. Moreover, these documents comprise of a large number of clauses that it is a very tedious effort to read the whole document in order to just know the specific rights which affect the concerned user the most.  An end-to-end system which captures the question of the user as a voice, searches through the rights document and presents the concerned right would be very useful in such cases.

## Structure
To realize such a system, we intend to develop a combination of Automatic Speech Recognition (ASR), Machine Reading Comprehension (MRC) and Text-To-Speech (TTS). ASR will help get question in textual form from speech (question input as voice). MRC will search through the document for relevant rights and TTS will subsequently read them out to the user.

### ASR


### MRC
MRC is a well researched domain atleast for English. However, we will have to take care of doing MRC over very large documents.

Microsoft Research Maluuba works on this significantly.

There are several pretrained models by AllenNLP, BERT which perform several language modelling tasks including Machine Reading Comprehension.

### TTS
We intend to use the CMU Flite TTS as it is extensible to other languages as well. There are several low-resource languages which is used by the tribal community like Gondi, and hence the ability to extend this to other languages will help in expanding our reach in the tribal communities.

## Documents

* [Forest Rights Act (52 pages)](FRARulesBook.pdf)