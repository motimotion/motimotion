I would like you to evaluate the quality of {num_targets} generated videos based on the following criteria: physical realism, photorealism, and semantic consistency. Given the original image (the first frame of the videos) and the text prompt: '{prompt}', please evaluate the quality of each video on the three criteria mentioned above.

Note that: 
- Physical Realism measures how realistically the video follows the physical rules and whether the video represents real physical properties like elasticity and friction. To discourage completely stable video generation, we instruct respondents to penalize such cases. 
- Photorealism assesses the overall visual quality of the video, including the presence of visual artifacts, discontinuities, and how accurately the video replicates details of light, shadow, texture, and materials. 
- Semantic Consistency evaluates how well the content of the generated video aligns with the intended meaning of the text prompt.

Please provide the evaluation for each video according to the following format, scores should be ranging from 0-1, with 1 to be the best:
Video:
    Physical Realism Score: [a score]
    Photorealism Score: [a score]
    Semantic Consistency Score: [a score]