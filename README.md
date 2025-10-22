Key Features

Button Click Event

Loops through all elements with the class .drum.

Adds a click event listener to each button.

On click, it:

Gets the inner HTML of the button (the key, e.g., "w", "a", "s").

Calls makeSound() to play the corresponding drum sound.

Calls buttonAnimation() to add a visual effect.

Keyboard Press Event

Listens for any keypress on the document.

Calls makeSound() and buttonAnimation() with the pressed key.

makeSound(key) Function

Plays a different drum sound depending on the key:

w → tom-1

a → tom-2

s → tom-3

d → tom-4

j → snare

k → crash

l → kick

Uses the JavaScript Audio object to play .mp3 files.

buttonAnimation(currentKey) Function

Adds a .pressed CSS class to the button corresponding to the key.

Removes the class after 100 milliseconds for a visual click effect.

How It Works

When you click a button or press a key, the corresponding drum sound plays.

The button also flashes briefly to indicate it was pressed.
