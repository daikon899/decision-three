# Uso di funzioni rilevanti
## decision_tree_learning(examples, attributes, parent_examples=()): 
Crea un albero di decisione come descritto in R&N 2009 §18.3, utilizzando l’entropia come misura di impurità. Prende in ingresso un dataset e gli attributi interessati. Il parametro parent_examples serve esclusivamente all'interno della funzione per chiamate ricorsive
## test_dtree(dtree)
Effettua un test dell'albero sul validation_set e restituisce un punteggio tra 0 e 1 proporzionalmente alla precisione.
## to_rules(tree)
Trasforma l'albero in una list di regole in DNF (Mitchell 1997)
## test_rules(dataset, rules)
Effettua un test delle regole su un dataset e restituisce un punteggio tra 0 e 1 in base alla sua precisione e una lista di punteggi per ogni singola regola
## rules_pruning()
Effettua il pruning sulle regole

# Link per il dataset
https://archive.ics.uci.edu/ml/datasets/Adult
