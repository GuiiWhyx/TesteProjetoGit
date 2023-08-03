Como utilizar o github como repositório?

*Criando projeto*

- Criar uma pasta no PC (será o repositório local / seu código)

- Abrir VSCode ou outra IDE.

- Criar o arquivo "Readme.md" e salvar.

- Dentro da pasta do repositório local, clicar com botão direito e abrir o Git Bash.

- "git init" irá inicializar o diretório.

- Criada uma pasta chamada .git no diretório.

- "git add Readme.md" para enviar o arquivo para área de stagging.

- "git commit -m 'primeiro commit'" para realizar o commit ao repositório.

- "git branch -M 'main'" altera o nome da branch principal.

- Criar repositório no Github, adicionar nome e breve descrição.

- Copiar o link gerado na página do Git.

- Para informar para onde o código deverá ser enviado, devemos utilizar o link do repositório.

- "git remote add origin <link do repositório>"

- origin é o nome de referência do repositório.

- Com isso o repositório local já esta conectado ao repositório do Github, mas para o commit ser enviado para o github, é preciso empurrá-lo.

- "git push -u origin main" Irá realizar o envio do commit para o Github.






