# Welcome!

## I'll be showing you some easy optimization flags that can be applied to **any** Chromium browser (ie. Chrome, Chromium, Opera GX, etc.)

![Capture](https://github.com/TrueHerobrine/trues-chromium-optimizations/assets/69488295/b25aa66a-a025-4c48-98bf-2a8c603b1416)

# These are the main optimizations you will need.

## Here's an explaination, in order, of what they do:

  - Number of Raster threads
    
    Tells your browser how many cores/threads of your processor you want it to use to generate the look of the webpage

    Optimal setting: 4
 
  - Experimental QUIC protocol

    Optimal setting: Enabled
    
    A new type of encryption to connect to sites that prioritizes speed and security, of course.
 
  - WebAssembly baseline compiler

    Optimal setting: Disabled
    
    I'm too lazy to explain this one, if you want an explanation, I'll link one [here](https://v8.dev/docs/wasm-compilation-pipeline) 🤣🤣
  
  - WebAssembly tiering

    Optimal setting: Disabled
    
    See [this](https://v8.dev/docs/wasm-compilation-pipeline)

  - GPU rasterization

    Optimal setting: Enabled

    Tells your computer's GPU to render the website you're loading

    ### Note: I would **not** recommend enabling this one if you have an iGPU.

  - Not typing the name of this one lol

    Optimal setting: Enabled

    Tells your browser to use two render threads instead of one.

    ## That's it!

    ### Now, enjoy your newly optimized browser! So long!

  ## Please create an issue if I've made a mistake.
