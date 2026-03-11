# 📚 E-Portal

Sistema web desenvolvido como Trabalho de Conclusão de Curso (TCC) do curso **Técnico em Desenvolvimento de Sistemas da ETEC de Poá**.

O **E-Portal** é uma plataforma de comunicação interna voltada para estudantes, com o objetivo de centralizar **avisos, projetos extracurriculares, cursos e oportunidades** dentro da instituição.

O sistema permite que setores como **Grêmio Estudantil, Atlética e administração escolar** publiquem conteúdos e avisos relevantes, facilitando o acesso à informação pelos alunos.

---

# 🎯 Objetivo do Projeto

Durante nossa vivência na ETEC, identificamos que muitas informações importantes sobre **projetos, cursos, eventos e oportunidades** eram divulgadas de forma dispersa ou pouco acessível.

O **E-Portal** foi criado para resolver esse problema, oferecendo uma plataforma digital onde os alunos podem acompanhar facilmente tudo o que acontece dentro da escola.

---

# 🛠 Tecnologias Utilizadas

O projeto foi desenvolvido utilizando tecnologias comuns no desenvolvimento web:

- HTML
- CSS
- JavaScript
- MySQL
- Node.js
- Bibliotecas/frameworks como: Express e Multer

---

# 🚀 Funcionalidades

O sistema possui diferentes níveis de acesso e funcionalidades, incluindo:

### 👤 Área do usuário
- Login e autenticação
- Visualização de avisos gerais
- Visualização de projetos e cursos disponíveis
- Perfil do usuário

### 📰 Sistema de notícias
- Publicação de avisos e comunicados
- Organização de conteúdos por categoria

### 🛠 Painel administrativo
- Sistema **CRUD completo**
- Gerenciamento de projetos
- Gerenciamento de avisos
- Controle de conteúdos publicados

### 🎓 Conteúdos disponíveis
- Projetos extracurriculares
- Cursos
- Avisos institucionais
- Informações relevantes para alunos

### 🔐 Segurança e controle de acesso
- Sistema de **autenticação obrigatória**, impedindo acesso às páginas sem login
- **Controle de níveis de permissão**, separando usuários comuns e administradores
- **Verificações de sessão** para garantir que apenas usuários autenticados possam acessar determinadas funcionalidades

---

# ▶️ Executando o Projeto

1. Clone o repositório.
2. Instale as Dependências `npm install`.
3. Configure o banco de dados. Importe o arquivo `.sql` presente na pasta do projeto utilizando o phpMyAdmin ou qualquer outra ferramenta de preferência.
4. Inicie o Servidor: `npm run dev`.
5. Acesse `http://localhost:8080/login` em seu navegador.<br>
🔑 Login de Administrador:
  Usuario `23040`
  Senha `54321`

# 🖥️ Demonstração do Sistema

### Tela de Login
Página inicial do sistema onde o usuário realiza a autenticação utilizando suas credenciais. O acesso às demais páginas do portal é restrito a usuários autenticados, garantindo maior segurança no acesso às informações.

![login_page](https://github.com/user-attachments/assets/a794f99b-87eb-43c0-82e9-fb561dc12fa1)

### Avisos Gerais
Área destinada à exibição de comunicados e avisos importantes publicados pela instituição ou por administradores do sistema, mantendo os alunos informados sobre eventos, atualizações e outras informações relevantes.

![avisos-gerais](https://github.com/user-attachments/assets/30f90bb9-62ab-4ccd-b428-c01979e4b8e8)

### Gerenciamento de Postagens (CRUD)
Interface exclusiva para administradores, onde é possível gerenciar o conteúdo da plataforma através de operações **CRUD (Create, Read, Update, Delete)**. Nessa área é possível criar, editar e remover informações publicadas no portal. <br>
Ao realizar a postagem, ela guarda também o **horário** em que foi realizada, além das informações de **quem** a fez.

![CRUD](https://github.com/user-attachments/assets/2c777e1c-ed10-425a-b28f-f8f6cd6630c2)

### Projetos Extracurriculares
Seção dedicada à divulgação de **projetos extracurriculares** oferecidos pela instituição. Os alunos podem visualizar informações detalhadas sobre cada projeto disponível.

![projetos](https://github.com/user-attachments/assets/2432ebac-545f-497b-a1ba-199cd69d4541)

### Perfil do Usuário
Página onde o usuário pode visualizar suas informações pessoais, que são puxadas diretamente do banco de dados do sistema, além de acessar funcionalidades relacionadas à sua conta como alterador de senha e outras informações.

![perfil](https://github.com/user-attachments/assets/436a3723-b4a3-4f0c-bff5-b9a1f3a042d2)

### Postagem de Avisos por Curso
Página destinada à criação e gerenciamento de avisos específicos para cada curso.  
Administradores podem visualizar e publicar avisos para diferentes cursos, enquanto os alunos visualizam apenas os avisos relacionados ao **seu próprio curso**, garantindo uma comunicação mais direcionada.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/a59e3b10-8d7f-48c9-b5ea-180b16f13791"/>

### Postagem de Estágios
Área do sistema voltada para a publicação de **oportunidades de estágio**.  
Administradores podem cadastrar novas vagas, permitindo que os alunos acompanhem oportunidades relevantes para sua formação e inserção no mercado de trabalho.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/cc8c2d41-f52d-45c6-af77-d254dd016352"/>

### Visão do Aluno
Exemplo da interface visualizada por alunos ao acessarem o sistema. Nota-se que eles não podem visualizar os botões para gerenciar as postagens, além disso, ao visualizarem os avisos relacionados ao curso, só podem visualizar as postagens para o curso em que eles estão cadastrados.

![visão_aluno](https://github.com/user-attachments/assets/7d9a74b9-ba46-4094-8786-9c57b4effd2a)

---

# 👨‍💻 Desenvolvimento

Este projeto foi desenvolvido em grupo como parte do **Trabalho de Conclusão de Curso (TCC)** do curso Técnico em Desenvolvimento de Sistemas da **ETEC de Poá**. A equipe foi composta por **5 estudantes**, responsáveis pelo planejamento, desenvolvimento e documentação do sistema.

A ideia do **E-Portal** surgiu a partir de uma observação feita pelos alunos durante a rotina escolar na **ETEC de Poá**. Muitas informações importantes sobre **projetos extracurriculares, cursos, eventos e avisos institucionais** eram divulgadas de forma descentralizada, muitas vezes apenas por murais físicos, redes sociais ou comunicação informal.

Essa falta de centralização dificultava o acesso dos alunos às oportunidades oferecidas pela escola, fazendo com que muitos sequer soubessem da existência de determinados projetos ou atividades.

Diante desse cenário, surgiu a proposta de desenvolver uma plataforma digital que reunisse todas essas informações em um único lugar. Assim nasceu o **E-Portal**, um sistema pensado para facilitar a comunicação interna da escola e tornar o acesso à informação mais simples, organizado e acessível para todos os alunos.

---

# 📌 Possíveis Melhorias Futuras

- Sistema de notificações
- Sistema de inscrição em projetos
- Melhorias na interface e experiência do usuário
- Versão mobile mais otimizada
