+++
title = "Volca Keys Tutorial"
sort_by = "weight"
+++

The Korg volca keys is an **analog synthesiser**.
That means we basically we have a musical instrument that creates sound signals from manipulating an electrical current.

**Analog** means no computers involved! We will do everything by manipulating current and resistance in a circuit and thus shaping physical sound waves of the signal.
**Synthesis** by itself just means that creating something through composition, but we'll be creating sounds or even music. In particular, we'll make use of substractive synthesis, shaping a sound through filtering.

The Volca keys is a great synth to learn the basics, because it has everything an analog synth needs in a nice and simple interface.
With this knowledge you can also work with digital synths, as they just imitate through code what ananlog synths do with electricity.

So at the core, we need to learn about sound waves and how wave shapes and manipulation influences the sound. Physics and math! Hurray!

Of course you can also just try and turn the knobs and see what's happening, but it's definitely more straight forward if you have at least a little bit of an idea what you are doing.

# The interface

First let's look at the device more closely before diving into the theory.

If you look at the Volca you can, purely visually, make out two parts. The top part with the knobs is where the sound is created. The lower part with the keys is quite digital, actually, and will help us later on with recording and other things.

Let's start with the top.

In the top left corner you have the power button. Press and hold to turn it on (and off). Next to it you see a 9V DC jack, which you can use to power the Volca. Alternatively you can use batteries, which come included.

Otherwise the top part is separated in to different sections with vertical lines.
The left most section is labelled VCO and it's both the two big black knobs as well as the three transparent ones directly under the label.

The next three sections are labelled VCF, LFO and EG and each has three transparent knobs.

To the right, we have a MIDI input and audio jacks for synchronising with other analog synths and a headphone jack so you can use headphones and don't annoy people around you with your experiments.

Below that we have a row of knobs with the last all the way to the right being master volume, feel free to already turn it all the way up (clock-wise)!

Below that we have functional buttons that we'll use together with the bottom half of the Volca.

The bottom half can be a bit difficult to understand. First, you can see it emulates a piano keyboard with white and black keys (hence the name, Volca keys). With this we'll be able to play notes like we would on a piano! If you don't know how to read or play piano, no worries. This definitely something you can just play play around with later and see what sounds good to you.
All white keys are individually labelled for other functions, but also grouped by labels directly beneath them.
And below every key there is also an light that, among other things, indicates usually indicates the state of the individual function.

Now we can turn some knobs!

# The knobs

Alright! First, turn the Volca on and turn all transparent knobs everywhere down (counter-clockwise) and the black volume knob all the way up and the tempo next to it to a 12 o'clock position.

You can turn the black knobs on the left on UNISON and 8' if you want.
You will hear nothing. Try and touch some keys on the keyboard. You should hear a sound.
Perfect.

## VCO pt 1

The volca creates sound through three integrated osciallators. An oscillator creates periodic waves (sine waves, anyone?) which is the basis for our manipulation.

The upper black knob on the left is called **Voice** and decides how the oscillators should work with each other:
- UNISON: all oscillators create the same wave, you can only touch one key at a time
- POLY: each oscillator creates a dedicated wave per key you're touching, maximum of three
- OCTAVE: two oscillators create the base wave and the third creates a wave with a pitch an octave higher
- FIFTH: two oscillators create the base wave and the third creates a wave with a pitch five halftones higher
- UNISON RING and POLY RING we are used for ring modulation which we will not cover but are a great follow up topic!

The lower black knob is called **Octave** and shifts, you guessed it, the octaves of our keyboard higher or lower.

You might not hear any changes with the these two knobs yet, because there is nothing exciting going on yet. But that is about to change.

Under VCF, turn Cutoff to about a 2 o'clock position. Play some notes on the keyboard and change Voice and Octave!

Amazing, isn't it? We'll lean about what we just did in a second. But for playing around there is are a few knobs that make our lives easier, so we'll do that next.

## EG

EG stands for Envelope Generator and describes the shape of the waves being generated and separates it into different phases and mappes each to a knob:

- **Attack** is the time from pressing a key to reaching the sustain level. No attack means the sound comes immediately and full attack means the sound fades in
- **Decay/Release**: **Decay** is the time after attack was reached and it moves into sustain. **Realease** sets the time for how long the note fades out after the key was released. Usually these phases are split into two knobs, here we only have one for both
- **Sustain** sets the maintained volume of the note pressed after the decay phase is over

Try the different knobs in the EG and get a feel for how they sound.

Both **VCO** and **VCF** have a knob called **EG int** it basically sets how much much the settings of the **EG** effect the VCO pitch and the VCF cutoff.

For the next couple of sections its nicer to turn **Sustain** up to 12 o'clock to better hear what is happening.

## VCF

Remember when we turned up **Cutoff** under **VCF**? So what did that do?

VCF stands for Voltage Controlled Filter and filters are at the heart of subtractive synthesis.
Why? Because the filter decides what to filter or cut or *subtract* from the soundwave!

