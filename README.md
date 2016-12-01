# fuxwitnazis
## Goal
There's this site to list professors with "anti American values"/who challenge facism. They crowd-source the data (you "report acts of discrimination") but I can't imagine how they'd curate the final results without humans.

I'd like to use: 
- A fake name generator (there exist apis) 
- fake university generator or list of real ones 
- a simple, HMM-driven neonazi-bullshit-generator trained on their existing descriptions of professors.

To flood them with reasonable looking garbage.

## Next Step Dev Tasks
 - use JS to fill out form OR reverse-engineer post request format from form
 - Ping/use fake name generator to acquire reasonable fake professor names
 - Scrape their descriptions of professors for training data
 - Train HMM on their descriptions
 - Generate reasonable-length horseshit using HMM
 - Pass along to JS-form-filler or make post request
 - Acquire list of real universities and/or find fake university generator
 
## Possible Extensions
 - Use real, conservative professor names
 - Deal with the inevitable captcha, either with ML or [Mechanical Turk](https://www.mturk.com/mturk/welcome)
 - laugh in their face

## Resources/Libraries:
 - ~professor~watchlist~.org (fuck linking to their site)
 - [Namefake Api](en.namefake.com/api)
 - [HMM python Library](https://github.com/hmmlearn/hmmlearn/blob/)
