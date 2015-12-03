#Requirements for Euchre Submission

##Must do

1.	Play a game of bid euchre (below are some likely caveats)
  1. Correctly handle trump (including LoNo and High No calls)
  2. Ensure only valid cards are played
  3. Handle calls to go alone
2.	Support the choice of at least one human player or an automatic game (all computer players)
  1. Human player should have trump sorted in a human-understandable way:
    * The trump suit should not move to the end of the hand because it's the "greatest", but should stay in place.  Ex: if Clubs is trump, the order of cards should still be Clubs, Diamonds, Spades, Hearts.
    * The bowers should be correctly sorted as the greatest cards within the trump suit
  2. AI
    1. Must select a bid (or pass) (can just use a weighted random)
    2. Must look at their hand to determine what to call when they win their bid
    3. Must play valid cards
3.	Offer the choice to play another game at the end of a game
4.	Be playable from the command line (unless there's a good reason the specific language shouldn't be run from the command line)


##Optional
1.	AI that are somewhat intelligent in bid and card selection
  * A good card selection algorithm is to play the best card if it will earn you the trick, otherwise play something bad.
  * Bid selection is a tricky process
2.	Multiple AI skills
3.	Configuration options for more than the two required states

##Extra(s)
Unlike the 99-Bottles-of-Beer.net project, there is no reason to have all euchre programs do more or less the same thing.  If a particular language makes it easy to do something, adding extras is encouraged.  Examples of things to do:
*	Add a GUI
*	Language good for actual AI?  Make a machine-learning computer player.
*	Seamless database integration in your favorite language?  Add in a database to replay past games.
