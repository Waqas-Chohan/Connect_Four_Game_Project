Connect Four (C++ Console Game)

A terminal implementation of the classic two-player strategy game

Key Features
Gameplay

    Toss-based turn system with player name input

    6x7 grid with column-wise disc dropping

    Win detection: Horizontal/Vertical/Diagonal (forward & backward)

    Draw condition handling

Menu System

    Play Game (Toss → Turn-based play)

    Credits (Developer info)

    Rules (Game instructions)

    Records (Winner history & draw stats)

    Exit

Records Tracking

    Auto-saves to file (records.txt):

        Winner names + win turns

        Draw statistics (total turns)

Technical Implementation
Core Components
Concept Applied	Implementation Details
2D Arrays	Board state management
Control Structures	Nested loops for grid rendering
Functions	Modularized game logic (win-check, drop)
File Handling	Persistent game history
