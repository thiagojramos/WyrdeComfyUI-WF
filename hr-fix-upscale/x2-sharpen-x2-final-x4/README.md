# wyrde HR-Fix model upscaling x2 x2 (x4 final)

Includes WAS nodes. https://github.com/WASasquatch/was-node-suite-comfyui

Takes an image from text prompt (or image) and
* samples it
* uses an upscale model to double the size
* hi-rez fixes the image through a sampler
* uses a 4x upscale model to increase the size again
* saves it at a total of x4 size

Includes a couple lora. There's also a coupple places where moving noodles changes the generation.