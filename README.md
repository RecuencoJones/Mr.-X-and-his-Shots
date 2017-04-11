# Mr. X and his Shots

A cricket match is going to be held. The field is represented by a 1D plane. A cricketer, Mr. X has favorite shots. Each shot has a particular range. The range of the i<sup>th</sup> shot is from A<sub>i</sub> to B<sub>i</sub>. That means his favorite shot can be anywhere in this range. Each player on the opposite team can field only in a particular range. Player i can field from C<sub>i</sub> to D<sub>i</sub>. You are given the favorite shots of Mr. X and the range of players.

represents the strength of each player i.e. the number of shots player can stop.
Your task is to find:

SUM<sub>i=1</sub><sup>M</sup> S<sup>i</sup>

Game Rules: A player can stop the i<sup>th</sup> shot if the range overlaps with the player's fielding range.

For more clarity about overlapping, study the following figure:

![figure](https://s3.amazonaws.com/hr-challenge-images/8943/1441719277-9d9c50f731-L.png)

## Input Format

- The first line consists of two space separated integers, N and M.
- Each of the next N lines contains two space separated integers. The i<sup>th</sup> line contains A<sub>i</sub> and B<sub>i</sub>.
- Each of the next M lines contains two space separated integers. The i<sup>th</sup> line contains integers C<sub>i</sub> and D<sub>i</sub>.

## Output Format

- You need to print the sum of the strengths of all the players: SUM <sub>i=1</sub><sup>M</sup> S<sub>i</sub>

## Sample Input

```
4 4                
1 2 
2 3
4 5
6 7
1 5
2 3
4 7
5 7
```

## Sample Output

```
9
```

## Explanation

Player 1 can stop the 1st, 2nd and 3rd shot so the strength is 3.
Player 2 can stop the 1st and 2nd shot so the strength is 2.
Player 3 can stop the 3rd and 4th shot so the strength is 2.
Player 4 can stop the 3rd and 4th shot so the strength is 2.

The sum of the strengths of all the players is 3+2+2+2 = 9.
