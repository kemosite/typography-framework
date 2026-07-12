**Ideal Font Size**

Automatically and responsively setting an ideal font size in CSS can be done as a function of:

--vmin-one-degree-arc: calc( 100vmin / 30 ); /* 1 degree of arc = 3.333vmin = 4 letter fixation point

--letter-width: calc( var(--kemosite-vmin-one-degree-arc) / 4;

--font-size: calc( var(--letter-width) / 0.52 /* Or actual x-height of font */

Or, in short:

--font-size: 1.602vmin
