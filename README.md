# go-palette2048_greer

Package **palette2048_greer** provides the Greer 1-bit color palette in the form of 256 RGBA color with 8-bits per color channel,
that when used with the https://github.com/reiver/go-palette2048 package works with Go's built-in `"image"`, `"image/color"`, and `"image/draw"` packages.

## Documention

Online documentation, which includes examples, can be found at: https://github.com/reiver/go-palette2048_greer

[![GoDoc](https://godoc.org/github.com/reiver/go-palette2048_greer?status.svg)](https://godoc.org/github.com/reiver/go-palette2048_greer)

## Example

```go
import (
	"github.com/reiver/go-palette2048"
	"github.com/reiver/go-palette2048_greer"
)

// ...

palette := palette2048.Slice(palette2048_greer.Palette)

// ...

// Get the color at a specific index in the palette.
color := palette.Color(index)

// ...

// Get the color in the palette that is closet to a reference color.
closestColor := palette.Convert(referenceColor)
```

## See Also

Also see:

* https://github.com/reiver/go-palette2048

## Greer

To learn more about the the _Greer 1-bit color palette_ refer to: https://youtu.be/0BZwEoj50uw