How does it do this? A sound is basically waves vibrating or oscillating at certain frequency. Frequency is times per second (or Hertz (Hz)) and human hearing can pick up frequencies from 20 to 20000 Hz. The string in a piano playing middle A should vibrate at around 400Hz, so around 400 times per second.
But no sound in nature is so pure! There are a lot of other waves mixed within, the so called (harmonic) overtones and they also determine how we perceive different sound. Like a piano playing middle C is different from an adult voice singing to a flute playing and so on.

With the VCF we can cut away from those overtone and change the wave and the sound. The **Cutoff** knob determines just that. Press a note and turn the **Cutoff** knob while holing it (**Sustain** should be turned up, too). Do you hear the difference?

Underneath the **Cutoff** is the **Peak** knob. Peak describes the how the curve of the filter looks like and can highlight some of the overtones. Try some configurations with **Cutoff** and **Peak**.

## VCO pt 2

Let's get back to the missing three **VCO** knobs.

Remember when we said in the beginning that the volca keys has three oscillators? Now is the time to play them! The **Detune** knob shifts the pitch for each oscillator, try this in with a couple of different **Voices**!

**Portamento** changes the portamento time, basically sounds fade into each other. Just try it, you'll hear it immediately.

## LFO

The LFO, or **Low Frequency Oscillator** is the last piece missing. It's another oscillator! It gives us cyclical changes that we can use to modify or modulate our sound as it's applied to the **VCO pitch** and **VCF cutoff frequency** throught the two bottom knobs respectively.

**Rate** sets the cycle length. The shorter the cycle (turned up) the 'faster' we will perceive it.

Try it out! Turn the **Rate** and try alternating the **Pitch int** and **Cutoff int**. Do you notice the different aspects that they influence?

## Delay

After you shaped your sound you can apply a Delay **Time** and **Feedback** with these knobs. **Feeback** sets how many iterations or 'echos' you want and **Time** sets the time between them.

## That's it!

This is what all the knobs are for! Now it's up to you to find something that sounds good to you!


# Settings and keys

Let's look at the recording functionality and put our sounds to use! For that we need to look at the remaining buttons and interface keys.

## Play and record

We'll use the play and record buttons to - you guessed it - play and record. Push the play button! You will hear a preprogrammed sequence. Push it again to stop. Record we'll try out later.

## Memory and func

The **Func** button has a variety of functions together with other buttons and keys and we'll use it quite a bit from here on.

The volca keys actually has 8 memory slots.

Press **Memory** button and you should see the red LEDs under the keys labelled M1 - M8 light up. One of them should be blinking and indicating with memory is active right now.

While pressing **Memory** touch one of the M keys to load a different memory slot. If you press **Play** now, you should hear a different sequence.

By pressing **Memory** and **Func** together and then an M key you can save the current sequence to that selected slot. We'll do that in a second.

## The keys

We'll only look at the most important keys in detail here, both for brevity and to keep it simple. Some we'll loko at later when it makes more sense to introduce them.

The state of each key is indicated by the LED underneath it (on -> active, off -> inactive) and can be changed by pressing **Func** and the respective key.

## Clear all

**Func** and **All** erased the sequence data. Perfect to start a new recording.

## LFO

The keys M4 - M7 are also labelled as LFO and they are options you can set for the **LFO**. Press **Func** and M4 or M5 or M6 to change the type of wave to saw, tri or square wave respectively. Can you hear the differences? We'll ignore M7 for now.

## Metronome

We have a built in metronome to help us keep in tact. Press **Func** and the **Metronome** to turn it on and off. But you will only hear the metronome when in **Play**ing.

## Tempo

**Func** and the keys labelled as **Tempo** let you set the tempo either relative to the **Tempo** knob or the MIDI to SYNC In jacks. We won't cover the external tempo options here, so only the **Tempo** knob is relevant for us right now. 1/1 means its the tempo specified by the knob, 1/2 is half as fast, 1/4 is a quarter of that.

## Motion sequence


# Making music

Finally it's time to record something!

## Recording

I like to start with lower tones to make some kind of rhythm. Turn **Octave** to 32' and create a sound that works for you.

Then press **Play** with the metronome activated and try to play some notes that fit in with the metronome. Happy? Then press **Record** to record the sequence. Press **Record** again to stop.

You will notice that we can only record one cycle as indicated by the light running throught the LEDs. Each cycle repeats the recorded sequence of notes.

If you're not happy use **Func** and **Clear All** to start again.

Next I want to put something on top of it. Change the **Octave** to 8' or 4' and change the sound. When you're ready you can hit record and record the new sequence on top of the other on.

Repeat this until you're satisfied with what you have.

## Motion Sequence

One thing you need to know is that when we record something, we don't actually record the position of the knobs that are used to make the sound.
What we can record though is the movement of the knobs, if **Motion Sequence** is **ON**.

When you **record** with **Motion sequence** activated and turn a know, this knob will start blinking as an indicator that this movement is now recorded.

Sometimes it's what you want, sometimes it's not. For example then you record and then quickly want to change the LFO rate before playing a note, this movememnt could accidentally be recorded as well.

In the beginning I think it's most effective to record your sounds without motion sequence and then consiously record a motion sequence on top of it.

You can clear the motion sequence with **Func** and **Motion Sequence Clear**.

## Active Step
