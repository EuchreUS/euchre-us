#Rules for Double-Deck \[Bid\] Euchre
######(as taught to [Chris J.M](https://www.github.com/duck57))

1. Use a double euchre deck (standard pinochle deck) and four players.
  1. There is a three-player variant where each player gets 16 cards and plays alone.  It's mostly similar to the rest of the rules otherwise, but, like single-deck (standard) euchre, probably won't be implemented by me (others are welcome to add this feature).
2. Dealer rotates the usual way (to the left) between each hand.
  1. Each player is dealt 12 cards.
     * The usual way is the Fibonacci Deal, where you deal each player 1, 1, 2, 3, then 5 cards each go around.
     * Other commonly-used deals
		 * 2 or 3 cards at a time
		 * The Cheater's Deal of alternating 11 and 1
		 * 1, 2, 3, 1, 2, 3
		 * Please don't be that guy (unless you're a computer dealer) who goes around the table 12 times with one card.
3. Bidding starts to the dealer's left with a minimum of 6.
	1. Each bid must be greater than the previous
	2. If no one has bid by the time it reaches the dealer, the dealer is stuck with a bid of 6.
	3. [Clarification on bidding alone needed: are loners and shooters separate bids?]
	4. [Clarification as to whether the bidding always stops at the dealer, or if it goes until no one outbids the standing bid]
4. The player who won the bid leads the first card and declares trump.
	1. In addition to a suit, Lo No and High No are also acceptable.
	2. If a suit is declared, the Jack of the trump suit ("right bower" or "right") is the highest-value card.  The Jack of the same-colour suit as trump ("left bower" or "left") is the second-best card.  EX: Spades is trump, Jack of Spades > Jack of Clubs > Ace of Spades > King of Spades, etc…
5. Each trick is played
	1. You must follow suit of the first card, if possible.
	2. When two of the same card are played, the first one played takes precedence.
	3. If no trump was played, only cards of the leading card's suit are counted for scoring.
	4. The person who won the trick leads for the next trick.
6. Scoring:
	1. If the betting team met or exceeded its bet, it earns the number of tricks it took plus 2 bonus
	2. If the betting team did not make its bet, it loses its bet (as in it earns negative points).
7. Games are played to 50 points (usually, but I've also seen 100).
	1. For AI testing purposes, I've also added some mercy rules: if a team reaches -50 points, they lose; if both teams end up under -25 points, they both lose.
