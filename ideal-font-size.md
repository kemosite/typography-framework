**Ideal Font Size**

Automatically and responsively setting an ideal font size in CSS can be done as a function of:
- vmin-one-degree-arc: calc( 100vmin / 30 ); /* 1 degree of arc = 3.333vmin = 4-5 letter fixation point
- letter-diameter: calc( var(--kemosite-vmin-one-degree-arc) / 4.5 (Average of 4 and 5);
- font-size: calc( var(--letter-width) / 0.5 /* Or actual x-height of font */

Or, in short:
- font-size: 1.481vmin

Example from a 1920 x 1080 monitor:
- Minimum dimension is 1080 pixels
- 1080 pixels / 30 degrees = 1 degree = 36 pixels
- 36 pixels / 4.5 letter fixation point = 8 pixel diameter per letter
- 8 pixels / x-height (0.5) = 16 pixels font size
- 16 pixels / 1080 minimum dimension = 1.481% = 1.481vmin
