# label of usable model

1. `1230linear3`: both h5 and tflite are usable, running well. Conclusion: almost perfact.
2. `1230categorical3`: both usable and running faster than linear, but off lane often, h5 made more mistake, fix lane slowly(tflite would do a big move correction in comparison); tflite did a great job on turning right, turning left is a little messy. Conclusion: usable but could be better.
3. `1230rnn3`: h5 is not usable, it's very lag(don't know why); tflite is good at turning right, turning left is terrible, usually hit the cabinet at tail corner. Conclusion: not recommended.
