[Shader Fast Libs]
Shader libraries for fast shader opetations.
Optimized for AMD GCN architecture. Should also be beneficial on all other architectures (to certain degree).

[Usage]
Include a lib *.h shader file in your .hlsl or PC (C, CPP) code.
PC requires #define _PC
Available libs:
>ShaderFastMath.h 
  Contains fast approximations for basic transcendental functions.
  Newton Raphson methods provided for reference purpose (some code / architectures might still benefit from single NR).

[Info]
Presented initially as part of:
Low Level Optimizations for AMD GCN - presented @Digital Dragons 2014
published : http://michaldrobot.com/publications/

[Authors]
Michal Drobot
hello@drobot.org
michaldrobot.com
@MichalDrobot
