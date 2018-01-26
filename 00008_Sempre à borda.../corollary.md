Como na aritmética, na lógica também existe o conceito de **precedência** e certas operações se resolvem antes que outras: primeiro a negação (`not`), depois a conjunção (`&&`) e por último a disjunção (`||`).

Por essa razão, a expressão `not podeMover(Norte) || not podeMover(Leste) || not podeMover(Sul) || not podeMover(Oeste)` pode ser escrita sem precisar colocar parênteses no meio.
