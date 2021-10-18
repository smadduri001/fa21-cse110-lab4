1. values added:  20
2. final result:  20
3. values added:  20
4. The code returns an error because result's scope is only within the if statement's block and therefore result cannot be accessed on line 13.
5. Nothing is printed by line 9. The code returns an error as line 9 tries to reassign the value of a const variable, which you can't do.
6. Nothing is printed by line 13 as the attempt at reassignment of a const variable in line 7 returns an error. Even without that line 13 would've returned an error as result's scope doesn't extend to line 13, as line 13 is outside the if statement block.