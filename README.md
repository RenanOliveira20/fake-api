# fake-jsonServer

> JSON fake server. Fork this "repo" and start on the "7000 PORT".

## Requisitions table :
|/v1/performance/sales/store/:locationId/daily|vendas diárias loja|
|---------------------------------------------|-------------------|
|/v1/performance/sales/store/:locationId/monthly | vendas mensais loja |
|/v1/performance/sales/store/:locationId/sections/daily| vendas de todas as seções no dia|
|/v1/performance/sales/store/:locationId/section/:sectionCode/daily|vendas diarias do setor especifico|
|/v1/performance/sales/store/:locationId/subsection/:subsectionCode/daily|vendas diarias da subseção especifica|
|/v1/performance/sales/store/:locationId/section/:sectionCode/monthly|vendas mensais do setor especifico|
|/v1/performance/sales/store/:locationId/subsection/:subsectionCode/monthly|vendas mensais da subseção especifica|
|/v1/performance/sales/store/:locationId/advisors/:sectionCode/daily |vendas dos assessores da seção especifica no dia|
|/v1/performance/sales/store/:locationId/advisors/:sectionCode/monthly|vendas dos assessores da seção especifica no mês|
|/v1/performance/sales/store/:locationId/humanResource/employee/:ldapNumber|buscar funcionario especifico|

### Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas nas seguintes tarefas:

- [X] Adicionar Funcionalidades
- [ ] Melhoria de UI/UX
- [ ] Melhoria de performance 
- [ ] Atualizações e expansão 

## 💻 Pré-requisitos

Insert the script (Scripts:"start" : "json-server --port 7000 --routes routes.json --watch db.json"). And go with npm start.
)

## 📫 Contribuindo com <fake-jsonServer>

Para contribuir com fake-jsonServer, siga estas etapas:

1. Bifurque este repositório.
2. Crie um branch: `git checkout -b <nome_branch>`.
3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`
4. Envie para o branch original: `git push origin <nome_do_projeto> / <local>`
5. Crie a solicitação de pull.

Como alternativa, consulte a documentação do GitHub em [como criar uma solicitação pull](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## 🤝 Colaboradores

Ranan, Christopher e Ricardo.

## 😄 Seja um dos contribuidores<br>

Quer fazer parte desse projeto? Clique [AQUI](CONTRIBUTING.md) e leia como contribuir.

## 📝 Licença

Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE.md) para mais detalhes.

[⬆ Voltar ao topo](fake-jsonServer)<br>