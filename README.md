## CITi - Onboarding

Este repositório contém todos os materiais necessários para o desenvolvimento do desafio.

## Objetivos
- Ter compreensão de user personas para a criação de um produto
- Saber criar um mapa de fluxo do usuário para um website
- Saber criar um wireframe efetivo
- Ter conhecimento de testes de usabilidade relevantes para o nosso produto
- Saber o que são model, view e template e como cada um trabalha junto 
- Saber criar layouts responsivos para qualquer tipo de dispositivo
- Junto ao design, saber criar templates que sejam agradáveis para o usuário

## Considerações
- Objetos == o que seu sistema fornece: casas ou carros (veja abaixo)
- A parte do administrador (inserção de objetos novos, categorias, etc) será feita pelo painel que é gerado automaticamente pelo Django (/admin), não necessitando de uma parte do site exclusiva para isso
- Se você estiver em dúvida sobre algo, primeiro cheque se está especificado na lista abaixo. Se não estiver, decida com sua equipe (não vamos cobrar nada fora do que está aqui, mas cabe à sua equipe tomar a decisão de como cada coisa deve ficar)

> [Equipe 1](https://github.com/orgs/citi-onboarding/teams/equipe-1/members) deve criar um sistema de aluguel de **casas**, enquanto a [Equipe 2](https://github.com/orgs/citi-onboarding/teams/equipe-2/members) deve criar um sistema de aluguel de **carros**

## Telas
Tela     |   Requisitos
---------|---------------
Início | - Objetos a serem alugados<br>- Menu com link para login, cadastro e página de quem somos<br>_Obs: Se o usuário estiver autenticado, substituir os botões de login e cadastro para logout_
Login | - Formulário de login simples, com usuário e senha
Cadastro | - Formulário de cadastro simples, com usuário, senha e confirmação de senha
Perfil | - O usuário poderá ver o que ele alugou<br>- Ele poderá ver também outras pessoas que estão cadastradas no sistema
Lista | - Cards com informações sobre o objeto a ser alugado: nome, preço, data de adição<br>- Nesses cards, incluir um botão para alugar o objeto em questão
Quem Somos | - Um texto sobre o sistema (pode usar `{% lorem 2 p %}` no template)

## Entregas
Teoricamente, todos os finais de semana devem ter entregas. Como o último foi design, a entrega deste sábado (02/12) seria sobre design, mas pelo atraso, o prazo foi alterado. **Todas as entregas devem ser feitas no GitHub e a branch considerada sempre será a master.**

### 🖌 Primeira semana: Design
> O prazo é Sábado, 16/12/2017

A equipe deverá criar um mockup, wireframe e a user persona do sistema. Os entregáveis estão abaixo:
- [ ] User persona do sistema (a definição do usuário ideal, [isso pode ajudar](https://www.caelum.com.br/apostila-ux-usabilidade-mobile-web/images/06_personas/personinha.jpg))
- [ ] Wireframe de baixa fidelidade **apenas da tela de perfil e lista** (pode ser em guardanapo, papel, Paint... só queremos saber onde cada coisa vai ficar!)
- [ ] Mockup **apenas da tela de Início** (em PNG ou PDF)
- [ ] Fluxo de usuário do sistema ([exemplo](https://i.pinimg.com/originals/6f/8c/a9/6f8ca96ea2c3e3613c9ef64b5f4b680d.jpg)) _(Não precisa ser elaborado, só queremos saber quais os caminhos do sistema)_

### ⚙ Segunda semana: Backend
> O prazo é Sábado, 09/12/2017

A equipe deverá entregar o backend do sistema em Django. Os entregáveis estão abaixo:
- [ ] Todos os models criados (o objeto - carro ou casa - e o usuário) _(se a equipe achar necessário, pode criar quantos outros quiser, por exemplo, um model que registre os aluguéis feitos com dois FKs: casa/carro e usuário)_
- [ ] Sistema de autenticação funcional (login, cadastro, logout)
- [ ] Urls, views e templates básicas (não precisa estar estilizado) para cada aplicação
Nota: Em resumo, o sistema deve estar completamente funcional, faltando apenas estilização e implementação de responsividade

### 💻 Segunda semana: Frontend
> O prazo é Sábado, 16/12/2017

A equipe deverá entregar o frontend do sistema em Django. Os entregáveis estão abaixo:
- [ ] Responsividade
- [ ] Interface gráfica estilizada
