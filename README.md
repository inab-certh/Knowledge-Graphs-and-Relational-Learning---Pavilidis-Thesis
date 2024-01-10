## Thesis 2024 - Κώδικας και αποτελέσματα

Τα αρχεία που περιέχονται είναι πρώτες προσπάθειες για ontology embedding και μετατροπή οντολογιών σε κατάλληλη μορφή για machine learning

Ο φάκελος "random walks" έχει ένα παράδειγμα μετατροπής του γράφου OWL από το παράδειγμα family πρώτα σε knowledge graph που τηρεί τους κανόνες του owl2vec. Στη συνέχεια τρέχουμε ένα deepwalk πάνω στο γράφημα.
Οι παράμετροι του μοντέλου deepwalk είναι ενδεικτικές και δεν μας αφορούν αφού έτσι και αλλιώς ο γράφος είναι πολύ μικρός για training

Ο φάκελος "embeddings" περιέχει ένα embedding κάθε class, individual και property. Χρησιμοποιεί την τεχνική embedding των κανόνων του OWL2Vec* αλλά γίνεται μέσα από τον wrapper της mowl με Word2Vec(Το ίδιο κάνει και η OWL2Vec* σαν standalone απλώς σε πιο περίπλοκο document structure)