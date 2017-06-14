# Pig Dice Game
A web page that allows 2-players to take turns rolling a single die with a range of 1-6 in value. The first player to reach a score of 100 or more wins. A player can roll as often as they desire during their turn, and every number value rolled will be added to their final score once their turn is complete. A player's turn is complete if they decide to hold where they are with the total value of their turn, however the player's turn is ended immediately if at any point they roll a value of 1 and all points acquired during that turn are forfited and not added to their total score. When one player's turn is over, it becomes the other player's turn.

## Code Specs
|Behavior - Plain English|Input|Output|
|---|---|---|
|Clicking the roll button will return a value of 1-6|Click Roll Button|One of the potential values will populate in their roll score: 1,2,3,4,5,6|
|A player's turn is complete by clicking the hold button and their turn score is added to their total score|Hold button is clicked|Total Score increases by the turn score amount|
|A player's turn is complete by rolling a 1 value and their turn score becomes 0 in value|Player rolls a 1 value|The player's turn score becomes 0 and it's the other player's turn|
|A player is given a win notification when their total score is greater than or equal to 100|Player clicks on the hold button after the sum of the player's turn score and total score are 100 or greater|The player is notified that they have won|

## Technologies Used
* HTML
* JavaScript
* jQuery
* Bootstrap

### License
Copyright 2017 Laura Hamilton, Mick Sexton, Esvethlynna Pangelinan, Joel Bakken

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
