# Scientist

A 4x12 ergonomic columnar stagger keyboard PCB for tray mount 60% cases.

The design is heavily influenced by fantastic projects like Lumberjack, Discipline, Corne/Cornelius, Rebound, Reviung and many more, incorporating many of the ideas in one place (along with a couple of my own). I've been tweaking and refining this layout over several iterations both to optimise ergonomics as well as make sure it everything fits in a tray mount case. It's at the point where I've been confidently using it as my primary keyboard for several months and am excited for others to try it out!

## Features

 * Ergonomic columnar stagger
 * Support for many (most?) tray mount 60% cases
 * Aggressive stagger for optimal pinky comfort
 * Corne/Reviung-like thumb key cluster
 * MX Hotswap sockets
 * Knob positions allows for actuation with thumbs without the fingers leaving the home row
 * Mostly through-hole construction for easy DIY construction (see below)
 * Optional RGB Underglow
 * Optional support for up to 3 encoders (up to one each side and one in the centre)
 * Optional support for OLED instead of an encoder in the central position

## Layouts

The PCB layout supports two distinct plates. A universal layout that gives you the most flexibility:

![pics/layout-universal.png]

For those who are sure they want to use encoders on each side, there's a dedicated layout that moves the encoders into a better position to allow for the use of larger knobs (this is the variant you can see in most of my pictures):

![pics/layout-knobs.png]

Just a quick word about the encoder positioning; I've had lots of questions about whether they get in the way of typing. I use my thumbs for the inner 6/7 keys on the bottom row, and my pinky for the outer two - this means the knob stays under my palm out of the way, and crucially the knobs can be actuated with my thumbs *without my fingers leaving the home row* (or with thumb and ring finger, while keeping my index finger on the home keys). This has been *huge* for me as it means I've been able to include their functions in my day to day typing without feeling like they're slowing me down. I highly recommend giving it a try.

## Building

The majority of the components are through-hole and so very easy for the beginner to solder with no special tools. The hotswap sockets *are* surface mount components, but they're very easy to hand solder even for a beginner. Underglow LEDs are a bit more difficult but still possible for most beginners.

The USB socket is the area most beginners are likely to have problems, it's not hard to solder but does require a bit of care. The job is made *much* easier if you use lots of flux, ideally flux paste, so that's strongly recommended.

A build guide will be provided.

### Kit includes

 * PCB
 * Plate
 * 46-50 Hotswap sockets (depending on configuration)
 * Acrylic cover and mounting hardware
 * ATMega32A flashed with the necessary bootloader

### Optional

 * 16x underglow LEDs
 * 128x32 OLED
 * 4x1 OLED socket
 * Encoders and Knobs   

## Case support

The PCB should supports most 60% cases with Poker style tray mount points. It's been tested with Tofu60, Mekanisk Klippe T and Fjell cases and various generic 60% cases. It does *not* support cases with very thick (>5mm) mounting posts in the two central mount point locations and may require kapton tape insulation (or o-ring mod) for some cases with >4mm mounting posts to prevent shorts. Does not support BBox60 cases without modification due to the many extra mount points present.
