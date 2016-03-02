This fork is intended to extend lda to a form of disclda.

It amounts to a simple matrix manipulation of the topic vector for a document for that is based on the label of a document

In DIscLDA, each document has a label $y_d$ and there is a stochastic matrix $T^y$ associated with each label.

Where in vanilla LDA you draw the word topics $z_{d,i} ~ Cat(\theta_d)$, in DiscLDA you draw $z_{d,i} ~ Cat(T^{y_d}\theta_d)$
