# pssht

Stupid script to creep out customers passing through the Apple section of a retail store. Running it will:

1. Declare an array of sentences to play which you can customize
2. Forever
    1. Try to max out the volume
    2. Play the sentences in order with random sleeps inbetween

Disclaimer: Be careful testing it (especially with headphones) because it will max out the volume of your sound output device. You have to be really immature and bored with your life to do this. Use at your own discretion and risk. I have never in my life ran this script.

## Usage

1. Open a terminal emulator app (i.e., Terminal.app in stock macOS).

2. Download the `pssht` script.

```
cd /tmp
curl https://raw.githubusercontent.com/fabiomaia/pssht/master/pssht > pssht
chmod +x pssht
```

3. Run the `pssht` script in the background with `&` after sleeping for 15 seconds.

```
sleep 15; ./pssht &
```

4. Optionally close the terminal emulator app, discretely move away from the computer, and strategically position yourself for observation.

5. Observe the reactions.

6. Feel bad because you have nothing better to do with your life.
