What are these files?

-POETRY_BOT uses Python's markovify module.
Then, I use Yabin Zheng's Google Images crawler and PyTesseract's Image OCR to aggregate custom poetry data. Here is the process flow:

1. Images are downloaded using Mr. Zheng's crawler. 
2. PyTesseract uses OCR to extract image data, in this case, Images queried "Poetry" will return poems when run through PyTesseract.
3. Markovify uses the scraped data to create interesting poems

-Files preceded with Markov_implement represent my attempt at replicating the classic markov chain algorithm.

Markov_implement_one_char, however, goes a step deeper and uses carneige mellon's dictionary of ipa transcriptions to take a corpus of text,
in this case, harry potter, and transcribes every word to its raw ipa transcription. These are run through my custom markov chain to produce a
string of text that theoretically sounds like J.K. Rowlings' linguistic utterances, broken down into every phoneme.

