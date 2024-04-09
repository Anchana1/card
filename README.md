# card 
python 

S = ["\u2663","\u2665","\u2666","\u2660"] 

Rank = [A,2,3,4,5,6,7,8,9,10,K,Q]
for rank in Ranks: 
   for suit in S: 
        print(f'{rank} of {suit}'.ljust(10), end='')
    print() 
