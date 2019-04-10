# Pythonion
The apriori principle can reduce the number of itemsets we need to examine. Put simply, the apriori principle states that

if an itemset is infrequent, then all its supersets must also be infrequent

This means that if {beer} was found to be infrequent, we can expect {beer, pizza} to be equally or even more infrequent. So in consolidating the list of popular itemsets, we need not consider {beer, pizza}, nor any other itemset configuration that contains beer.
