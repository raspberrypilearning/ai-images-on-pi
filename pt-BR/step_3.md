## Execute o script

--- task ---

Digite o seguinte comando no terminal e pressione <kbd>Enter</kbd> para executar o script:

```bash
./run_sd.sh
```

--- /task ---

--- task ---

Você será solicitado a digitar um prompt. Esta é uma descrição da imagem que você deseja gerar. O prompt orienta o processo de geração de imagem descrevendo a cena ou objeto desejado. Se você quiser saber mais sobre como criar prompts para um gerador de imagens de IA, [dê uma olhada no projeto aqui](https://projects.raspberrypi.org/pt-BR/projects/ai-image-prompt/){:target="_blank"}.

```bash
Enter the prompt: Um gato
```

Pressione <kbd>Enter</kbd>.

--- /task ---

--- task ---

Em seguida, digite o número de etapas. Isto afeta a qualidade da imagem. Mais etapas geralmente resultam em imagens de maior qualidade, pois o modelo tem mais oportunidades de refinar a saída. Leva cerca de 1 minuto por etapa em um Raspberry Pi 5 com 4 GB de RAM.

```bash
Enter the number of steps: 5
```

Pressione <kbd>Enter</kbd>.

--- /task ---

--- task ---

Digite o nome do arquivo de imagem. Este é o nome com o qual a imagem gerada será salva.

```bash
Enter the output image file name: cat.png
```

Pressione <kbd>Enter</kbd>.

--- /task ---

--- task ---

Aguarde a geração da imagem.

O script agora será executado com suas entradas para gerar a imagem. Isso pode levar alguns minutos, dependendo do número de etapas e do desempenho do seu computador.

--- /task ---

--- task ---

Verifique a saída.

Quando o processo estiver concluído, a imagem gerada será salva no diretório atual com o nome de arquivo especificado.

![Um gatinho laranja e branco com olhos grandes e expressivos e com um nariz rosa está sentado numa superfície de madeira. O gatinho tem um laço rosa no pescoço. Ao fundo, há raminhos de lavanda e um maço de flores de lavanda embrulhado em estopa, contra um fundo rosa suave.](images/cat.jpg)

--- /task ---

Seguindo estes passos, você pode facilmente gerar imagens usando o script. O prompt define o que a imagem representará, o número de etapas influencia sua qualidade e o nome determina como o arquivo será chamado quando salvo.

Divirta-se criando suas imagens!
