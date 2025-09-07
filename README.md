# Mixamo Root (Forked)

This repository is **forked from [finepointcgi/Mixamo-Root](https://github.com/finepointcgi/Mixamo-Root)**.  

## Reason for Fork
The original addon had a mismatch between **Blender’s default FBX import frame offset (1.0)** and the **root motion application starting at frame 0**.  

- This caused issues with **looping root motion animations**.  
- While animations looked correct during normal playback, they showed a slight **stutter at loop boundaries**.  

## Changes
- Fixed frame handling so that root motion aligns correctly with Blender’s FBX import behavior.  

## Maintenance
This fork is **not actively maintained**:  
- No plans for additional features or bug fixes.  
- Purpose is purely to fix the frame offset issue for personal use and for others who may need it.  
