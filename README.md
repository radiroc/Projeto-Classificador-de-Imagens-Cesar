# Projeto-Classificador-de-Imagens-Cesar

## Primeira Etapa - Geração do Dataset
Efetue o download ou extraia do repositório o notebook "CriandoDataset.ipynb" para executa-lo no Google Colab ou no Jupyter (como preferir).

Após a execução de todas as etapas do notebook de criação do dataset, um arquivo com o nome "Humans.zip" será gerado na pasta "/content".
Clique no arquivo e realize o download do mesmo. 

## Segunda Etapa - Tratamento do arquivo comprimido
Após a conclusão do download do arquivo, extraia os dados da pasta .zip para a sua máquina, copie a pasta 'Humans" extraída e cole no endereço "C:\Users\".
Acesse o github via cmd e clone o repositório https://github.com/radiroc/Humans_Image.git e adicione a pasta com o dataset montado ao git com os seguintes comandos:
        
        git init
        git clone https://github.com/radiroc/Humans_Image.git
        git add "Humans"
        git commit -m "add"
        git push origin main

obs: Caso o repositório já esteja com o dataset incluso, realize a limpeza do mesmo com os seguintes comandos e efetue a inseção com os comandos acima:
        
        git init
        git clone https://github.com/radiroc/Humans_Image.git
        git rm -r*
        git commit -m "delete"
        git push origin main

## Terceira Etapa - Execução do Classficador de Imagens
Efetue o download ou extraia do repositório o notebook "ClassificadorEtario.ipynb" para executa-lo no Google Colab ou no Jupyter (como preferir).
Após upload do notebook no ambiente desejado, execute todas as etapas e avalie os resultados apresentados. 

