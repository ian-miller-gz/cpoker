# cpoker
In-development snippet of a project that I completed a few years ago.

cpoker is a study of a poker variant. In the variant, four players players individually construct three hands out of thirteen cards and compare hands 1-on-1 in minature round robins.

The study sought to determine whether the variant had a strictly best strategy.

cpoker was a simulator that tested hypotheses to the effect that such-and-such strategy was srictly best.

The target strategy was to test each constructible min-max hand by scoring it in a sub-simulation game against the remaining cards. The min-max hand that performed best would be played in the super-simulation.

Results were shy of statistical significance. But the simulation was not run long enough. On our equipment, we would have needed to run the simulation for at least two weeks and we did not have the time.

The final project was never made available to the public because it could be used to cheat in online games.

This is not the final project. Only snippets of code from in-development. 1.0 was heavily refactored from the time these snippets were saved.

