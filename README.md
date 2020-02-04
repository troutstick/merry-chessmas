# a chess program for the ages
why use an optimized and functional library when you can not??? in short: here i mess around and try to program a game of chess which can be played from command line. maybe i'll even add a gui someday.

* bitboards????? pfffffffffffffft

* late move reduction? centipawns? mating nets? haha we don't do that stuff here amigo

* wavedashing? f-tilt? get outta here

### if anything, it can print a chessboard:
```
  _a__b__c__d__e__f__g__h_
8| R  N  B  Q  K  B  N  R |
7| P  P  P  P  P  P  P  P |
6| -  -  -  -  -  -  -  - |
5| -  -  -  -  -  -  -  - |
4| -  -  -  -  -  -  -  - |
3| -  -  -  -  -  -  -  - |
2|(P)(P)(P)(P)(P)(P)(P)(P)|
1|(R)(N)(B)(Q)(K)(B)(N)(R)|
```
  
anyways, this is basically the next stockfish

### Update: added basic moves from cmd line; here's the first few moves of the sicilian!
```
  _a__b__c__d__e__f__g__h_
8| R  -  B  Q  K  B  N  R |
7| P  P  -  P  P  P  P  P |
6| -  -  N  -  -  -  -  - |
5| -  -  -  -  -  -  -  - |
4| -  -  - (N)(P) -  -  - |
3| -  -  -  -  -  -  -  - |
2|(P)(P)(P) -  - (P)(P)(P)|
1|(R)(N)(B)(Q)(K)(B) - (R)|
```
### To-do
* Add move history

* Add castling

* Add check, 50mr, checkmate, stalemate, 3fold

* Maybe add resigning or something
