# bayes-golf
Bayesian updates to provide live adjustments to handicaps based on hole-by-hole results

## usage
This is designed for a match-play style golf game. Players need to have handicap *indices*. These aren't course handicaps. Those are calculated by the notebook. The notebook also needs to know the course's par and slope rating. It asks for course rating too, but that won't matter for this application. Feel free to input whatever you'd like. Then the hole's characteristics need to be read in. It'll ask for the hole's par, handicap index, and the score for each of the players. The notebook guides you along the way. It gives (I believe) sufficient explanation at each step. Comments in the code might give further clarification.

The notebook will spit at you a distribution of handicaps for each golfer - and the most probable of them. Take the new handicap and put it in at the top for the next hole. I could've automated this for each hole, but I did not.

## components

### notebook
The Jupyter notebook file should provide sufficient explanation of analysis. Further commentary and explanation available upon request.

### csvs
All five .csv files are referenced throughout the notebook. The notebook explains why they're used and where I got them.

Cheers,

Teddy