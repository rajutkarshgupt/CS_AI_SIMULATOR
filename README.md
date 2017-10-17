# CS_AI_SIMULATOR

ALGORITHMIC STEPS FOR GIVING SEQUENTIAL - INPUTS TO EXECUTE CODE :-

INPUT - FORMAT :-

1st - Line :- 
NO. OF TERRORISTS(m) AND COUNTER - TERRORISTS(n) respectively, separated by space 

2nd - Line :-
POSITION OF BOMB - SITE as ( x - coordinate followed by y - coordinate)

3rd - Line :-
ORDER OF PLAYING OF TERRORISTS

4th - Line :-
ORDER OF PLAYING OF COUNTER - TERRORISTS

5th - Line :-
STORAGE TYPE ("array" or "list")

Next 7*m - Lines :-

1) PLAYER - TYPE OF i-th TERRORIST
2) STRATEGY OF i-th TERRORIST
3) ANGLE OF SIGHT OF i-th TERRORIST FROM LINE OF ORIENTATION
4) INITIAL POSITION OF i-th TERRORIST
5) ANGLE OF LINE OF ORIENTATION OF i-th TERRORITST FROM '+' X - AXIS
6) INITIAL - ENERGY - LEVEL OF i-th TERRORIST
7) SPEED ( DISTANCE PER MOVE ) OF i-th TERRORIST 

Next 7*n - Lines :-

1) PLAYER - TYPE OF i-th COUNTER - TERRORIST
2) STRATEGY OF i-th COUNTER - TERRORIST
3) ANGLE OF SIGHT OF i-th COUNTER - TERRORIST FROM LINE OF ORIENTATION
4) INITIAL POSITION OF i-th COUNTER - TERRORIST
5) ANGLE OF LINE OF ORIENTATION OF i-th COUNTER - TERRORITST FROM '+' X - AXIS
6) INITIAL - ENERGY - LEVEL OF i-th COUNTER - TERRORIST
7) SPEED ( DISTANCE PER MOVE ) OF i-th COUNTER - TERRORIST

SAMPLE - TSET - CASES :-

1) SAMPLE - INPUT :-
1 1
0 0
circular
circular
list
aggressive
bomb
90.0
3 0
180.0
10
1
cautious
bomb
90.0
4 0
180.0
10
1
SAMPLE - OUTPUT :-
COUNTER - TERRORISTS WON

2) SAMPLE - INPUT :-
1 1
0 0 
circular
circular
list
aggressive 
bomb 
50.0
1 0 
180.0 
10 
1 
cautious 
bomb 
50.0
0 1
315.0 
10 
1
SAMPLE - OUTPUT :-
TERRORISTS WON

3) SAMPLE - INPUT :-
1 1
0 0
circular
circular
array
aggressive
bomb
90.0
3 0
180.0
10
1
cautious
bomb
90.0
4 0
180.0
10
1
SAMPLE - OUTPUT :-
COUNTER - TERRORISTS WON

4) SAMPLE - INPUT :-
1 1
0 0 
circular
circular
array
aggressive 
bomb 
50.0
1 0 
180.0 
10 
1 
cautious 
bomb 
50.0
0 1
315.0 
10 
1
SAMPLE - OUTPUT :-
TERRORISTS WON
