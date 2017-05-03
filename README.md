# Install:
```
mkdir Build
cd Build
cmake ../
make
sudo make install
```

# Use:
- in your project `#include <PJ_RPI.h>`
- in compiler attach library with `-lPJ_RPI` (NOTE: remember to put this AFTER file demanding it)
ex.: `gcc -std=gnu99 main.c -lPJ_RPI -o main`