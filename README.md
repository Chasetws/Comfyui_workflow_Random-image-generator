The workflow is used to conduct automatically, and randomly change the prompts and Lora.
What should you do is to download the workflow and txt files that you can put prompts there.
The path of txt files is .../ComfyUI/custom_nodes/comfyui-dynamicprompts/wildcards/

Dont change the content of binary.txt, random.txt randomint.txt and randomint2.txt
About other txt files, the content need to be as follow:

all.txt --- Put all  prompts which  will not conflict with the characters themselves here, like actions, expressions, decorations... you can add another simple character here like 1boy.
You can also add the lora's name (or path) here, like LoRAKissyFaceNoobAIXLvPred.safetensors, and the workflow will detect it and automatically generate relevant prompts.

loracharacter.txt and clothes.txt --- Put the character and clothes lora name or path there. In loracharacter.txt, maybe you can directly put prompts, but I have not tried before.

In such node like it
![屏幕截图 2025-03-26 230619](https://github.com/user-attachments/assets/74c30f94-573c-4ffc-96d3-65ed8b591014)
Input any lora in it, there is no function to the image, just to conduct with no error.
