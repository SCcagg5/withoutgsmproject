# without gsm
Algorithm for compressing digital values for SigFox frames of 12 bytes.  
Allows as well to sacrifice unit value for it to be coded on 2/4/8 values instead of 10. 

Use [twelve_bytes_compression.cpp](./twelve_bytes_compression.cpp) on the embedded software side of your SigFox project.  
Then, use one of the librairies in `/decompress` to decompress the frame on the server side.

## Run example

Just run the following command :

```
g++ main.cpp twelve_bytes_compression.cpp && ./a.out
```

:heavy_check_mark: = verified  
:white_circle: = should operate  
:x: = not compatible
