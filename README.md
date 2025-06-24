# 🗳️ Runoff Voting in C

This C program simulates a ranked-choice (runoff) election. Voters rank candidates by preference. If no one wins a majority, the last-place candidate(s) are eliminated and votes are redistributed based on next preferences. This continues until someone wins or a tie is declared.

## ✅ How to Run

1. **Compile:**
clang -o runoff runoff.c -lcs50

2. **Execute:**
./runoff Alice Bob Charlie

3. **Input:**
- Enter number of voters.
- Input each voter's ranked choices.

## 🔍 What It Does

- Stores each voter's ranked preferences.
- Tabulates votes based on highest-ranked non-eliminated candidates.
- Eliminates candidates with the fewest votes.
- Declares a winner with >50% of the votes or announces a tie.

## ⚙️ Notes

- Max voters: 100  
- Max candidates: 9  
- Uses the CS50 library (https://cs50.harvard.edu/library/)

Perfect for understanding structs, loops, arrays, and conditionals in C!
