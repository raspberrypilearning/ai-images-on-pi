## Run the script

\--- task ---

Type the following command into the terminal and press <kbd>Enter</kbd> to run the script:

```bash
./run_sd.sh
```

\--- /task ---

\--- task ---

You will be asked to enter a prompt. This is a description of the image you want to generate. The prompt guides the image generation process by describing the desired scene or object. If you want to know more about prompting an AI image generator, [have a look at the project here](https://projects.raspberrypi.org/en/projects/ai-image-prompt/){:target="_blank"}.

```bash
Enter the prompt: A cat
```

Appuie sur <kbd>Entrée</kbd>.

\--- /task ---

\--- task ---

Next, enter the number of steps. This affects the quality of the image. More steps generally result in higher quality images as the model has more opportunities to refine the output. It takes around 1 minute per step on a Raspberry Pi 5 with 4GB RAM.

```bash
Enter the number of steps: 5
```

Appuie sur <kbd>Entrée</kbd>.

\--- /task ---

\--- task ---

Enter the name of the image file. This is the name your generated image will be saved as.

```bash
Enter the output image file name: cat.png
```

Appuie sur <kbd>Entrée</kbd>.

\--- /task ---

\--- task ---

Wait for the image to be generated.

The script will now run with your inputs to generate the image. This may take a few minutes depending on the number of steps and your computer’s performance.

\--- /task ---

\--- task ---

Check the output.

Once the process is complete, your generated image will be saved in the current directory with the specified file name.

![An orange and white kitten with large, expressive eyes and a pink nose sits on a wooden surface. The kitten has a pink bow around its neck. In the background, there are sprigs of lavender and a burlap-wrapped bundle of lavender flowers, against a soft pink backdrop.](images/cat.jpg)

\--- /task ---

By following these steps, you can easily generate images using the script. The prompt defines what the image will depict, the number of steps influences its quality, and the name determines what the file will be called when saved.

Enjoy creating your images!
