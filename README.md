# wordlexcel
An Excel spreadsheet to help you solve WORDLE puzzles

## What does it do?
wordlexcel is a simple tool to help you solve WORDLE puzzles, as well as an experiment on Excel's string matching and manipulation functions.

## How to use it
It's very simple. worldexcel uses cells B2, C2, and D2 for your inputs.

In cell B2, under the <b>green</b> heading, enter any letters you have that are in the correct spot. Use an interrogation sign (?) for positions you are not certain of.

Example: if you used the word WEARY and the W is marked as being in the correct spot, you would input <b>W????</b> into B2.

In cell C2, under the <b>yellow</b> heading, enter any letters that are in the solution but in the wrong position. again, Use an interrogation sign (?) for positions you have not identified yet.

Example: if you used the word WEARY and the A and Y are marked as being in the solution word but in the wrong spot, you would enter <b>??A?Y</b> into C2.

In cell D2, under the <b>gray</b> heading, enter any letters you have used that are not in the solution.

Example: if you used the word WEARY and see that the letters E and R are not in the solution, simply enter <b>ER</b> into D3.

The possible solution to the wordle puzzle will be shown under the <b>solutions</b> heading in cell C3.

## Issues

1. There is currently no way to indicate that several different letters fall into the same yellow position. You can creatively work around this in the meantime.
2. There is a limit to the amount of letters in D2 that EXCEL can match as not being in the solution. Pay attention to this, particularly towards the later rounds.
