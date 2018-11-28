# GOTO10

My interpretation of the one-line Commodore 64 BASIC program: `10 PRINT CHR$(205.5+RND(1)); : GOTO 10`

Currently this only contains the C++ and Python version. I will try to include other interpretations in different languages in the future.

# C++

``` cpp
#include <iostream> 
int main() { while(true) { std::cout << static_cast<char>(32 + 63*(rand()%2)); } }
```
# Python

```python
import random
while(1):
	print (chr(47 + 45 * random.randint(0,1)), end=" ")
```

# Some GIFs

### Backward Forward Slashes

Classic, unfiltered

<p align="center">
  <img src="./gifs/maze.png" alt="Glitchy Terminal On Steroids" width="550"/>
</p>

### Morse code

With some over-the-top GIPHY filters

<p align="center">
	<img src="./gifs/morseCode.gif" alt="Glitchy Morse Code" width="550"/>
	<img src="./gifs/terminalOnSteroids.gif" alt="Glitchy Terminal On Steroids" width="550"/>
</p>
