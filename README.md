# Loupe Design System

Welcome to Loupe 2019, a conference on interactive design and creative coding.

Here at Framer, we aim to fully bridge the gap between designers and developers, through collaboration and shared design systems. This is what we'll be doing today!

## Overview

We'll be splitting up into smaller teams, with at least one developer and one designer. Our goal is to create a shared design system with components built ready for Framer X and Production. Through this, we'll gain a deeper understanding of what the collaboration aspect looks like in Framer X.

## Prerequisites

We have a few pre-requisites you'll need in order to follow along.

- node.js
- git
- Text/Code Editor
- Framer X

## Getting Started

We'll be using styled-components to make designing and coding our components more streamlined. This also allows us to integrate more fully with Framer X, if we use variables from Framer inside of our code.

1. [Fork this repository](https://help.github.com/en/articles/fork-a-repo).
1. [Clone the forked repository](https://help.github.com/en/articles/cloning-a-repository) locally
1. Run `yarn` to install dependencies

---

1. [Clone this repository](https://help.github.com/en/articles/cloning-a-repository) locally
1. `cd` into this directory and run `git checkout loupe-NewComponent -b` to create a new branch
1. Run `yarn` to install dependencies

#### Using Colors Example:

```
import { theme } from "../theme";

const StyledElement = styled.div`
    color: ${theme.color.primary};
`
```

There are a total of 8 colors from the Loupe Design System:

`primary` - ![#0055FF](https://placehold.it/15/0055FF/000000?text=+) <span style="background:#0055FF; color: white">#0055FF</span>

`secondary` - ![#98E7FF](https://placehold.it/15/98E7FF/000000?text=+) <span style="background:#98E7FF; color: black">#98E7FF</span>

`accentLight` - ![#E7FFF7](https://placehold.it/15/E7FFF7/000000?text=+) <span style="background:#E7FFF7; color: black">#E7FFF7</span>

`accentDark` - ![#FFC6A8](https://placehold.it/15/FFC6A8/000000?text=+) <span style="background:#FFC6A8; color: black">#FFC6A8</span>

`black` - ![#000000](https://placehold.it/15/000000/000000?text=+) <span style="background:#000000; color: white">#000000</span>

`grey` - ![#8A8A8A](https://placehold.it/15/8A8A8A/000000?text=+) <span style="background:#8A8A8A; color: white">#8A8A8A</span>

`lightGrey` - ![#FAFAFA](https://placehold.it/15/FAFAFA/000000?text=+) <span style="background:#FAFAFA; color: black">#FAFAFA</span>

`white` - ![#FFFFFF](https://placehold.it/15/FFFFFF/000000?text=+) <span style="background:#FFFFFF; color: black">#FFFFFF</span>

#### Using Spacing Example:

#### Using Fonts Example:

#### Components:

We have a list of components you can pick from to help build our design system:

- Button
- Link
- Card
- Banner
- Checkbox
- Radio Button
- Navigation
- Icon
- Chip
- List
- Input
- Select
- Segment
- Loader
- Slider
- Stepper
