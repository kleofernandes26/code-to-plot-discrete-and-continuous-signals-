Overview

This MATLAB script allows users to perform various signal processing operations on a discrete-time signal. The operations include:
1) Displaying the original signal.
2) Time-shifting the signal.
3) Time-scaling the shifted signal.
4) Reversing the signal (either the shifted or the scaled version).

This script uses user inputs to dynamically modify the signal and visualize the changes through plots.

Features:

1. Original Signal
The script prompts the user to input a discrete-time signal and displays it using a stem plot.

2. Time Shifting
The user specifies a shift value, and the script shifts the signal accordingly.

3. Time Scaling
The user inputs a scaling factor to compress or expand the signal in time.

4. Reversal
The user can choose to reverse the shifted or scaled signal, which is then displayed.

Input Prompts:
1) Starting and Ending Time (k and m): Defines the range of the signal's time indices.
2) Signal Values (x): Specifies the discrete-time signal.
3) Shift Value (f): Determines the amount by which the signal is shifted in time.
4) Scaling Factor (b): Specifies the factor by which the signal is scaled in time. If no scaling is needed, enter 0.
5) Reversal Choice (a): Enter 1 for reversing the signal, or 0 to skip.

Plot Details

The script generates up to four subplots:

1) Original Sequence: Displays the original signal.
2) Shifted Signal: Displays the signal after time-shifting.
3) Scaled Signal: Displays the signal after time-scaling (if scaling is applied).
4) Reversed Signal: Displays the reversed version of either the shifted or scaled signal, depending on user input.

Usage Instructions

Copy and paste the script into a MATLAB .m file.
Run the script in MATLAB.
Follow the prompts to input the required values.
View the generated plots to analyze the signal transformations.

Example Workflow
Enter the starting and ending time indices (k = 0, m = 4).
Input the signal values (x = [1 2 3 4 5]).
Enter the shift value (f = 2).
Enter the scaling factor (b = 2).
Choose to reverse the signal (a = 1).
View the four plots showing the original, shifted, scaled, and reversed signals.

Notes:-

Ensure the input signal length matches the specified time indices.
The script automatically handles cases where scaling is not applied (b = 0).
Axis limits for plots are fixed as [-5 5] for time and [0 5] for amplitude, which can be adjusted as needed.

File Structure

MATLAB Script File: Contains the main code to execute signal processing operations.
Plots: Visualizes each transformation step for better understanding.


