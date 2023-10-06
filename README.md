# PsychophysicsWebExp

You can try Psychophysics experiments on the web.

https://keigom.github.io/PsychophysicsWebExp/

The objective of the experiments is to estimate the PSE (and JND) of perceived lightness for two different colors.

The saturation of those two colors is the same, but the hue and lightness are different.

Your task is to find the subjective equal lightness of both colors.

## Task
### Method of Limit/Adjustment
Adjust the lightness of the sample until you feel the lightness of the reference and the sample are the same.

In total, you will repeat this task four times with different initial lightness.

### Method of Constant
Select which reference or sample you feel is lighter.

There are 12 different lightnesses in the sample.

Each sample has four repetitions.

## CSV values
### Method of Limit
method name, participant id, elapsed time

{initial lightness of sample} x num of repetition

{participant answer} x num of repetition

### Method of Adjustment
method name, participant id, elapsed time

{ascending series (up) or descending series (down)} x num of repetition

{participant answer} x num of repetition

### Method of Constant
method name, participant id, elapsed time

{lighenss of sample} x num of samples x num of repetition

{participant answer} x num of samples x num of repetition
