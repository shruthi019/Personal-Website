.. index:: PGN Notation

PGN Notation
============

This is a sample PGN file:

::

    [Event "Tal Memorial"]
    [Site "Moscow RUS"]
    [Date "2010.11.08"]
    [Round "4"]
    [White "Mamedyarov, Shakhriyar"]
    [Black "Aronian, Levon"]
    [Result "1/2-1/2"]
    [WhiteTitle "GM"]
    [BlackTitle "GM"]
    [WhiteElo "2763"]
    [BlackElo "2801"]
    [ECO "D11"]
    [Opening "QGD Slav"]
    [Variation "3.Nf3"]
    [WhiteFideId "13401319"]
    [BlackFideId "13300474"]
    [EventDate "2010.11.05"]
    
    1. d4 d5 2. c4 c6 3. Nf3 Nf6 4. Qc2 dxc4 5. Qxc4 Bf5 6. g3 e6 7. Bg2 Be7 8. O-O
    O-O 9. Rd1 Nbd7 10. e3 e5 11. Nc3 Qc7 12. h3 Rfe8 13. dxe5 Nxe5 14. Nxe5 Qxe5
    15. e4 Be6 16. Qe2 Bb4 17. f4 Qa5 18. Be3 Rad8 19. Qf2 Rxd1+ 20. Rxd1 Bxc3 21.
    bxc3 Qa4 22. Rd4 Bc4 23. Qd2 c5 24. Rd8 Rxd8 25. Qxd8+ Qe8 26. Qd6 b6 27. e5 Qd7
    28. Qb8+ Ne8 29. Qa8 Kf8 30. a3 Qd3 31. Bf2 Qd1+ 32. Kh2 Qc2 33. Kg1 Qd1+ 34.
    Kh2 Qc2 35. Kg1 1/2-1/2

Portable Game Notation (PGN) is a plain text computer-processible format for recording chess games 
(both the moves and related data), supported by many chess programs.
The chess moves are given in algebraic chess notation.
The PGN code begins with a set of 'tag pairs' (the tag names and corresponding values) and the 'movetext'
(chess moves with optional comments).

Tag Pairs
---------
Tag pairs begin with an initial left bracket ``[`` followed by the name of the tag. The value of the tag is 
enclosed in double quotes and then the tag is terminated with ``]``.
There are seventeen such tag pairs in the sample provided above.

Movetext
--------
This describes the actual moves of the game. The moves are numbered as the number followed by a period. (see above)

.. table:: Letter Abbreviations for Pieces

   ============ ==============
    Piece/Pawn   Abbreviation
   ============ ==============
    King            K
    Queen           Q
    Rook            R
    Bishop          B
    Knight          N
    Pawn            " " / P
   ============ ==============

The algebraic name of any square is as per usual algebraic chess notation; from white's perspective, the leftmost square closest to 
white is a1, the rightmost square closest to the white is h1, and the rightmost (from white's perspective) square closest to black side 
is h8.

In a few cases a more detailed representation is needed to resolve ambiguity; if so, the piece's file letter, numerical rank, or the 
exact square is inserted after the moving piece's name (in that order of preference). Thus, Nge2 specifies that the knight originally on 
the g-file moves to e2.

Further Reading
---------------
You can read more on `PGN Notation - Wikipedia <https://en.wikipedia.org/wiki/Portable_Game_Notation>`_






