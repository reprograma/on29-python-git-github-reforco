## Exercício de Git: "Mulheres que te Inspiram"

Este exercício envolve a criação de um repositório colaborativo chamado "Mulheres que te Inspiram". Cada aluna do curso irá adicionar uma contribuição ao repositório, destacando uma mulher que as inspira, com uma foto, uma descrição e uma palavra que a define. Este exercício prático ensina os fundamentos do Git e do GitHub, promove a colaboração e celebra mulheres notáveis de todo o mundo. 🧡

### Objetivo:
Utilizar Git e GitHub para criar um projeto colaborativo que destaca mulheres inspiradoras de todo o mundo.

### Materiais Necessários:
- Git instalado no computador.
- Uma conta no GitHub.
- Uma imagem da mulher que te inspira ou uma imagem representativa.

### Passos para o Exercício:

1. **Setup Inicial**
   - Todos as alunas fazem fork deste repositório para suas contas do GitHub.

2. **Clone o Repositório**
   - Cada aluna clona o repositório forkeado para seu computador:
     ```bash
     git clone https://github.com/{{SeuUsuario}}/reprograma/on29-python-git-github-reforco.git
     cd Mulheres-que-te-Inspiram
     ```

3. **Criação de Branch**
   - Crie uma branch dedicada à mulher que você deseja destacar:
     ```bash
     git checkout -b inspiracao-[nome-da-mulher]
     ```
   - Exemplo: `git checkout -b inspiracao-beyonce`

4. **Adicionar Contribuição**
   - Escreva um arquivo Markdown (`.md`) com informações sobre a mulher que te inspira. Inclua uma foto, por que ela te inspira, e uma palavra que a define:
     ```markdown
     ## Mulheres que Inspiram: Beyoncé

     ![Beyoncé](link-para-uma-imagem-de-Beyoncé-aqui)

     ### Por que ela me inspira
     Beyoncé é uma figura icônica não apenas no mundo da música, mas também como uma mulher de impacto que usa sua plataforma para promover a igualdade, a justiça e o empoderamento. Suas músicas, suas ações públicas e seu ativismo me inspiram a ser forte, independente e a lutar pelo que é certo.

     ### Uma Palavra para Defini-la
     Empoderadora
     ```
   - Salve o arquivo no diretório do projeto e adicione ao Git:
     ```bash
     git add .
     git commit -m "Adiciona inspiração por Beyoncé"
     ```

5. **Push e Pull Request**
   - Faça push da sua branch para o GitHub:
     ```bash
     git push origin inspiracao-beyonce
     ```
   - No GitHub, crie uma Pull Request da sua branch para a branch `main` do repositório original, descrevendo brevemente o conteúdo.

6. **Revisão e Merge**
   - Outras alunas podem revisar as Pull Requests, fornecendo feedback e aprendendo mais sobre mulheres inspiradoras.
   - Pull Requests aprovadas podem ser merged para a branch principal, formando um belo mural de mulheres inspiradoras.

### Resultado Esperado:
Ao final, o repositório `Mulheres-que-te-Inspiram` será uma compilação rica e motivadora de histórias sobre mulheres notáveis, todas documentadas e celebradas pelas alunas do curso. Este exercício ensina os fundamentos do Git e do GitHub de maneira prática e promove inspiração através das conquistas femininas ao longo da história e no mundo contemporâneo.
