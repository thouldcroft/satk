# The Sound Art Toolkit (SATK)
## Introduction
The Sound Art Toolkit is a collection of high-level Pure Data modules (abstractions) that provide access to common sound generating processes. These tools (attempt) to not lean towards any one specific sound art pratice - in other words, the tools aren't specifically made for, say, making music, but that is not to say that they cannot be used to make music. <br>

These modules primarily were developed to introduce non-coders to developing sound works using patching environments. Within the set of modules include tools for audio file playback, synthetic tone generation, control over sound generation, and tools closer to those one would implement in a patching-coding environment, like number generation, number distribution, data arrays, and basic math objects.<br>

## Requirements
This library uses code from the following libraries which may need to be installed via Deken (Pd Vanilla: Help > Find Externals, PlugData: Find Externals):<br>
- tdh.lib (by this author, <https://github.com/thouldcroft/tdh.lib/>)
- Else (already installed in PlugData, <https://github.com/porres/pd-else/>)
- Cyclone (aleady installed in PlugData, <https://github.com/porres/pd-cyclone/>)

## Overview
Modules in the SATK follow the following conventions:<br>
- Modules that end with a '~' output audio signals or data at signal rate
- Modules without a '~' output data at control rate (slower)
- Modules use the following naming convention:
  - satk.category.name
- Module categories:
  - Algorithmic Composition (ac.---): Abstractions for the algorithmic generation of sonic composition, musical or otherwise.
  - Control (ctrl.---): slider and a button to trigger or control sound generation.
  - Math (math.---): basic arithmetic, number manipulation, number generation, value conversion.
  - Sequence (seq.---): Modules for sequencing events in time.
  - Signal Processors (sigproc.---): modules that process or change incoming signals that send them back out.
  - Synthesis Modules (synth.---): Synthetic sound generation. Many draw on modular synthesis design foundations.
  - Utilities: More or less, everything else. This includes:
    - Panning and mixing tools
    - Envelope/ramp tools
    - Audio-file playback
    - Audio I/O
    - Audio recording
    - Audio graphic displays
    - Patching tools
    - Clock tools
    - Arrays and data tables
    - Remote send modules to send data without (virtual) wires

## License
Copyright (C) 2024 Travis Houldcroft<br>
thouldcroft@gmail.com <br>
<https://travishouldcroft.com/> <br>

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.<br>

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details. <br>

You should have received a copy of the GNU General Public License along with this program.  If not, see <https://www.gnu.org/licenses/>.
