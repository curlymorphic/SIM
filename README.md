# SIM

## Coerce
![Coerce](https://github.com/imDanSable/SIM/blob/master/coerce.png)

**Coerce** Consists of six independant quantizers. One on each row. Unlike traditional quantizers where inputs are quantized to scales, Coerce uses the input values of the polyphonic quantize input (the middle column) as quantize values. This could be a scale taken from the output of [ScaleCV](https://library.vcvrack.com/AaronStatic/ScaleCV) by Aaron Static, but it could also be a mix of LFOs or VCOs to manipulate an audio signal.

The quantization values are normalled down. So if you connect a polyphonic input with values of an E minor chord to the top most Quantize input and one with a A minor scale to the fourth quantize input you have 3 quantizers that quantize the inputs to the the E minor chord and 3 quantizers that quantize the the A minor scale.

There are two quantization modes that are accessible via the menu.
1) **Octave fold:**
This is the default mode and makes Coerce behave like a regular quantizer folding values around one Volt.
2) **Restrict:**
In this mode, all input voltages are quantized to quantize values.

There are three rounding methods that are also accessible via the menu.
**Up**, **Closest** and **Down**.
