# Romanized Nunkish to Romanized Tamil Encoder/Decoder

### About
This code is basic and not that efficient code I've written that can take the romanized version of Nunkish, the language written in the anime series "Violet Evergarden", and decode it into romanized Tamil, which is what the original language is.

### Handwritten Procedure
The resource that helped the most on this short project was [this Reddit post](https://www.reddit.com/r/anime/comments/88bbob/violet_evergarden_alphabet_and_language_part_2/) that explained the semantics and reasoning behind the language. To sum up its findings, here are both ways to encode and decode to and from English to Nunkish.

#### Encoding
- Write out your sentences in plain English, and throw those into a translation program that can return Romanized Tamil (Such as Google Translate)
- __**IMPORTANT:**__ Use online software [like this](https://codebeautify.org/remove-accents) to remove any accents that may be present.
- Take the string of Romanized Tamil and substitute it into the input_string of the encoder.
- The encoder will return a string of text that can then be written using [this font, made by よづき](https://kkyane.booth.pm/items/1979406), that converts it into the typeface that viewers of Violet Evergarden will recognize.

#### Decoding
- This is a bit more painstaking to do. Use the guide below to decode Nunkish into its romanized counterpart:
![Image](https://github.com/Ai-TaSAi/nunki-tamil-encoder-decoder/blob/main/NunkiRomanized.png?raw=true)
- Once you have that, substitute the string into the input_string of the decoder.
- The decoder will return a string that is essentially non-accented Romanized Tamil.
- Putting this into Google Translate does not perform particularily well, as without the accents many words are left untranslated. You might want to have a base understanding of Tamil or have access to a resource or someone else who does, if you want to fully comprehend the text.

### Running the Code
- ```git clone``` the repo into your local workspace.
- Make sure you have Anaconda and Jupyter Notebook installed.
- Open the ```.ipynb``` file on your Notebook, and run all cells to initialize variables.
