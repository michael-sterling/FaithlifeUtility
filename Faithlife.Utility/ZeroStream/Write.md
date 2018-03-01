# ZeroStream.Write method

Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written.

```csharp
public override void Write(byte[] buffer, int offset, int count)
```

| parameter | description |
| --- | --- |
| buffer | The source array. |
| offset | The zero-based byte offset in the buffer. |
| count | The number of bytes to be written to the current stream. |

## Remarks

The bytes are not actually stored and will be read as zeroes.

## See Also

* class [ZeroStream](../ZeroStream.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->