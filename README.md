Find People In Texts

(c) Bill Pascoe, 2025

Apache 2.0 licence (open source, free to re-use with attribution)

This Jupyter Notebook reads input texts and identifies people in them, outputting their names, the sentence their name appears in, a citation and URL if available as a CSV file. A CSV file can be opened in Excel for correcting and adding other data.

These methods will save a great deal of time and make large scale research feasible when before it was not. None the less, these methods unavoidably have a high error rate and will require a substantial amount of human checking and manual correction.

The input format is not strict markup, but is designed to be very quick and easy to use for a non IT person trawling full text OCR archives. Just copy and paste the citation and the text and seperate with a line of any number of hashes, like this:
###########

An example input file Example_Eureka.txt is included.

It will also attempt to identify dates from the citation to help piece together people's life course, or the order events they were involved in. It may pick up the 'accessed on' date or other date instead of the publication date.

See the notebook for more inline documentation.
