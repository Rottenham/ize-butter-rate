# ize-butter-rate

This program calculates the "butter rate" of kernel-pults as in Plants vs. Zombies.

## 2023/2/21 UDPATE

Changed line 35 of main.go from
```
rand.Intn(15)+286
```
to 
```
randResult := rand.Intn(300) - rand.Intn(15)
for randResult < 0 {
    randResult = rand.Intn(300) - rand.Intn(15)
}
```
This gives more accurate results.