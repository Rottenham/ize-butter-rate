# ize-butter-rate

This program calculates the "butter rate" of kernel-pults as in Plants vs. Zombies.

2023/2/18 UDPATE:
Changed line 35 of main.go from `rand.Intn(15)+286` to `rand.Intn(rand.Intn(15)+286)`. This gives more accurate results.
