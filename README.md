# ELECH473

## SIMD Tips and tricks

- [SIMD list of instructions]{https://www.felixcloutier.com/x86/}
- Image conversion of raw image to other format using ImageMagick `convert -size 1024x1024 -depth 8 gray:in.raw out.bmp`
- [Website to visualize raw images]{http://rawpixels.net/}
- Code snippet substracting 42 from a vector:
```C
unsigned char* foo = malloc(sizeof(unsigned char) * 16);
memset(foo, 42, 16);
__asm__(
    /* somehow put foo inside xmm3 and your output in xmm2 */
    "psubb %%xmm3, %%xmm2\n"
    /* outputs, inputs, clobbers*/
);
```
- Multithreading in C using pthread: [gist]{https://gist.github.com/parastuffs/a7818b1ff46de40b95949943fbd53c8b}
