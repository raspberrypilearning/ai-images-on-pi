## Executa o script

\--- task ---

Introduz o seguinte comando no terminal e pressiona <kbd>Enter</kbd> para executar o script:

```bash
./run_sd.sh
```

\--- /task ---

\--- task ---

Vai ser-te pedido para escreveres um prompt. Esta é uma descrição da imagem que pretendes gerar. O prompt guia o processo de gerar as imagens ao descrever a cena ou o objeto pretendido. Se quiseres saber mais sobre como escrever uma prompt num gerador de imagens de IA, [dê uma vista de olhos ao projeto aqui](https://projects.raspberrypi.org/en/projects/ai-image-prompt/){:target="_blank"}.

```bash
Escreve o prompt: Um gato
```

Pressiona <kbd>Enter</kbd>.

\--- /task ---

\--- task ---

Em seguida, introduz o número de passos. Isto afeta a qualidade da imagem. More steps generally result in higher quality images as the model has more opportunities to refine the output. It takes around 1 minute per step on a Raspberry Pi 5 with 4GB RAM.

```bash
Enter the number of steps: 5
```

Pressiona <kbd>Enter</kbd>.

\--- /task ---

\--- task ---

Enter the name of the image file. This is the name your generated image will be saved as.

```bash
Enter the output image file name: cat.png
```

Pressiona <kbd>Enter</kbd>.

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
