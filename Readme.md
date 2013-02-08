# OSLO hacking

Functionality added to [OSLO-EDU][oslo], the optics simulation program.

It is using the CCL programming language, which is a subset of C with
a bunch of built in commands.

The proper place of this is in the Public directory of OSLO (e.g on
Windows 7 it is `C:\Users\Public\Documents\OSLO66 EDU\public`.

## Commands

### space()

In `spacing.ccl`, for appropriately set up singlet+dublet pair, adjust
the spacing and find the Strehl number as a function of spacing.

Print results (position, Strehl for best focus and smallest OPD, NA, EFL)
in the text window and also plot it.

Plenty to to about this, but basic functionality is there, can use
Matplotlib for nicer plot.

[oslo]: http://www.lambdares.com/education/oslo_edu "OSLO homepage"
