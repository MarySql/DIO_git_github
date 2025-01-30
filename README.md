
# DIO | Resumo Git e Github 

Breve resumo do conteúdo visto no bootcamp da DIO 

### O que é Git? 💻

> Git é um sistema de controle de versão distribuído que permite acompanhar mudanças no código-fonte de um projeto. Com ele, é possível: 

- Rastrear modificações no código ao longo do tempo.

- Trabalhar em equipe de forma eficiente.

- Criar diferentes versões do projeto (branches) e mesclá-las.

- Restaurar versões anteriores caso necessário.

### O que é GitHub?

> GitHub é uma plataforma de hospedagem de repositórios Git baseada na nuvem. Ele oferece recursos como:

- Armazenamento de repositórios públicos e privados.

- Colaboração entre desenvolvedores via pull requests e issues.

- Integração com ferramentas de CI/CD para automação de processos.

- Controle de permissões para equipes.
# Comandos Básicos do Git

### Configurar o usuário

`git config --global user.name` "Seu Nome"
`git config --global user.email` "seuemail@example.com"

### Inicializar um repositório Git
`git init`

### Clonar um repositório existente
`git clone` URL_DO_REPOSITORIO

### Verificar o status dos arquivos
`git status`

### Adicionar arquivos ao controle de versão
`git add .`   Adiciona todas as mudanças

### Criar um commit com uma mensagem
`git commit -m` "Mensagem do commit"

### Enviar alterações para o repositório remoto
`git push origin main`

### Atualizar o repositório local com mudanças remotas
`git pull origin main`

### Criar uma nova branch
`git checkout -b` nome-da-branch

### Alternar entre branches
`git checkout` nome-da-branch

### Mesclar uma branch na branch atual
`git merge` nome-da-branch

# Dicas 👇

- Use `git log --oneline --graph` para visualizar o histórico de commits.

- Adicione um `.gitignore` para evitar o versionamento de arquivos desnecessários.

- Sempre faça `git pull` antes de iniciar uma nova tarefa para evitar conflitos.

- Utilize boas mensagens de commit para facilitar o rastreamento das mudanças.

Para mais informações, consulte a documentação oficial do Git (https://git-scm.com/docs/git/pt_BR)
 e do GitHub (https://docs.github.com/pt).
