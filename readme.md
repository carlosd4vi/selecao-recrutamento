# ![Logo Grupo 3x](https://archive.org/download/sua_logo/sua_logo.jpg) 
# Grupo 3x

O Grupo 3x é um dos maiores varejistas do Ceará, fundado em 1979 na cidade de Maracanaú, destacando-se fortemente no setor de alimentos com o Frangolândia Supermercados. Atualmente, a rede abrange mais de 20 unidades, incluindo a bandeira Mega Atacadista e a plataforma de inovação digital, o app de compras Levoo.

## 🎯 Projeto de Seleção e Recrutamento
O intuito do Projeto é ajudar os recrutadores a centralizar a atração de talentos, padronizar o recebimento de candidaturas e otimizar drasticamente o tempo de análise dos perfis. Através de uma plataforma própria, o sistema elimina a dependência de plataformas de terceiros, oferecendo um fluxo de trabalho seguro, automatizado e sob medida para a alta demanda de contratações das diversas marcas do grupo.

## 📸 Visão Geral da Plataforma

### Tela Inicial
![Print da Tela Inicial](https://ia902801.us.archive.org/16/items/home_20260512/home.PNG)

A Página apresenta a cultura, os valores e a dimensão do Grupo 3x de forma atrativa, moderna e responsiva. É o cartão de visitas digital que fortalece a marca empregadora da empresa e engaja os talentos a fazerem parte da equipe.

### Vagas
![Print do Painel de Vagas](https://archive.org/download/home-vagas/home-vagas.PNG)

Uma Página dinâmica com todas as oportunidades disponíveis no momento. Os candidatos podem navegar pelas vagas, visualizar requisitos, benefícios e regime de trabalho, e realizar a candidatura de forma ágil e segura, submetendo seus dados e currículos em PDF através de um formulário.

### Detalhes da Vaga
![Print do Painel de Vagas](https://archive.org/download/detalhes_202605/detalhes.PNG)

Nos Detalhes da Vaga contém titulo, Tipo de Vaga (Ex: Efetivo (CLT)), Localidade, Salário, Modelo de Trabalho, Atividades, Requisitos e Benefícios da empresa. e logo abaixo o Formulário.

### Formulário do Candidato
![Print do Formulário Candidato](https://archive.org/download/vaga-candidatar/vaga-candidatar.PNG)

É um Formulário Público onde qualquer pessoa tem a possibilidade de candidatar-se (Sem precisar criar uma conta). O Formulário conta com uma segurança de Recaptcha contra bots e automações, e verificações de arquivos maliciosos. E também PDFs com senha. (Será notificado ao usuário caso ocorrer).

### Lojas
![Print da Lojas](https://ia902904.us.archive.org/17/items/lojas_202605/lojas.PNG)

A Página apresenta as unidades disponiveis das Lojas Frangolândia em bairros, municípios e cidades.

### Contato
![Print do Contato](https://archive.org/download/lojas_202605/contato.PNG)

A Página apresenta contatos para o CD (Central) Maracanaú e Lojas de Fortaleza.

## ⚙️ Área Restrita (Painel do Recrutador)

### Dashboard: Postar Vagas
![Print do Dashboard de Postar Vagas](https://archive.org/download/lojas_202605/postarvagas.PNG)

Desenvolvido para ser intuitivo e rápido, permite que o time de RH publique novas vagas em segundos. O recrutador preenche dados cruciais como título, atividades, localidade (ex: Maracanaú, Fortaleza), salário e modelo de trabalho. Uma vez salva, a vaga começa a exibir para o Público.

### Vagas Ativas
![Print das Vagas Ativas](https://archive.org/download/lojas_202605/vagasativas.PNG)

É possível acompanhar vagas que estão disponiveis, a quantidade de pessoas que se inscreveram na vaga, editar informações, alterar o status ou encerrar inscrições com um único clique.

### Triagem & Sistema ATS (Applicant Tracking System)
![Print da Tela de Triagem](https://archive.org/download/lojas_202605/Triagem.PNG)

Essa Página lista todos os currículos recebidos com filtros por vaga específica. O grande diferencial é o Sistema ATS integrado, que realiza uma leitura preliminar e fornece um Raio-X de Compatibilidade (Match) do candidato com a vaga, gerando um score (pontuação) baseado em experiência, habilidades e formação. A tela também conta com ações de "Excluir" ou "Baixar", permitindo ao RH excluir múltiplos perfis ou baixar todos os PDFs filtrados em um único arquivo compactado (.zip), poupando horas de trabalho manual.

### Visualizador de Currículos Nativo
![Print do Visualizador Nativo](https://archive.org/download/lojas_202605/triagem-visualizar-curriculo.PNG)

O Sistema permite que o recrutador visualize o arquivo PDF do candidato em tela cheia (através de um Modal elegante) sem precisar fazer o download para a sua máquina ou depender de softwares externos. Leitura rápida, fluida e integrada à jornada de decisão.

## 🛠 Tecnologias Utilizadas
Este projeto foi construído com uma arquitetura moderna, focada em segurança, performance e escalabilidade:

* **Frontend:** React.js
* **Backend:** Node.js (API RESTful segura, manipulação em memória para segurança de arquivos)
* **Banco de Dados & Storage:** Supabase (PostgreSQL, Políticas de RLS rigorosas)
* **Estilização:** Tailwind CSS (Padrões de design limpo e responsivo)
* **Funcionalidades Extras:** Compactação nativa no navegador (JSZip) para exportação de arquivos.
