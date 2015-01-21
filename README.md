# Data for card influence study

This is supplementary data
for the paper "Influencing Choice Without Awareness"
in *Consciousness and Cognition*
(Olson, Amlani, Raz, & Rensink, 2015).
In the study,
participants chose playing cards
from a series presented on a computer.
Borrowing techniques from magicians,
we tried to influence participants to choose
a particular card from each series.

## Data format

The data file (forcing.csv) is in comma-separated value format.
It contains the columns:

- snum:      Subject number (N=43).

- trial:     Trial number (1 to 28).

- tname:     Target card name (e.g., AS = Ace of Spades).

- tvalue:    Target card value (1 to 13, e.g., 1 = Ace, 2 = Two, 11 = Jack).

- tsuit:     Target card suit (1 to 4, i.e., Spades, Hearts, Clubs, Diamonds).

- tpos:      Target position in stream of cards (5 to 22).

- cname:     Chosen card name (cf. tname).

- cvalue:    Chosen card value (cf. tvalue).

- csuit:     Chosen card suit (cf. tsuit).

- cpos:      Chosen card position in stream (1 to 46, else NA if chosen card was absent).

- cf:        Number of frames chosen card was shown for (else NA if absent, 1 frame = 10 ms).

- right:     Whether chosen card was target card.

- rt:        Time taken to enter and confirm value and suit.

- trans:     Revised Transliminality Scale score (Lange, Thalbourne, Houran, & Storm, 2000).

- control:   Internal Control Index (Duttweiler, 1984).

- visd:      Visibility sensitivity of target card (d', see Olson, Amlani, & Rensink, 2012).

- visc:      Visibility bias (c).

- memd:      Memorability sensitivity (d').

- memc:      Memorability bias (c).

- lik:       Likeability (0 to 1).

- free:      "Did you feel that you had a free choice over which cards you chose?" (cf. Questionnaire).

- influence: "Did you feel that you were being influenced to choose any particular cards?".

- nlonger:   "Did you notice that any cards were shown longer than the others?".

- nlongest:  "Each trial, one card was shown longer than all of the rest of the cards. Did you notice this?".

- card#:     Card (0 to 51, e.g., 0 = Ace of Spades, 51 = King of Diamonds) in # position in stream.

- card#f:    Number of frames each card was shown (cards 1 to 10 and 37 to 46 were masks, 1 frame = 10 ms).
