## Loupe Design System

Welcome to Loupe 2019, a conference on interactive design and creative coding.

Here at Framer, we aim to fully bridge the gap between designers and developers, through collaboration and shared design systems. This is what we'll be doing today!

### Overview

We'll be splitting up into smaller teams, with at least one developer and one designer. Our goal is to create a shared design system with components built ready for Framer X and Production. Through this, we'll gain a deeper understanding of what the collaboration aspect looks like in Framer X.

### Prerequisites

We have a few pre-requisites you'll need in order to follow along.

- node.js
- git
- Text/Code Editor
- Framer X

### Instructions

We'll be using styled-components to make designing and coding our components more streamlined. This also allows us to integrate more fully with Framer X, if we use variables from Framer inside of our code.

#### Using Colors Example:

```
import { theme } from "../theme";

const StyledElement = styled.div`
    color: ${theme.color.primary};
`
```

There are a total of 8 colors from the Loupe Design System:

`primary` - <span style="background:#0055FF; color: white">#0055FF</span>

`secondary` - <span style="background:#98E7FF; color: black">#98E7FF</span>

`accentLight` - <span style="background:#E7FFF7; color: black">#E7FFF7</span>

`accentDark` - <span style="background:#FFC6A8; color: black">#FFC6A8</span>

`black` - <span style="background:#000000; color: white">#000000</span>

`grey` - <span style="background:#8A8A8A; color: white">#8A8A8A</span>

`lightGrey` - <span style="background:#FAFAFA; color: black">#FAFAFA</span>

`white` - <span style="background:#FFFFFF; color: black">#FFFFFF</span>

#### Using Spacing Example:

#### Using Fonts Example:

### Components

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
