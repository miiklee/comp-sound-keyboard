## Electronic keyboard made with webaudio API for Barnard COMS 3430, Computational Sound with Prof Mark Santolucito. 


With each click of a key, a new note is produced and the color of the text changes to the next in order. Once one extreme
is reached the colors reverse direction and continue back the way the came--click multiple notes at once and you will jump
forward multiple colors.

Each note plays within a consistent ADSR envelope, and when multiple notes are played simultaneously, their amplitudes are adjusted
accordingly to maintain a max total amplitude of 1 and prevent clipping.

###### supports range of notes C4 - E6 with mapping to keyboard keys as follows: 

      Z - C
      S - C#
      X - D
      D - D#
      C - E
      V - F
      G - F#
      B - G
      H - G#
      N - A
      J - A#
      M - B
      Q - C
      2 - C#
      W - D
      3 - D#
      E - E
      R - F
      5 - F#
      T - G
      6 - G#
      Y - A
      7 - A#
      U - B
      I - C
      9 - C#
      O - D
      0 - D#
      P - E
      
      
