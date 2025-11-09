# Ord like LLM game
This is a unique text-based adventure inspired by [Ord.](https://store.steampowered.com/app/1079000/Ord/) It tells tales 3 words at a time, giving the user an initial situation, 2 options and an outcome. 
But instead of the story being pre-written, it can go anywhere because situations, options, and outcomes are all generated using an LLM with API calls. A Groq API key is required which you can get for free [here](https://console.groq.com/keys)

To play the game, run the script llm_ord2.py with the right dependencies installed, you'll be prompted for your API key.

### Other scripts:

First we tried to create a custom model based on data from the game Ord. itself but since there were only about 300 entries we couldn't really get a proper working model out of it.
