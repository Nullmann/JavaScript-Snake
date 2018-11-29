This is a heavily modified version of Patrick Gillespie's Javascript Snake.
It was made for a survey about gaming at the TU Darmstadt.

Changes made:
* It is now timed for 2 minutes
   * You respawn after dying, your score is preserved
* Mobile-ready
   * Swipe-motions achieved with hammerjs
   * Mobile version is set to a slower 120ms compared to keyboard version with 70ms
* Deactivated pause function
* Food gives iteratively more points
   * 1st 10 points, 2nd 11 points, ...
* A point cannot spawn at the edge of the field (less random, fairer)
* No options, Text is now in German
* Design changed to simpe colours
   * Black & White backgrounds
   * Snake is green, "Apple" is red
