# Poker Exam
Create a class for the following object. 
1. Deck - contains 52 cards initially. Each card is represented by an unchangeable suit and value.
Suits - ♣ (Club), ♠ (Spade), ♥ (Heart), ♦ (Diamond) Values - 1(A),2,3,4,5,6,7,8,9,10,11(J),12(Q),13(K)

## Actions
1. draw - retrieves the top most card on the deck. When called with number of desired cards, it will try to draw the N cards, if not enough, draw all cards.
2. shuffle - randomizes the location of all cards, excluding the drawn cards 
3. restore - returns the last N cards drawn on the bottom of the deck, if no number is provided, return all drawn cards. 

### Make sure that the class is encapsulated.
