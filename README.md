# The VCR Font Family

![screenshot](screenshot.png)

## Overview

VCR is monospaced bitmap font inspired by the overlay text used in
many video cassette recorders of the 1980s and 1990s.

The design is a two-color font of white text outlined in black.
Seeing as the BDF font format does not support multiple colors, the
white and black portions have been split into two separate font files.
The white inline portions of each character are in
`vcr-normal-inline.bdf` and the black outline portions are in
`vcr-normal-outline.bdf`.

The inline and outline fonts are meant to be overlaid in contrasting
colors in a similar manner to what you see in the example screenshot.

## Installation

1. Copy or symlink the fonts to your ~/.fonts directory:
   `cp vcr-normal-*.bdf ~/.fonts`
2. Run `fc-cache -fv` to update your font cache.
