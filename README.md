The workflow is used to conduct automatically, and randomly change the prompts and Lora.
What should you do is to download the workflow and txt files that you can put prompts there.
The path of txt files is .../ComfyUI/custom_nodes/comfyui-dynamicprompts/wildcards/

Dont change the content of binary.txt, random.txt randomint.txt and randomint2.txt
About other txt files, the content need to be as follow:

all.txt --- Put all  prompts which  will not conflict with the characters themselves here, like actions, expressions, decorations... you can add another simple character here like 1boy.
You can also add the lora's name (or path) here, like LoRAKissyFaceNoobAIXLvPred.safetensors, and the workflow will detect it and automatically generate relevant prompts.

loracharacter.txt and clothes.txt --- Put the character and clothes lora name or path there. In loracharacter.txt, maybe you can directly put prompts, but I have not tried before.

On the setting, there is certain probability to add clothes lora in the image, so if there is no info about clothes lora, please try more times.

Now, you can use slider lora in random weight in the workflow, and I add a bit diversity in action group, to make sure some loras can be triggered. (But it increases the probability of image collapse a bit)

In such nodes like it, you shoule input any lora's name or path in, and there is no function to the image, just to conduct with no error.

![屏幕截图 2025-03-26 230619](https://github.com/user-attachments/assets/74c30f94-573c-4ffc-96d3-65ed8b591014)

The workflow unsupport multi-character loras. And if the pormpts given by authors in werid format, may lead to image collapse, although I have tried to avoid the condition.

