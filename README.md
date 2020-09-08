# MHRD_solutions
## Solutions to [MHRD](https://store.steampowered.com/app/576030/MHRD/), a hardware design game.
All solutions are legit(i.e. fully implement the specification).

All solutions expect RAM4W16B, DECODER and CPU are optimal(i.e. has minimum number of NAND gates).
- RAM4W16B: It can be improved because the automatically generated MUX16B is not optimal, but it is too tedious to write and might exceed the 39x82 character limit.
- DECODER: I'm not sure whether the 11 NANDs global top is legit. My solution is 12 NANDs and it doesn't seem possible to cut one more.
- CPU: The CPU uses DECODER. I didn't spend much time trying to optimize this one so there might be other improvements.

Boolean simplification processes are written in comments for many solutions.

All solutions have nice code style : )
