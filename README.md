# Content-Based-Recommendation---Good-Reads-data
Content Based Recommendation using Good read data

Fixed a few errors in the notebook as given below:

Cell \[2\] : `df = pd.read_csv("test.csv")`\
I replaced `test.csv` with `data.csv`\
`df = pd.read_csv("data.csv")`

Cell \[9\] : `google_model.build_vocab(line_of_sentance)`\
I replaced `line_of_sentance` with `corpus`\
`google_model.build_vocab(corpus)`

Cell \[9\] : %%time\
SyntaxError: invalid syntax\
I commented it.

Cell \[13\] : `cosine_similarities = cosine_similarity(array_embeddings, array_embeddings)`\
I replaced `array_embeddings` with `word_embeddings`\
`cosine_similarities = cosine_similarity(word_embeddings, word_embeddings)`

