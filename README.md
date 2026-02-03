# ditherGirl
A small python program that applies dithering algorithms in layers to an image. ditherGirl is inspired on ditherBoy and all creative acknowledgement should go to the developers of ditherBoy.

https://studioaaa.com/product/dither-boy/

<img width="1493" height="2100" alt="QueenPriestess" src="https://github.com/user-attachments/assets/1f9f200b-2bbb-4f9f-b924-64e08138d97e" />



---

## Quick Start

```bash
# Required
pip install pillow numpy
python ditherGirl.py
```

---

## What's Inside

| File | Role |
|---|---|
| `ditherGirl.py` | The main python script |
| `ditherGirl.app` | MACOS executable |


---

## How to Use

🎨 Layer System:

Add unlimited layers with different dithering algorithms
Stack and blend layers with various blend modes (normal, multiply, screen, overlay, hard_light)
Adjust layer strength/opacity (0-100%) for subtle or intense effects
Reorder layers with up/down buttons to change the effect order
Enable/disable layers to experiment without deleting
Each layer has its own threshold setting

💀 Stencil Mode & Aggressive Features:

Stencil Mode checkbox - Extreme contrast crushing for bold, graphic looks
Enhanced sharpen (0-5x) for crisp, aggressive edges
Boosted contrast range (0.5-3.0) for dramatic tonal shifts
New algorithms:

Halftone Dots - Classic newsprint style with circular patterns
Cross Hatch - Angular, sketchy texture perfect for dark aesthetics



🔥 Blend Modes for Creative Control:

Multiply - Darken and intensify blacks
Screen - Lighten and create glow effects
Overlay - Boost contrast dramatically
Hard Light - Extreme contrast blending

How to Create Dark, Aggressive Images:

Load your image
Enable Stencil Mode for extreme contrast
Boost Contrast to 2.0-3.0 and Sharpen to 2-3
Add Layer 1: Floyd-Steinberg at 100% (base texture)
Add Layer 2: Cross Hatch with Multiply blend at 50-70% (adds aggression)
Add Layer 3: Halftone Dots with Overlay blend at 30% (adds depth)
Lower Brightness to 0.7-0.8 for darker mood
Adjust individual layer thresholds to control detail
