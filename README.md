# 📚 Plataforma EAD

<div align="center">
<img src="https://github.com/portfolio-projetos-dev/plataforma-ead/raw/main/.gitassets/capa.png" width="350" />

<div data-badges>
    <img src="https://img.shields.io/github/stars/portfolio-projetos-dev/plataforma-ead?style=for-the-badge" alt="GitHub stars" />
    <img src="https://img.shields.io/github/forks/portfolio-projetos-dev/plataforma-ead?style=for-the-badge" alt="GitHub forks" />
    <img src="https://img.shields.io/github/issues/portfolio-projetos-dev/plataforma-ead?style=for-the-badge" alt="GitHub issues" />
</div>

<div data-badges>
    <img src="https://img.shields.io/badge/next.js-%23000000.svg?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
    <img src="https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" />
    <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
    <img src="https://img.shields.io/badge/prisma-%232D3748.svg?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma" />
    <img src="https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
    <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
    <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS" />
    <img src="https://img.shields.io/badge/jwt-%23323330.svg?style=for-the-badge&logo=json-web-tokens&logoColor=pink" alt="JWT" />
   <img src="https://img.shields.io/badge/turborepo-%23000000.svg?style=for-the-badge&logo=turborepo&logoColor=white" alt="Turborepo" />
   <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
   <img src="https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
   <img src="https://img.shields.io/badge/prettier-%23F7B93E.svg?style=for-the-badge&logo=prettier&logoColor=white" alt="Prettier" />
   <img src="https://img.shields.io/badge/eslint-%234B32C3.svg?style=for-the-badge&logo=eslint&logoColor=white" alt="ESLint" />
   <img src="https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" />
   <img src="https://img.shields.io/badge/swc-%23F7B93E.svg?style=for-the-badge&logo=swc&logoColor=white" alt="SWC" />
   <img src="https://img.shields.io/badge/jest-%23C21325.svg?style=for-the-badge&logo=jest&logoColor=white" alt="Jest" />
   <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</div>
</div>

A Plataforma de Ensino a Distância é um projeto que tem como objetivo proporcionar uma experiência de aprendizado completa e focada no desenvolvimento de habilidades em programação. A plataforma abrange uma ampla gama de cursos, que vão desde introdução à programação até linguagens, frameworks e tecnologias avançadas, atendendo tanto iniciantes quanto profissionais que desejam se especializar ou atualizar seus conhecimentos. Além disso, os usuários contam com o suporte de um time dedicado para esclarecer dúvidas e auxiliá-los durante toda a jornada de aprendizado, garantindo uma experiência mais eficiente e personalizada.

Os usuários podem criar suas contas, se inscrever nos cursos de interesse e acessar materiais didáticos variados, como vídeos explicativos, textos detalhados e exercícios práticos que ajudam a fixar o conteúdo aprendido. A plataforma também oferece fóruns de suporte, onde os alunos podem interagir com colegas e instrutores, compartilhar experiências e tirar dúvidas em um ambiente colaborativo. Cada curso possui um sistema de progresso independente, permitindo que os alunos acompanhem seu desempenho individual em cada módulo ou atividade. Além disso, ao concluir um curso, o aluno recebe um certificado digital que pode ser acessado diretamente em sua conta, ajudando a comprovar suas conquistas e a valorizar seu currículo.

Outro diferencial da plataforma é a possibilidade de os alunos consultarem estatísticas detalhadas sobre seu desempenho, como porcentagem de conclusão de cursos e tempo dedicado a cada módulo. Isso permite que o estudante tenha controle total sobre sua evolução e identifique áreas que precisam de maior dedicação.

## 🖥️ Como rodar este projeto 🖥️

### Requisitos:

- Node.js instalado
- Docker instalado

### Execução:

1. Clone este repositório:

   ```sh
   git clone https://github.com/portfolio-projetos-dev/plataforma-ead.git
   ```

2. Acesse o diretório do projeto:

   ```sh
   cd plataforma-ead
   ```

3. Rode o comando de configuração:

   ```sh
   npm run config
   ```

   Este comendo irá executar um script com diversas fases onde diferentes configurações, como criação de arquivos de ambiente, instanciação de containers docker, instalação de dependências, etc.

4. Configure as variáveis de ambiente:

   Verifique os arquivos `.env` criados nas seguintes páginas e os preencha com as variáveis adequadas:

   - `apps/admin`
   - `apps/web`
   - `apps/backend`

5. Inicie a aplicação rodando o comando `npm run dev` na pasta raiz da sua aplicação.

6. Acesse o projeto web em [http://localhost:3000](http://localhost:3000) e o projeto mobile através do emulador que será aberto automáticamente.

## 🗒️ Features do projeto 🗒️

- Cadastro e Login de Usuários
- Login seguro com autenticação (e-mail e senha ou autenticação via redes sociais)
- Navegação por uma ampla variedade de cursos
- Acompanhamento do progresso em cada curso com indicação de módulos concluídos e pendentes
- Emissão de certificados digitais personalizados para cada curso concluído
- Acesso e download de certificados diretamente no perfil do usuário
- Acesso a vídeos, textos, slides e exercícios práticos
- Fórum de Suporte e Discussão para tirar dúvidas e interagir com instrutores e outros alunos
- Ferramentas para criar cursos, adicionar vídeos, textos,e outros recursos na área administrativa da plataforma
- Envio de Notificações para alunos sobre novos cursos, progresso ou eventos ao vivo

![](https://github.com/portfolio-projetos-dev/plataforma-ead/raw/main/.gitassets/1.png)

![](https://github.com/portfolio-projetos-dev/plataforma-ead/raw/main/.gitassets/2.png)

![](https://github.com/portfolio-projetos-dev/plataforma-ead/raw/main/.gitassets/3.png)

## 💎 Links úteis 💎

- [Next.js](https://nextjs.org/docs)
- [NestJS](https://docs.nestjs.com/)
- [Prisma](https://www.prisma.io/docs)
- [PostgreSQL](https://www.postgresql.org/docs/)
- [Tailwind CSS](https://tailwindcss.com/docs)
