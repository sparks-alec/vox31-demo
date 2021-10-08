# The Vox31 Cable Standards
This document describes the cabling standards used at The Vox31. It can be used as a reference when ordering new components or performing maintenance on existing systems.

# Color Code
Color | Length
------------ | -------------
🟥 Red | 5'
🟩 Green | 10'
🟦 Blue | 15'
🟪 Purple | 25'
🟧 Orange | 50'
⬜️ White | 75'
🟨 Yellow | 100'

Length is indicated via colored electrical tape wraps on both ends of all cables. In addition, most cables are also labeled with a printed heat shrink wrap.

# Terminology
The Vox31 follows the recommendation of the Professional Audio Manufacturers Alliance (PAMA) for the term "Plug" to refer to the version of a connector with pins and "Socket" to refer to the other. Other recommendations can be found at www.tinyurl.com/PAMA-NN-Guide.

# Labeling
All cable is labeled with custom heat shrink on one end.
![connector example](https://user-images.githubusercontent.com/919746/136599366-fc1ab0d5-6269-4ca5-a5fd-c20bc240f80d.png)

The first heat shrink sleeve has The Vox31 logo, with the "The" end facing the connector. The next sleeve denotes the cable length as text.
A half-width wrap of colored electrical tape follows the length. All of this is covered in clear heat shrink. The clear heat shrink should not be so long as to reduce the flexibility of the cable.

It is important that all lengths are indicated in text so the color code can be easily learned.

On XLR cables, the connector ring should be the same color as the electrical tape wraps.

### Components
Heatshrink labels are [Elite Core CUSTOM-SHRINK](https://elitecoreaudio.com/elite-core-custom-shrink-100pk/) black labels with white print. TODO: add the image files to use when ordering.

A velcro cable tie should be zip-tied to the cable on the same end as the heat shrink.

# Construction
### NL4 (speakON)
Color | Length
------------ | -------------
1+ | 🟥 Red
1- | 🟩 Green
2+ | ⬛️ Black
2- | ⬜️ White

The Vox31 frequently uses pin-swap adapter cables to separately power two speakers with one NL4 cable. All NL4 cable must be 4-wire to avoid confusion.


### DMX
Pin | Color | Purpose
-- | -- | --
1 | ⚡️ | Ground
2 | 🟥 | Data 1+
3 | ⬛️ | Data 1-
4 |  | Data 2+
5 |  | Data 2-

All DMX cable available to rental users is 5-Pin.

#### DMX over Twisted Pair
The Vox3l follows ESTA Color Code for DMX over twisted pair cable for architectual applications.
XLR Pin | Twisted Pair Color | Purpose
-- | -- | --
1 | ⬜️🟫 White/Brown | Ground
2 | 🟧🟧 Orange | Data 1+
3 | ⬜️🟧 White/Orange | Data 1-
4 | 🟩🟩 Green | Data 2+
5 | ⬜️🟩 White/Green | Data 2-


### Audio XLR
Pin | Color | Purpose
-- | -- | --
1 | ⚡️ | Shield, Ground
2 | 🟥 | Positive
3 | ⬛️ | Negative


### Twisted Pair
All data cable at The Vox31 is Cat6A. Receptacles in the grid are NE8FDX-Y6 etherCON Cat6A which is compatible with standard RJ-45 plugs.

The Vox31 uses T-568B color code.
Pin | Color
-- | --
1 | ⬜️🟧 White/Orange
2 | 🟧🟧 Orange
3 | ⬜🟩 White/Green
4 | 🟦🟦 Blue
5 | ⬜🟦 White/Blue
6 | 🟩🟩 Green
7 | ⬜️🟫 White/Brown
8 | 🟫🟫 Brown

When looking at an RJ-45 connector, Pin 1 is on the left when the clip is pointing away from you.
