# GrainFader

### A pair of buffer granulators that can be crossfaded and independently monitored

GrainFader wraps up 2 instances of BufGrainJ and index into soundfile buffers using a Phasor of variable speed and direction (< 0 >). You supply a file path of a folder containing soundfiles and they are all loaded for swapping on the fly. The two instances of BufGrainJ are summed into a mono feed via a power-panning crossfade. The feeds can be monitored individually via two monitor busses, indepent of the main output bus. Each grain stream can also be sent to an auxilliary bus.

### Installation

Open up SuperCollider and evaluate the following line of code:
`Quarks.install("https://github.com/mtmccrea/grainfader.quark")`
