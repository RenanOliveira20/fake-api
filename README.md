# fake-jsonServer

> JSON fake server, clone este "repo" e inicie na porta "7000".

## Requisitions table :
|Rotas|Payload|
|---------------------------------------------|-------------------|
|/v1/performance/sales/store/:storeNumber?period=param|Vendas montly/daily.|
|/v1/performance/sales/store/:storeNumber/allSections |Vendas de todas as seções/dia. |
|/v1/performance/sales/store/:storeNumber/section/:sectionNumber?period=param| Vendas monthly/daily de seção especifica.|
|v1/performance/sales/store/:storeNumber/subsection/:subsectionNumber?period=monthly|Vendas monthly/daily de subseção especifica.|
|/v1/performance/sales/store/:storeNumber/humanResource/employee/:ldap|Colaborador especifico.|
|/v1/performance/sales/store/:storeNumber/advisors/:sectionNumber|Assessores/seção especifica|
|/v1/performance/sales/store/:storeNumber/advisor/:ldap?period=param|Vendas assessores/seção especifica monthly/daily|

### Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas nas seguintes tarefas:

- [X] Adicionar Funcionalidades
- [ ] Melhoria de UI/UX
- [ ] Melhoria de performance 
- [ ] Atualizações e expansão 

## 💻 Pré-requisitos

Npm instalado.

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

[⬆ Voltar ao topo](https://github.com/RenanOliveira20/fake-api/blob/main/README.md)<br>