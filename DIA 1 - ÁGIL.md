# DIA 1 - ÁGIL

## CONTEÚDO

* Organização
* Git e Gitlab
* ReadMe

# 1 - Organização

A organização é fundamental para atingir os objetivos, seja de estudos, ou para atingir resultados no ambiente de trabalho.
Desde anotações em bloco de notas, até mesmo agendas digitais, a organização fará a produtividade geral aumentar consideravelmente.

## Ferramentas recomendadas:

1. **Notion**

- Notion é um aplicativo da web freemium para produtividade e anotações desenvolvido pela Notion Labs Inc. Ele oferece ferramentas organizacionais, incluindo gerenciamento de tarefas, rastreamento de projetos, listas de tarefas e marcadores . Recursos off-line adicionais são oferecidos por aplicativos de desktop e móveis disponíveis para Windows, macOS, Android e iOS . Os usuários podem criar modelos personalizados, incorporar vídeos e conteúdo da web e colaborar com outras pessoas em tempo real.

2. **Microsoft OneNote**

- O Microsoft OneNote é um programa de computador para o recolhimento de informação de forma livre e colaboração multiusuário. Ele recolhe as notas do usuário (manuscritas ou digitadas), desenhos, recortes de tela e comentários de áudio. As notas podem ser compartilhadas com outros usuários do OneNote através da internet ou por uma rede.

3. **Obsidian**

- Obsidian é um aplicativo de anotações em arquivos que utilizam a linguagem Markdown e se destinam à formação de uma base pessoal de conhecimentos. Ele permite que os usuários façam links internos entre anotações e depois visualizem as conexões como um gráfico. Ele é projetado para ajudar os usuários a organizar e estruturar pensamento e conhecimentos de maneira flexível e não linear. O software é gratuito para uso pessoal, com licenças comerciais disponíveis mediante pagamento.

## 2 - Matriz de Eisenhower

A Matriz de Eisenhower é uma ferramenta de gestão do tempo que ajuda a priorizar tarefas com base em dois critérios: urgência e importância.
a matriz é representada em um plano cartesiano e categoriza as atividades em quatro quadrantes:

## Quadrantes da Matriz de Eisenhower

1. **Importante e Urgente**

   - Tarefas que precisam ser tratadas imediatamente, como crises e prazos iminentes.

2. **Importante, mas Não Urgente**

   - Tarefas que devem ser planejadas e agendadas, como desenvolvimento pessoal e estratégias a longo prazo.

3. **Urgente, mas Não Importante**

   - Tarefas que podem ser delegadas ou minimizadas, pois não contribuem significativamente para os objetivos a longo prazo.

4. **Não Importante e Não Urgente**

   - Tarefas que podem ser evitadas ou realizadas apenas quando todas as outras tarefas mais importantes forem concluídas.

# 3 - Git e Gitlab

## Requisitos

- [ ] Sistema Operacional: Windows, macOS ou Linux
- [ ] acesso a internet
- [ ] (opicional) Familiaridade com comandos em terminal

## Instalação do Git

- Baixar e instalar o `Git` através do `Link`: 
[Link para download](https://git-scm.com/downloads)

## Criar um novo projeto no desktop

* Crie uma nova pasta no desktop com o nome do projeto, por exemplo `Meu projeto git`

* Abrir o editor de código dentro da pasta, neste exemplo, o Vscode

* Criar um arquivo `README.md`

* Em caráter de exemplo, escreva algo para salvar nessa primeira versão do `README.md`, conforme exemplo:

* Salve o arquivo

## Dentro do GitBash

* Inicie `Git Bash` através da opção `Git Bash here` dentro da pasta do projeto

* Execute o comando `Git init` para inicializar o repositório

    ```sh
    git init
    ```
Com este comando, é criado uma pasta `.git`, ao qual **não deve ser apagada**

* Utilize o comando `git add` para transferir os arquivos do repositório para a `staging area`
    ```sh
    git add
    ```
Vale ressaltar, que podemos realizar este comando de duas maneiras:

- git add <nome_do_arquivo> fará a adesão de apenas um único arquivo criado ou atualizado, bastando colocar o nome especifico dele 

- git add . fará a adesão de todos os arquivos criados ou atualizados, bastando colocar o caractere `.` para representar esta ação.

a imagem abaixo demonstra na prática este processo entre transferência da máquina para o repositório online:

* Feito isto, poderá realizar a adição de um ou mais arquivos do seu `repositório local` para o `repositório remoto`

* Para confirmar se o(s) arquivos(s) foram direcionados para a `staging area`, podemos realizar o comando `git status`

    ```sh
    git status
    ```

* Precisamos criar o commit para registrar as ações ou adesões realizadas, para isto, iremos utilizar o comando `git commit`

    ```sh
    git commit -m "descrição das mudanças realizadas"
    ```

## Criando o repositório no GitHub

Para realizarmos a transferência dos arquivos que mantemos na `staring area` diretamente para o `repositório online`, devemos criar um novo `repositório` dentro do `git hub`.
De forma prática, após criar a sua `conta`, basta clicar dentro do seu perfil em `repositórios` e em seguida, `new`. Conforme na imagem, basta preencher os campos para criar o `repositório`

## Após a criação do projeto e repositório
Com o `projeto` e o `repositório`repositório criado, será demonstrado abaixo os principais conceitos e comandos utilizados

* Criar uma nova pasta no PC pra isso chamada `Git Tutorial`

* Abrir o VSCode nessa pasta

* Criar um novo arquivo `README.md`

## Comandos utilizados neste documento
- `git --version`: checa a versão de instação do git na sua máquina.
    ```sh
    git --version
    ```
