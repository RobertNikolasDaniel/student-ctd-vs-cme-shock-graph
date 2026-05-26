# student-ctd-vs-cme-shock-graph
Student example graph to show divergence between Cheapest To Deliver and CME Futures convexity

takes the convexity formula

- Pnew = Pold*(Dmod/(bp/10,00))+.5*C((bp/10,000)^2))

for both cash ctd and cme
cme convexity is just

- convexity/cf

this project shows that ctd convexity =/= cme convexity and a perfectly hedged cash to futures basis trade can break quick in rate moves
