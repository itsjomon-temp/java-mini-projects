# Memory Game
A simple Java console program that challenges players memory skills. The game features eight cards (four matching pairs) that are randomly shuffled and placed face down, represented by numbered slots from 0 to 7. Players take turns entering two different indices between 0 and 7 to flip the cards and reveal what is underneath. If the two flipped cards match, they stay face up; if not, they are turned back down. The game continues until all pairs are found, and a congratulatory message is displayed at the end.

## Sample Input & Output

```
Welcome to the Memory Game!
|   |   |   |   |   |   |   |   |
Enter index of first card to flip:
0
| A |   |   |   |   |   |   |   |
Enter index of second card to flip:
1
| A | D |   |   |   |   |   |   |
Sorry, those cards don't match.
|   |   |   |   |   |   |   |   |
Enter index of first card to flip:
0
| A |   |   |   |   |   |   |   |
Enter index of second card to flip:
4
| A |   |   |   | A |   |   |   |
You found a pair!
| A |   |   |   | A |   |   |   |
Enter index of first card to flip:
1
| A | D |   |   | A |   |   |   |
Enter index of second card to flip:
7
| A | D |   |   | A |   |   | B |
Sorry, those cards don't match.
| A |   |   |   | A |   |   |   |
Enter index of first card to flip:
1
| A | D |   |   | A |   |   |   |
Enter index of second card to flip:
3
| A | D |   | C | A |   |   |   |
Sorry, those cards don't match.
| A |   |   |   | A |   |   |   |
Enter index of first card to flip:
1
| A | D |   |   | A |   |   |   |
Enter index of second card to flip:
6
| A | D |   |   | A |   | D |   |
You found a pair!
| A | D |   |   | A |   | D |   |
Enter index of first card to flip:
2
| A | D | B |   | A |   | D |   |
Enter index of second card to flip:
7
| A | D | B |   | A |   | D | B |
You found a pair!
| A | D | B |   | A |   | D | B |
Enter index of first card to flip:
3
| A | D | B | C | A |   | D | B |
Enter index of second card to flip:
5
| A | D | B | C | A | C | D | B |
You found a pair!
Congratulations, you won!
```