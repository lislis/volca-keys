+++
title = "Interface"
date = "2022-12-12"
description = "Interface"
weight = 1
+++

The interface is roughly split into two parts: the knobs in the top for actual sound synthesis and the rest for settings and recording.

If you're already familiar with other synthesizers and know your way around the knobs, feel free to skip to the [settings section](settings-aka-keys-and-buttons).


# Synthesis aka the knobs

Let's look at the top part first. Most of the knobs here have something to do with the synthesis or generation of the sound.

![](/top.jpg)

To see what each knob does, we'll do through them one by one.

First, turn the volca on (you should see red lights) and turn all transparent knobs everywhere down (counter-clockwise) and the black volume knob all the way up and the tempo next to it to a 12 o'clock position.

You can turn the black knobs on the left on UNISON and 8' for now.

![](/step1.jpg)


Try and touch some keys on the keyboard. You should hear a quiet, dull sound.

Perfect.

## VCO pt 1

The volca creates sound through three integrated **osciallators**. An oscillator creates periodic waves (maybe you've heard of sine waves?) which are the basis for our manipulation. VCO stands for Voltage Controlled Oscillator, btw.

![](/step2.jpg)

The upper black knob on the left is called **Voice** and decides how the three oscillators should work together:
- UNISON: all oscillators create the same wave with the pitch of the note you're touching. Only one note at a time is played
- POLY: each oscillator creates a dedicated wave per key you're touching, maximum of three
- OCTAVE: two oscillators create the base wave and the third creates a wave with a pitch an octave higher
- FIFTH: two oscillators create the base wave and the third creates a wave with a pitch five halftones higher
- UNISON RING and POLY RING we are used for ring modulation which we will not cover but are a great follow up topic!

The lower black knob is called **Octave** and shifts the keyboard octaves higher higher or lower. So instead of one long keyboard with lots of keys we can make due with just they keys here but can still play a wide range.

These two don't do much by themselves, but feel encouraged to also switch up those in later stages of this tutorial.

But let's actually hear something: Under **VCF**, turn **Cutoff** to about a 2 o'clock position.

Play some notes on the keyboard and change Voice and Octave! Amazing, isn't it?

We'll learn about what we just did in a second. But for playing around there is are a few knobs that make our lives easier, so we'll do that next.

## EG

**EG** stands for Envelope Generator and describes the shape of the waves being generated and separates it into different phases and maps each to a knob:

![](/step4.jpg)

- **Attack** is the time from pressing a key to reaching the sustain level. No attack means the sound comes immediately and full attack means the sound fades in
- **Decay/Release**: Usually these phases are split into two knobs, here we only have one for both
  - **Decay** is the time after attack was reached and it moves into sustain.
  - **Realease** sets the time for how long the note fades out after the key was released.

- **Sustain** sets the maintained volume of the note pressed after the decay phase is over

Try the different knobs in the EG and get a feel for how they sound what they influence.

For the next couple of sections its nicer to turn **Sustain** up to 12 o'clock to better hear what is happening when you keep pressing a key.

Both **VCO** and **VCF** have a knob called **EG int**. It sets how much much the settings of the **EG** effect the VCO pitch and the VCF cutoff. We'll talk about those next.


## VCF

Remember when we turned up **Cutoff** under **VCF**? So what did that do?

**VCF** stands for Voltage Controlled Filter and filters are at the **heart of subtractive synthesis**.
Why? Because the filter decides what to filter or cut or *subtract* from the soundwave!

![](/step3.jpg)

Real quick background on that:
Sound is all about waves vibrating or oscillating at a certain frequency. The string in a piano playing middle A, for example, should vibrate at around 400 times per second (or 400Hz).

But no sound in nature is so pure! There are a lot of other waves mixed within and they naturally sound good together. These are the so called (harmonic) **overtones** and they also determine how we perceive different sound. Like a piano playing is different from an adult voice singing to a flute playing even if they all play the same note.

With the VCF we can cut away from those overtones and thus change how we perceive the sound without changing the note. The **Cutoff** knob determines just that. Press a note and turn the **Cutoff** knob while holding it (**Sustain** should be turned up, too). Do you hear the difference?

Underneath the **Cutoff** is the **Peak** knob. Peak describes the how the curve of the filter looks like and can highlight some of the overtones. Try some configurations with **Cutoff** and **Peak**.

## VCO pt 2

Let's get back to the missing three **VCO** knobs.

![](/step2.jpg)

Remember when we said in the beginning that the volca keys has three oscillators? Now is the time to play them!

The **Detune** knob shifts the pitch for each oscillator just a little bit and makes it sound fuller. Try this in with a couple of different **Voices**!

**Portamento** changes the portamento time, basically sounds fade into each other. Just try it and play quick succession of notes, you'll hear it immediately.

## LFO

![](/step5.jpg)

The LFO, or **Low Frequency Oscillator** is the last piece missing. It's another oscillator! It gives us cyclical changes that we can use to modify or modulate our sound as it's applied to the **VCO pitch** and **VCF cutoff frequency** throught the two bottom knobs respectively.

**Rate** sets the cycle length. The shorter the cycle (turned up) the 'faster' we will perceive it.

Try it out! Turn the **Rate** up and try alternating the **Pitch int** and **Cutoff int**. Do you notice the different aspects that they influence?

## Delay

![](/step6.jpg)

After you shaped your sound you can apply a Delay **Time** and **Feedback** with these knobs. **Feeback** sets how many iterations or 'echos' you want and **Time** sets the time between them.

## That's it!

You can now shape the sound! It's up to you to find something that sounds good to you!


# Settings aka keys and buttons

Let's look at the recording functionality and put our sounds to use! For that we need to look at the remaining buttons and interface keys.

![](/bottom.jpg)

## Play and record

![](/step7.jpg)

We'll use the play and record buttons to - you guessed it - play and record. Push the play button! You will hear a preprogrammed sequence. Push it again to stop. Record we'll try out later.

## Memory and func

![](/step8.jpg)

The **Func** button has a variety of functions together with other buttons and keys and we'll use it quite a bit from here on out!

The volca keys has 8 memory slots.

Press **Memory** button and you should see the red LEDs under the keys labelled M1 - M8 light up. One of them should be blinking and indicating with memory is active right now.

While pressing **Memory** touch one of the M keys to load a different memory slot. If you press **Play** now, you should hear a different sequence.

By pressing **Memory** and **Func** together and then an M key you can save the current sequence to that selected slot. We'll do that with our own sequence later.

## The keys

![](/step9.jpg)

Surprise, there are piano inspired keys here! You probably noticed the name giving feature of the volca already, and I've already been telling you to press keys since the very beginning. Good job!

You hopefully also noticed that you don't need to know anything about playing the piano to get some cool sounds out of the volca, which is just fine! Bonus points if you do know how to play the piano, though, as it will definitely come in handy.

All of the 'white' keys of the piano have a second function together with the **Func** button. We'll only look at the most important keys in detail here, both for brevity and to keep it simple. Some we'll introduce at later point and some we'll just skip entirely. Content for self-study!

The state of each key is indicated by the LED underneath it (on -> active, off -> inactive) and can be changed by pressing **Func** and the respective key.

## Clear all

![](/step10.jpg)

**Func** and **All** erased the sequence data. Perfect to start a new recording.

## LFO settings

![](/step11.jpg)

The keys M4 - M7 are also labelled as LFO and they are options you can set for the **LFO**. Press **Func** and M4 or M5 or M6 to change the type of wave to saw, tri or square wave respectively. Can you hear the differences? We'll ignore M7 for now.

## Metronome

![](/step12.jpg)

We have a built in metronome to help us keep in tact. Press **Func** and the **Metronome** to turn it on and off. But you will only hear the metronome when in **Play**ing!

This goes super well together with the **Tempo** knob!

## Tempo

![](/step13.jpg)

Not super relevant for us but I do want to mention it:
**Func** and the keys labelled as **Tempo** let you set the tempo either relative to either the **Tempo** knob or the MIDI to SYNC In jacks. We won't cover the external tempo options here, so only the **Tempo** knob is relevant for us right now. 1/1 means its the tempo specified by the knob, 1/2 is half as fast, 1/4 is a quarter of that.

## That's it

You can now load different memory slots and clear them, play and pause a sequence with or without metronome, change the base wave of the LFO and learned something about tempo settings.

Next up: [Getting to know some workflows](/workflow)!
