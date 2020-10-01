# gyro-Max-externals

![](gyro_logo.jpg)

pre-built Max externals for gyro: A MaxMSP wrapper for Google Resonance. 

`gyro` is based on the `min-devkit`, which can be found [here](https://github.com/Cycling74/min-devkit). If you are interested in the code behind `gyro`, you can view the source code and builds the externals yourself in the [gyro repository](https://github.com/sncheca/gyro). 

`gyro` is powered by [Google Resonance](https://resonance-audio.github.io/resonance-audio/), which is Google's open source ambisonics and spatial audio project. Resonance is available in many forms already, such as Unity, FMOD, DAW Plugin, etc, but for some reason, there wasn't a Max version, which is why I made `gyro`. `Gyro` uses the C++ source code that can be found [here](https://github.com/resonance-audio/resonance-audio). 

## Using these patches
In order for Max to find the patches, they must be in the `Max 8/Packages` folder.
I prefer to just create an alias to the `gyro` repo and move this alias into the `Max 8/Packages` folder. You can create an alias by right clicking on the directory in finder and clicking "Make Alias". 

Alternatively, you can add a search path to the `gyro-Max-Externals/` directory by going to `Options >> File Preferences` within Max. 

### Installing Max
Max can be installed from [here](https://cycling74.com/downloads). It comes with a 30 day free trial period. If you are a student, you can probably get a subscription through your university. There are also free licenses available for AES ([Audio Engineering Society](https://www.aes.org/)) members. 

## Attributions
This work was jointly funded by the [Yale Center for Collaborative Arts and Media](https://ccam.yale.edu/), the [Yale Department of Music](https://yalemusic.yale.edu/), and [Yale Blended Reality](https://blendedreality.yale.edu/). Special thanks to Professor Konrad Kaczmarek.  
All `min-devkit`, `min-api`, and `min-lib` code is the property of Cycling74. All `resonance_audio` code is the property of Google. All other code is the property of Sofia Checa, but may be used freely for any purpose, provided that Cycling74, Google, and Sofia are properly attributed. 

## Help
Please feel free to reach out here on Github with bugs, issues, questions, or anything else. Nothing is too small!
