# How to make your game look bad
## HEAVY WIP, just jotted some ideas down
All sections are listed from least involved to most involved (with diminishing returns)

Guide is focused around Windows and Nvidia

DO NOT RUN RANDOM RANDOM SCRIPTS TO “OPTIMIZE” YOUR PC

I recommend reading through the guide first, and then choosing what you want to do afterwards. 

[In Game Settings](#in-game-settings)

[Windows](#windows)

[Config](#config)

[Mods](#mods)

[GPU Settings](#nvidia-gpu-settings)

[BIOS](#bios)

[Down the Rabbit Hole](#down-the-rabbit-hole)

[Mental Illness](#mental-illness)


## In Game Settings:
Window: Full Screen (You can use Borderless Window if you care about Alt Tabbing)

Upscaling Technology: Stretch

> Don’t be scared of Upscaling if your GPU can support it! I’ve had great results with DLSS+Transformer

Anti-Aliasing: Off

Screen Space AO: Off

Distance Field Shadows: Off

Shadow Quality: Low

Fog Quality: Low

Texture Quality: Low

Post Process Bloom: Off

Effects Bloom: Off

VSync: Off

Area Lights: Off

Depth of Field: Off

In game FPS: Max

Rendering: DX11

Nvidia Reflex: On


## Config
[OptimizationLock](https://github.com/Sqooky/OptimizationLock) has several options, but also contains a lot of commands that are no longer supported in engine.

[My config](https://github.com/thesmellofwindex/deadlock-optimization-guide/blob/main/config/gameinfo.gi)
> File location: **Deadlock Install Location** \ game\ citadel \ gameinfo.gi
>
> Bound to be outdated soon because of how often the game is updated, I'll try and stay up to date 

[video.txt](https://github.com/thesmellofwindex/deadlock-optimization-guide/blob/main/config/video.txt)
> File Location: **Steam Install Location** \userdata\ **Your User ID** \ 1422450 \ local \ cfg
> You need to change some values that are specific to your computer!
> 
> Copy and paste these values from your current video.txt: Version, VendorID, DeviceID.
> 
> Set as Read Only

## Mods
> Make a folder in: **Deadlock Install Location** \ game\ citadel \ called Addons
> Naming structure is as follows: pakXX_dir.pak
> 01-99 is priority based

[Blur Disabler](https://github.com/Sqooky/OptimizationLock/tree/main/Performance%20Improving%20Mods/Blur%20Disabler)
  
[Optimized Soul Container (Broken ATM?)](https://github.com/Sqooky/OptimizationLock/tree/main/Performance%20Improving%20Mods/Optimized%20Soul%20Container)
  
[Sinner Light Fix mod (if mip bias >4)](https://github.com/Sqooky/OptimizationLock/tree/main/Performance%20Improving%20Mods/Sinner%20Light%20Fix%20Mod)
  
[Vindicta Scope Downscale](https://github.com/Sqooky/OptimizationLock/tree/main/Performance%20Improving%20Mods/Vindicta%20Scope%20Downscale)

[Clutter Be Gone](https://github.com/Sqooky/OptimizationLock/tree/main/Performance%20Improving%20Mods/Clutter%20be%20Gone)

[Potato Lock Hero Texture (Breaks Lighting)](https://gamebanana.com/mods/692484)

[LOD Pack](https://github.com/thesmellofwindex/deadlock-lod) (My mod pack, currently a WIP)

## Windows
Update Drivers (GPU, CPU Chipset)

Ensure Game Mode, HAGS, Resizable Bar, and Windowed Optimizations (if you use Borderless Window) are enabled

Disable Overlays (Steam, Discord, Etc)

Close Unused Programs (Web Browser, Discord, Etc.)

Disable unneeded background process (Third party apps like game launchers)/disable start up programs

Debloat Windows (Make a restore point!) Chris Titus Tool and ShutUp10


## Nvidia GPU Settings
Set monitor to highest refresh rate, enable G-Sync if supported

Power Management Mode: Prefer Maximum Performance

Low Latency Mode: Software Controlled

Texture Filtering - Quality: High Performance

Texture Filtering - Trilinear Optimization: Yes

Texture Filtering - Anisotropic Optimization: Yes

Vertical Sync: Off/Software Controlled

## BIOS
Update BIOS if not on latest version already

Ensure XMP and Resizable Bar (If supported) are enabled

## Overclocking
Can be pretty intimidating, I’ll link a guide as it’s an involved process and not one size fits all

## Down the Rabbit Hole
Reinstall Windows, I personally use Enterprise as it comes relatively lightweight

Nvidia Clean Install

Disable Unnecessary Windows Services

CPU / GPU Affinity

Disable various system features (Bluetooth, Wi-Fi if on Ethernet)


## Mental Illness

[https://github.com/BoringBoredom/PC-Optimization-Hub](https://github.com/BoringBoredom/PC-Optimization-Hub)

There’s obviously a never ending list of changes you can do, this is just a rough guide
