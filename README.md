# lottie

Plays expored animations from After Effects in JSON format.

The JSON is passed to a variable called gameJSON.

the script is inside the html.

there are 3 functions added:

animatingGame() {called when the button is clicked - destroyes old animations - sets new animations with updated data and plays it}
textAE(index,text){changes the text value in the json file - first is the index for the layer in after effects, second is the new value}
slotTxt(n=8){loops the other text layers in the json file and sets them to a randomly picked values from an array of numbers}
