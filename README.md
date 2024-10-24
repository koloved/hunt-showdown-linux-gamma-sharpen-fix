# Hunt Showdown Linux Gamma Sharpen Fix

This project provides a gamma sharpening fix for *Hunt: Showdown* on Linux using VKBasalt. 

## Prerequisites

Before you begin, ensure that you have **VKBasalt** installed on your system. If you're using Bazzite, it comes pre-installed.

## Steam Launch Command

To launch the game with the necessary settings, use the following command in Steam:

`VKD3D_FEATURE_LEVEL=12_2 gamemoderun mangohud ENABLE_VKBASALT=1 DXVK_FRAME_RATE=165 %command%`

> *The `VKD3D_FEATURE_LEVEL=12_2` setting is primarily intended for me (Nvidia 30 GPU). Users with different graphics hardware may need to adjust this setting for optimal performance.*

## Setup Instructions

1. **Copy Configuration File**  
   Place the `vkBasalt.conf` file into your *Hunt: Showdown* Steam folder.

2. **Download Shader**  
   Place the `Tonemap.fx` shader and place it in the following directory:  
   `/home/YOUR_USER/.config/vkBasalt/reshade/Shaders/Tonemap.fx`

3. **Edit Configuration**  
   Open the `vkBasalt.conf` file and replace `YOUR_USER` in the path with your actual username.

## Usage

- Launch *Hunt: Showdown*.
- Use the **HOME** key to enable or disable the gamma and sharpening effect.

## Troubleshooting

If you encounter any issues, ensure that:
- VKBasalt is correctly installed and configured.
- The paths in `vkBasalt.conf` are accurate.
