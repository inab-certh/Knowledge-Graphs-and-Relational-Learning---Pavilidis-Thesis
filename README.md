## Thesis 2024 - Κώδικας και αποτελέσματα

Τα αρχεία που περιέχονται είναι πρώτες προσπάθειες για ontology embedding και μετατροπή οντολογιών σε κατάλληλη μορφή για machine learning

Ο φάκελος "embeddings" τα Vector embeddings που προκύπτουν από τον κώδικα του φακέλου "Models", κάθως και παράγωγα αρχεία. Συγκεκριμένα
* Το αρχείο "annotation_corpus_gene_ontology.txt" περιέχει όλα τα annotations της οντολογίας ώστε να χρησιμοποιηθούν σαν corpus
* To "ontology.embeddings-OWL2VecStar.txt" περιέχει ένα embedding κάθε class, individual και property. Χρησιμοποιεί την τεχνική embedding των κανόνων του OWL2Vec*
* Το "OWL2VecStar_projection_with_word2vec_embeddings_.txt" περιέχει ένα embedding κάθε class, individual και property. Χρησιμοποιεί την τεχνική embedding των κανόνων του OWL2Vec*, μέσα από τον wrapper της mowl με DeepWalks για να προκύψει corpus και  Word2Vec για συντακτική ανάλυση
Ο φάκελος "embeddings" περιέχει ένα embedding κάθε class, individual και property. Χρησιμοποιεί την τεχνική embedding των κανόνων του OWL2Vec* αλλά γίνεται μέσα από τον wrapper της mowl με Word2Vec(Το ίδιο κάνει και η OWL2Vec* σαν standalone απλώς σε πιο περίπλοκο document structure)

Η οντολογία που χρησιμοποιήθηκε είναι το Gene Ontology 