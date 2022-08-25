# Sinta-se em casa!

Este repositório de boas vindas para novos membros.

## Você já sabe clonar um repositório?

Encontre e experimente clonar este repositório. Você só precisa fazer isso na primeira vez que vai trabalhar no projeto.

> Dica: botão verde aqui perto tem a url.

`$ git clone [url]`

## Onde você encontra as tarefas do projeto?

A aba Issues conterá todas as tarefas em andamentos, sejam elas bugs a corrigir, novas funcionalidades, ou alguma que não seja diretamente relacionada ao código em si.

O coordenador do projeto irá designar que tarefas ficarão aos seus cuidados, dentro da própria e você receberá notificações disso. Também é possível filtrar as tarefas que estão definidas para você.

Como você chegou agora, provavelmente uma tarefa de boas vindas foi criada. Dê uma lida primeiro, e perceba que você pode colocar perguntas lá. Apenas leia a issue e volte pra cá. Depois você continua.

## Como você resolve as tarefas?

> Alerta: Jamais realize commits e push para o branch main. É muito arriscado para o projeto em si.

Se você já clonou o repositório, crie um branch de trabalho só pra você:

`$ git switch -c umNomeASuaEscolha`

> Dica: Escolha um nome que lhe lembre para quê você criou esse branch.

Codifique a solução da tarefa, rode testes, etc (cada projeto específico terá suas próprias necessidades aqui), e:

1. Configure suas informações pessoais:

`$ git config user.name "Seu Nome"`

`$ git config user.email seuemail@uhuuul.com`

2. Ponha os arquivos de interesse em estado "staged"

`$ git add .` (este exemplo adiciona tudo que foi criado, modificado ou excluído do repositório)

3. Grave uma mensagem de commit (confirmação das alterações)

`$ git commit -m "descreva o que realizou"`

> Dica: faça commits que tem estrita relação com uma tarefa apenas, de modo a simplificar revisões de modificações. Isso é especialmente interessante em projetos com mais membros.

4. Envie as modificações para o repositório

`$ git push origin oNomeDoBranchQueVocêCriou`

Suas alterações estão no repositório, mas, que tal seguirmos boas práticas e trabalharmos com colaboração?

## Colaboração entre membros

Após subir seu branch, crie um pull request a partir do seu branch e marque um membro da equipe para revisar suas alterações.

> Ao criar o pull request você pode em sua descrição mencionar a issue que está trabalhando usando o símbolo de "jogo da velha", formalmente conhecido como cerquilha, e o número da mesma. Isso vai facilitar o GitHub ligar esse seu trabalho àquela tarefa.

Essa pessoa poderá:

- Aprovar suas alterações, e isso liberará suas alterações para serem aplicadas sobre a versão principal do projeto
- Comeentar suas alterações sugerindo mudanças ou tirando dúvidas
- Recomendar alterações, e você continuará seus trabalhos no mesmo branch (todo push para ele irão parar nesse pull request ainda)

Quando todo esse processo concluir, seu trabalho finalmente fez efeito sobre a versão principal do código.

## Consigo acompanhar o fluxo disso tudo em algum lugar?

Na aba projects há um kanban que para algumas ações é automatizado, mas você pode mover as tarefas que está trabalhando livremente entre as colunas.

Quando concluir esse passo a passo de onboarding, informe o coordenador do seu projeto.
