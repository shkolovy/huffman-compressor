# Implementation of archivator using Huffman coding

### How to use

```python
compress("compress-me.txt", "compressed.bin")

decompress("compressed.bin", "decompressed.txt")
```

>frequencies: Counter({' ': 1403, 'e': 807, 't': 547, 'h': 508, 'a': 494, 'o': ...

>encoded huffman tree code: 0010010000001011001010001011100001001011000101100011...

>encoded text code: 000000001111011011010010001111010011101101111110111001110100...

>before: 7528bytes, after: 4109bytes, compression 45.4%