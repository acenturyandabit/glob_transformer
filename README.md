# Glob Transformer
Glob transformer has three panels. The first is the plaintext input. The second is a set of transformations, coded in javascript, e.g. regex. The last is the output.

It's like SED with a GUI.

After re-implementing this on at least three separate occasions, I thought it was time I committed to making a proper nice version of it.

## How to use
1. Go to [https://acenturyandabit.github.io/glob_transformer/]
1. Copy your text into the first box.
2. Complete the transformation function. 
3. Press the 'execute' button.
4. Replace the text in the first box, and press 'execute' as many times as you need to.

## Notes
- Everything runs in your browser. If you want some kind of localstorage to save your scripts, feel free to submit a PR.
- Sorry its not dark mode .-.
- Unsafe eval is used. Just a heads up.
- Needless to say, do not use this in prod.