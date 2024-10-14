# Vaga para Desenvolvedor Front-End

## Introdução
Estamos à procura de um Desenvolvedor Front-End talentoso para se juntar à nossa equipe. Se você é apaixonado por criar interfaces de usuário incríveis e tem experiência com o Quasar Framework, queremos ouvir de você!

## Desafio:
O objetivo principal é realizar uma tela onde irá acontecer o cadastro de uma unidade de medida.
> Bonûs, utilizar o [Pinia](https://pinia.vuejs.org/) (gerenciador de estado global) para armazenar os dados, ele já está incluso no projeto.

## Qualificações Necessárias
- Proficiência em HTML, CSS e JavaScript.
- Capacidade de criar interfaces de usuário responsivas e amigáveis.
- Familiaridade com ferramentas de versionamento de código, como Git.
- Vontade de aprender e pesquisas novas técnologias.

## Responsabilidades
- Desenvolver e manter interfaces de usuário utilizando o Quasar Framework.
- Garantir a qualidade do código através de revisões e testes.
- Participar de reuniões de equipe e contribuir com ideias para melhorar o produto.

## Desejavel
- Conhecimento com o Quasar Framework.
- Conhecimento em Vue.js.

## Sobre o Projeto
O projeto envolve o desenvolvimento de uma tela principal e modal utilizando o Quasar Framework:
1. **Tela de cadastro**: Inteface mostrando os cadastros.
![image](https://github.com/user-attachments/assets/44b0d748-8015-4dfe-852c-067cb346af7a)

3. **Modal de cadastro**: Modal que será realizado o cadastro.
![image](https://github.com/user-attachments/assets/ef33e15a-c2ca-4283-ab36-ae2157369cc4)

5. **Modal de edição**: Modal que será utilizado para realizar a edição
![image](https://github.com/user-attachments/assets/13b3c111-8eef-4600-b686-11482c7ee9dd)

# Tabela de Unidade de Medida
| Campo       | Descrição                                      | Regras                                                             |
|-------------|------------------------------------------------|--------------------------------------------------------------------|
| id          | Identificador único da unidade de medida       | Unico autoincrement, não é possivel alterar                        |
| codigo_erp  | Código utilizado no sistema ERP                | alfanumerico, tamnho maximo de 5 caracteres não obrigatorio, unico |
| sigla       | Abreviação da unidade de medida                | Caixa alta, unico e obgrigatorio                                   |
| descrição   | Descrição completa da unidade de medida        | Caixa alta, obrigatorio e possivel repetir                         |
| status      | Status da unidade de medida (ativo/inativo)    | Padrão é true, possivel false e quando falso não deve ser listado  |
