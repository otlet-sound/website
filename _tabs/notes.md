---
# the default layout is 'page'
icon: fas fa-pencil
order: 5
---

Running notes for the moment

## EQUIPMENT

[Godin Guitars](https://godinguitars.com/)

### DEFINITIONS

[Coil](https://www.sweetwater.com/insync/coil/)

Magnetic Pickup - A simple mechanism based on a magnetic field that induces a current in a coil in that
field. The pickup converts string vibration into electrical energy, usually by means of a permanent magnet,
or six magnetic polepieces, surrounded by a wire coil.

Hexaphonic Pickup - A guitar pickup with a discrete output for each of the six strings of a standard 
guitar. This arrangement permits separate processing for each string. A hexaphonic pickup attached to 
a converter can sense the pitch coming from individual strings for conversion into MIDI note messages.


13-Pin Connection - An output of the guitar can be connected to a guitar-to-MIDI converter, a guitar 
synthesizer, or a guitar modeling system. The 13-pin connector carries individual output from each of 
the six strings, the signal from the guitar’s regular pickups, and several control signals. If the 
connected device can provide it, phantom power too.

Note that the 13-pin connection itself does not carry MIDI information. An ancillary box must be used 
to convert the analog signals created by the hex pickup into MIDI note and control data.

```text
PIN Diagram

Pin 1 – signal 1
Pin 2 – signal 2
Pin 3 – signal 3
Pin 4 – signal 4
Pin 5 – signal 5
Pin 6 – signal 6
Pin 7 – output from regular guitar pickups
Pin 8 – synthesizer volume control signal
Pin 9 – not used/no connection
Pin 10 – synthesizer switch control signal (normally used for preset down)
Pin 11 – synthesizer switch control signal (normally used for preset up)
Pin 12 – +7 volts power
Pin 13 – –7 volts power
```

A de facto standard devised by Roland for connecting guitars and basses equipped with a hex pickup to a guitar synthesizer. The cable carries the audio signal from each of the 6 individual coils of the hex pickup to the synth for processing and analysis. The interface also provides +/- 7V DC power to the guitar's electronics. Additionally, it can carry a few control signals from controls on the guitar, and a mono signal from the guitar's conventional pickups. 

Roland 13-pin DIN socket

![Pic](/assets/img/13-DIN-pinout.png)

13-pin PIN Out
![Pic]()

| DIN pin | Signal           | Wire color   | GK-1 pin |
|---------|------------------|--------------|----------|
| 1	      | SIG1	            | red	         | 19       |
| 2 	     | SIG2	            | pink         | 20       |
| 3	      | SIG3             | yellow	      | 21       |
| 4       | 	SIG4            | dark green   | 22       |
| 5	      | SIG5	            | light green	 | 23       |
| 6	      | SIG6	            | orange       | 24       |
| 7	      | GT.SIG	          | light blue   | 18       |
| 8	      | SY.VOL	          | dark blue    | 9        |
| 9	      | "Guitar/Mix/GK"	 | gray         | 7        |
| 10	     | S1 ("down")      | brown        | 15       |
| 11	     | S2 ("up")	       | white        | 16       |
| 12	     | +7V              | black	       | 1 (+15V) |
| 13	     | -7V              | purple	      | 2 (-15V) |
