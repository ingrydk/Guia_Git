<p align="center">
  
  <h1 align="center">Guia Git ⭐</h1>
  <p align="center">Feito com 💖 por <a href="https://github.com/ingrydk" target="_blank">Ingryd</a></p>
  </p>

## :dart: Guia super básico e iniciante

> Aqui você encontrará o passo a passo para te ajudar a clonar repositórios remotos para seu computador e como enviar seus códigos para seu repositório remoto. Não seja agoniado. Leia com calma!
> 
> No final, tem um resumo com os principais comandos utilizados.

<sub> <strong>Dê uma forcinha aí nas minhas redes sociais: </strong> <br>
[<img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">](https://github.com/ingrydk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/ingrydk)
</sub>


## ⚠️ Como Clonar um Repositório Remoto para o Seu Computador 💻

- Abra o Git Bash ou o terminal de sua preferência
> Você pode encontrá-lo facilmente pesquisando por "Git Bash" no menu Iniciar do seu computador e clicando para abrir.
>
> Alternativamente, se já estiver na pasta desejada no seu explorador de arquivos, basta clicar com o botão direito do mouse dentro dela e selecionar "Git Bash Here". Isso abrirá o Git Bash nesse local específico e você poderá pular o próximo passo. 
- Navegue até o Local Desejado
>No Git Bash, digite ```cd caminho/para/sua/pasta``` e pressione Enter. Por exemplo, ```cd Documentos/projetos``` e pressione Enter para ir para a pasta onde deseja clonar o repositório. 

> Se você optou por abrir o Git Bash usando o botão direito do mouse dentro da pasta desejada, já está no local correto e pode seguir para o próximo passo.
- Copie o Link do Repositório Remoto
>Vá até o repositório no GitHub, clique no botão verde "Code" e copie o link que aparece. Isso é feito clicando no ícone de "cópia" ao lado do link ou simplesmente clicando com o botão direito do mouse e selecionando "Copiar". 

- Cole o Link no Git Bash
>De volta ao Git Bash, cole o link copiado digitando git clone seguido do link que você acabou de copiar e clique Enter:
```bash
git clone url_do_repositório
```
>O Git irá baixar uma cópia do repositório para a pasta onde você está no Git Bash. 

## ⚠️ Como Subir Seu Código para o Repositório Remoto 🚀
- Faça Suas Mudanças
>Abra a pasta do repositório no seu computador e faça as alterações nos arquivos usando o editor de texto de sua preferência (crie seu código, bb). 

- Adicione as Mudanças
>De volta ao Git Bash, digite git add . e pressione Enter. Isso irá preparar todas as suas mudanças para serem enviadas (sim, há um espaço após "add".
```bash
git add .
```

- Faça o Commit
>Agora, digite git commit -m "Descrição das suas mudanças" e pressione Enter.
```bash
git commit -m "Adiciona novos recursos"
```
>Isso irá salvar suas mudanças localmente. 

- Envie para o Repositório Remoto
>Por fim, digite git push e pressione Enter.
```bash
git push
```
> O Git irá enviar suas alterações para o repositório remoto no GitHub.

## ⚠️ Resumão com bônus xP

- Clonar repositório remoto em uma pasta local
```bash
git clone url_do_repositório
```

- Adicionando todos os arquivos e mudanças na "Staging Area" e os preparando para o próximo commit
```bash
git add .
```

- Adicionando um arquivo específico na "Staging Area" e o preparando para o próximo commit
```bash
git add nome_do_arquivo
```

- Criando ligação entre um repositório remoto e um local
```
git add origin url_repositorio
```
- Fazer commit
```bash
git commit -m "Adiciona novos recursos"
```

- Enviando para repositório remoto
```bash
git push
```

- Criar uma Branch a partir de uma atual
```
git checkout -b nome_da_branch
```

- Trocar de Branch
> Por exemplo, você tá na Branch Main e quer ir para uma outra Branch do mesmo repositório.
```
git checkout nome_da_branch
```

- Listar todas as Branchs
```
git branch
```

- Baixar alterações feitas em uma Branch (na q vc ta)
```
git pull 
```

- Exibir histórico de commits
```
git log
```
 
E voilà! Se você seguiu o passo a passo direitinho, o código já subiu e está disponível para todos no GitHub 🎈
<p align="center">Feito com 💖 por <a href="https://github.com/ingrydk" target="_blank">Ingryd</a></p>
