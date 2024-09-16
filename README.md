#**INTEGRANTES**

98207 - Lucca Rinaldi Valladão de Freitas

98624 - Eduardo Foncesca Finardi

551808 - Ricardo Yuri Gonçalves Domingues

550776 - Angélica Ferreira de Matos Melo

98581 - Matheus Roberto Aparecido de Medeiros Carvalho Pereira de Souza

#**Explicação da arquitetura**

*Monolítica, pois utiliza-se uma abordagem mais simples, além de que existe uma facilidade na manutenção, pois o código esta tudo em um único projeto e também existe uma certa rapidez no desenvolvimento*

#**Desing Patterns utilizados**

- [ ] Repository Pattern

#**Instruções para rodar a API**

## ENDPOINTS

`GET` /cadastro
Listagem de dados necessários para cadastrar o cliente
`CNPJ`
`Nome`
`Logradouro`
`Ramo de atuacao`
`Email`
`Senha`

**Códigos de status**

`200` sucesso

`GET` /cadastro/{id}

Sistema retorna os detalhes do cadastro com o `id` informado.

**Códigos de status**
`200` sucesso

`404` id não encontrado

---



