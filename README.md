# JavaScript Simon Game -- NO jquery

#### "Simon is an electronic game of short-term memory skill invented by Ralph H. Baer and Howard J. Morrison, working for toy design firm Marvin Glass and Associates, with software programming by Lenny Cope. The device creates a series of tones and lights and requires a user to repeat the sequence. -- Wikipedia"

This Simon JS project recreates the famous game, with unique sounds for each button courtesy of free downloaded from **Pixabay.com**.

- This project uses 100% **Vanilla JavaScript** (NO jquery)
- Uses **keydown** event to start game (any key press with do)
- **serveBtn()** function pics a random button and flashes it with the sound.
- random button **sequence** is stored in an array
- User tries to follow along by clicking the sequence after each new button is added.
- Button click function checks if button clicked by user matches corresponding color in the **sequence** array.
