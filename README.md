## Quick, Draw!
- this project will be a spin on the MNIST dataset, but instead of reading/analyzing numbers it will understand doodles
- GUI <- tkinter (from scratch)
- doodle data <- from Google's Quick, Draw dataset

#### Sprint 1
- Create the Tkinter drawing interface.
- ABILITIES:
    - draw on interface
    - clear the screen

#### Sprint 2
- Create the model.
- ABILITIES:
    - given doodles, predict what the image is with accuracy
    - use a text-to-voice library to say the guess outloud

#### Sprint 3
- Integrate the model and drawing interface.
- ABILITIES:
    - *WHILE* the user is drawing on the screen the AI model will guess
    - the guess won't stop until it guesses it correct (control the number of guesses it can say)

#### EXTRA:
> Model Training:
> Find a way to make the images be the training for the model. Making it better over time.