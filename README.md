# ProjektiLojaBlackJack
ss 


ndryshim ne start game 

dealerHand = new ArrayList<>();
dealerSum = 0;
dealerAceCount = 0;

hiddenCard = deck.remove(deck.size()-1);
dealerHand.add(hiddenCard);
dealerSum += hiddenCard.getValue();
dealerAceCount += hiddenCard.isAce() ? 1 : 0;

Card card = deck.remove(deck.size()-1);
dealerHand.add(card);
dealerSum += card.getValue();
dealerAceCount += card.isAce() ? 1 : 0;

