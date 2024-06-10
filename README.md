![wordle_big_animation2](https://github.com/Dom17Pham/WordleMe/assets/71042283/8f23361b-07b2-4624-a2c1-32a57c232783)

# Wordle Analysis
Wordle is the game that's taken over our mornings, lunch breaks, and any spare moment where we pretend to be doing something productive. 
It's the perfect blend of brain-teaser and time-waster, and now, thanks to this nifty analysis, you might just beat your friends more consistently!
(Personally I'm awful at this game so this is what's driving me to analyze it)
##
### What’s in This Analysis?
**The aim of this analysis is to uncover the hidden patterns and trends in potential guesses and solution words that can help us improve our guesses of the wordle.**

The analysis is done in a jupyter notebook which dives deep into the patterns and probabilities of Wordle along with interesting data visualizations
to help support our findings. The notebook provides insights to:
* Identify which letters and combinations are most likely to appear.
* Strategize your guesses to maximize your chances of hitting the wordle sooner.

The dataset that is used for this analysis can be found here on Kaggle:

https://www.kaggle.com/datasets/bcruise/wordle-valid-words
##
### Wordle Rules 
The rules are simple, yet the challenge is immense: guess a five-letter word within six tries. 
Every guess comes with color-coded feedback:
* Green: You've nailed it! The letter is in the word and in the right spot.
* Yellow: Well Yes, But Actually No. The letter is in the word but in the wrong spot.
* Grey: Nope, not today. The letter is unfortunately not in the word.

### Sounds Simple, Right?
With 2,309 possible words, the odds are not always in your favor. 
Random guessing is a strategy, sure, but it's not that effective. That’s where our analysis comes into play.
With this anaylsis we can potentially gain insights that we can leverage to improve and optimize our guesses and
uncover the wordle in less attempts i.e within 3-4 guesses. 
##
### Why You’ll Love This
This analysis is not just about winning (No, it really is). 
It’s about understanding the game on a deeper level and having fun while doing it. 
Anyways, I hope this analysis becomes helpful in your next wordle game.

Happy guessing!
