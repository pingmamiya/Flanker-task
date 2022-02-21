# Flanker-task

This MATLAB script contains all-inclusive codes that runs the arrow-version of the Flanker task.
Five arrows will be generated. The center arrow either points in the same or the opposite direction as the flanking arrows.
When all arrows point in the same direction, it is called the congruent trials.
When the center arrow points in the opposite direction, it is called the incongruent trials.
Participants will use the left or right key to respond. The correct answer should reflect the direction of the center arrow.
The maximal time is 2-minutes for a single trials. If there is no input given in a trial, the script will automatically advance to the next trial.
To begin the task, simply enter: subject_id, and the number of trials desired. 
For example, subject101, 10. This will result in 10 trials. Five of them will be congruent trials and the remaining five trials will be incongruent trials.
The results will be saved in a file called subject101_flanker.mat.
