# encof

Encoding finder, just a ugly hack trying to survive through encoding problems =/

Usage:

```sh
./encof <file>
```

The file contents are read as an array of bytes and the code
tries to decode using different encodings and shows you the
result of each decode process so you can manually inspect
if it makes sense.

Example:

```sh
./encof samples/unknown.txt
```
