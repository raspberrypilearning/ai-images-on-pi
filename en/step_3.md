## Generate an Image with SDXL Turbo

### Using the Script

--- task ---

Type the following command into the terminal and press `Enter` to run the script:

```bash
./run_sd.sh
```

--- /task ---

--- task ---

You will be asked to enter a prompt. This is a description of the image you want to generate. The prompt guides the image generation process by describing the desired scene or object. If you want to know more about prompting an Iimage generator, [have a look at the project here](https://projects.raspberrypi.org/en/projects/ai-image-prompt/){:target="_blank"}. 


```bash
Enter the prompt: A beautiful sunset over the mountains
```

Press Enter.

--- /task ---

--- task ---

Next, enter the number of steps. This affects the quality of the image. More steps generally result in higher quality images, as the model has more opportunities to refine the output. It takes around 1 minute per step on a Raspberry Pi 5.

```bash
Enter the number of steps: 5
```

Press Enter.

--- /task ---

--- task ---

Enter the name of the image file. This is the name your generated image will be saved as.

```bash
Enter the output image file name: sunset_image.png
```

Press Enter.

--- /task ---

--- task ---

Finally, enter a seed number. This makes the image generation process reproducible. The seed number ensures that the same prompt and settings will produce the same image every time, which is useful for consistency. 

```bash
Enter the seed number for your image: 1426396
```
--- collapse ---
---
title: Maximum seed number
---

Add any seed number from 0 up to *around* 2 billion (2,000,000,000) - a higher seed than this will likely result in an error.

--- /collapse ---

Press Enter.

--- /task ---

--- task ---

Wait for the Image to Generate

The script will now run with your inputs and generate the image. This may take a few moments depending on the number of steps and your computer’s performance.

--- /task ---

--- task ---

Check the Output

Once the process is complete, you will find your generated image saved in the specified file name in the current directory.

--- /task ---

By following these steps, you can easily generate images using the script. The prompt defines what the image will depict, the number of steps influences its quality, the file name determines where it will be saved, and the seed ensures reproducibility. Enjoy creating your images!
