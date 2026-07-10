# Definition
- The ability of the eyes and brain to automatically adjust to different light sources to perceive colors consistently
- Central to achieve color constancy
- This is why objects retain hues regardless of different ambient lighting conditions

# How it Works
## Photoreceptor Gain Control (The von kries Coefficient Rule)
- The retina contains three types of cone cells (L, M, and S-cones)
	- When exposed to a specific color cast (e.g., yellowish light), the cones most stimulated by that color adjust their sensitivity *("gain")* downward.
	- The brain independently scales the signals from the L, M, and S cones to rebalance the overall color spectrum and establish a new **white point**
## Neural Adaptation
- While the initial adjustment begins in the retina, the brain's visual pathways and visual cortex process this info further to suppress uniform color casts globally
- This higher-level processing helps the visual system quickly adapt and recognize contrasts

## Adaptation Speed
- For the cone desensitization, this happens within a fraction of a second
- Full chromatic adaptation to the brain can take several minutes

## Importance to Multimedia Artists and Designers
### Cross-Platform Consistency
- A design created on one monitor under warm office lighting will look completely different to someone viewing the design on their phone outdoors
- Monitor calibration and neutral lighting environments is key
	- This ensures that colors are predictable and accurate across different screens and print media
### Designing for eXtended Reality (AR/VR)
- A huge white screen in a dark room strains the eyes because pupils and photoreceptors have adapted to the dark ambient environment
- Designers, when the technology permits so (e.g., Virtual/Augmented Reality) could adjust contrast ratios and color warmth based on the user's ambient environment 
### Managing The "Simultaneous Contrast" Illusion
- The human eye adapts to the dominant colors on the screen itself
- Graphic designers should choose background and foreground colors that account for this localized adaptation
	- For example, a neutral gray next to a vibrant blue will make the gray look artificially warm (yellow-ish)
### Accurate Color Management (Color Math)
- When an asset moves between an illustration software, a video editing timeline, and a 3D renderer, each program interprets color coordinates differently.
	- As the human eye adapts to changes in color (chromatic adaptation), this is can be a semi-invisible problem that we can let the software itself fix
	- The Bradford Transform is used in color management software to simulate how human eyes adapt to different lighting sources
		- This is used in everything from monitors to cameras and printers to ensure color consistency across different devices and platforms

### Print and Packaging Design (CMYK)
- Designing for print and packaging media isn't 1:1 as screens use the RGB format, while print media uses CMYK. The same colors that show from a screen will not be the same colors seen under ambient lighting on print
	- Designers should test their designs under simulated proofing ("*soft proofing*" in Affinity/Photoshop), or if available, using the PANTONE system to ensure color consistency everywhere (though, this is VERY expensive). 
- This ensures the product design maintains it's exact brand colors physically