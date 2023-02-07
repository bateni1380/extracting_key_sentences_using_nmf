# extracting_key_sentences_using_nmf
This was a project for Computational Data Mining course (the master course that I got in undergraduate period) tought by Dr. Shakeri in December 2022 at Amirkabir University of Tecknology.

In this document I assigned a matrice to an article...Then I extracted important sentences using Non-negative matrix factorization (NMF).

We construct the matrice this way:
columns are corresponded to posible words and rows are corresponded to sentences of the article. We set a cell 1 of and only if the word has occurred in the sentence.

Then we apply the NMF algorithm and we get W and H. We knew (from the course) that the importance of words are related to norm of rows of the W matrice and 
the importance of sentences are related to norm of columns of the H matrice. So we use this property.
