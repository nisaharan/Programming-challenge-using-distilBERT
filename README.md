# Programming-challenge-using-distilBERT
Using the wikitext dataset with the distilbert-base-cased model checkpoint.

Start by loading the wikitext-2-raw-v1 version of that dataset, and take the 11th example (index 10) of the train split. We'll tokenize this using the appropriate tokenizer, and we'll mask the sixth token (index 5) the sequence.

When using the distilbert-base-cased checkpoint to unmask that (sixth token, index 5) token, what is the most probable predicted token (please provide the decoded token, and not the ID)?
