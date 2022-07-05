# pssht

Stupid script to creep out customers passing through the Apple section of a retail store with random voice prompts coming out of a Macbook. Running it will:

1. Sleep for 15 seconds
2. Declare an array of sentences to play (which you can edit)
3. Forever
    1. Try to max out the volume
    2. Play the sentences in order with random sleeps inbetween

Disclaimer: Be careful testing it (especially with headphones) because it will max out the volume of your sound output device. Use at your own discretion and risk. I am not responsible for anything, and personally I have definitely never ran this script.

## Usage

Ideally you would read these instructions on your smartphone and:

1. Open a terminal emulator app (i.e., Terminal.app in stock macOS).

2. Download the `pssht` script.

```
git clone https://github.com/fabiomaia/pssht.git /tmp/pssht
```

3. Run the `pssht` script in the background with `&`.

```
bash /tmp/pssht/pssht &
```

4. Optionally close the terminal emulator app, discretely move away from the computer, and strategically position yourself for observation.

5. Observe the reactions.

6. Feel bad because you have nothing better to do with your life.

## License

`pssht` is appropriately licensed under the WTFPL.

```
            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                    Version 2, December 2004

 Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.
```
