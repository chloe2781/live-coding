# live-coding
Building my own vanilla live coding language and played with Sonic Pi live coding, technically a DJ now.

This is an almost minimal command-based live coding engine. Press the button to re-evaluate your code. This language allows you to specify a rhythmic pattern of beats by entering a space-separated list of times, pitches, and waves. You can also include javascript computation in the values. 

As an example:

```1+1@220 2@220*2@S 1*3@270@T```

x@y@z

x - duration of a note

y - pitch of a note

z - wave type of a note

- S - sine (default)
- W - sawtooth
- Q - square
- T - triangle
