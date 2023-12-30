# Abbreviated nomenclature for smart timer creation
Hangboard protocols should be easy to read with a simple universal (hangboard independent) notation.
The following notation is based on the work of Eva Lopez.

## Abbreviated syntax
The following entry:
```
2x 3x Hang @25mm +0kg #4;Open 7(3)s:57s
```
translates as
```
2x      3x      Hang       @18mm              4F       Crimp  0             7                    3               60
[#sets] <#reps> <Exercise> <Hold[left;right]> [Finger] [Grip] [AddedWeight] <HangTime[(Margin)]> <PauseRepTime> [PauseSetTime]
```
- #sets: [0-9]x
- #reps: [0-9]x
- Exercise: [Any Name]
- Hold: @[0-9]mm   or   if left/right different: @[0-9]mm;[0-9]mm   or   @[0-9]° for Slopers   or   @Jug
- Finger: [1-4]F
- Grip: Text
- AddedWeight: +[0-9]kg   or   -[0-9]kg
- Hangtime: [0-9]   time in seconds

## Examples:
+ 2x 3x Hang @18mm &4 §Crimp W+5kg 7:3:60s
+ 2x 7x Hang @Jug 7:3:150s
+ 2x 7x Hang @45mm &Front3 §Open 7:3:150s
+ 2x 7x Hang @45mm &4 §Open 7:3:150s
+ 3x MEDHang @18mm 7(3):180s
+ 3x MAXHang @30mm W+10kg 7(3):180s

# References
