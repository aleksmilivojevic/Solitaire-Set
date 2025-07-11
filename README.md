# Solitaire-Set

Instructions: Save the html file and open it (most likely with a browser by default).

Solitaire version of the game Set -- There are 4 properties that each card features - number, shape, color, and shading. Each property has 3 variations - number can be 1,2,3; shape can be oval, diamond, squiggly; color can be red, green, purple; shading can be empty, half, full. For each combination of variations there is exactly 1 card, totalling in a deck of 81 cards. For example, there is a unique card with 2 half-shaded green ovals.

A set is a collection of three cards such that for each of the four properties, either all the variations for that property exhibited among the three cards are the same, or they are all different. For example, a set would be {2-oval-green-empty, 3-oval-green-full, 1-oval-green-half}. In the properties "number" and "shading", the three cards cover all three variations, while in the properties "shape" and "color" they are all the same. The three cards can be all the same in one property and all different in another, that is fine - the verification of being a set just goes property by property independently. A non-set would be {2-oval-green-empty, 2-oval-green-full, 1-oval-green-half}. Note now that the numbers exhibited are 2,2,1 -- they are not all the same, but they also do not cover all three possibilities.

In the usual, multiplayer, Set, players look at 12 laid down cards and the first to find a Set collects those cards. The cards that were taken out of play are then replenished. If there is no Set on the board, cards are added. At the end of the game, when the deck is depleted and there are no remaining Sets on the board, the player with the most collected cards wins.

In Solitaire Set, you strategize -which- Set to collect, if any, by imposing a points system that differentiates Sets based on their difficulty of perception. A Set is worth k points if the three cards in it are all different for k of the 4 properties. Note that k can be 1,2,3,4. For example, the set we considered before, {2-oval-green-empty, 3-oval-green-full, 1-oval-green-half} is worth two points. A set worth 4 points is called a **megaset**.

If you think there is no set on the board, you are given two options -- reshuffle the deck and place down 12 new cards, at the cost of 2 points, or add a new card to the board, at the cost of all sets being worth only 1 point as long as there are > 12 cards on the board. Reshuffling when there are > 12 cards on the board brings the number of cards down to 12. 

You can also use the "locate set" feature to find a random set on the board.
