## 🎯 Desafio Técnico: Sistema de Cadastro de Unidades de Medida
> Desenvolver uma interface intuitiva e responsiva para o cadastro de unidades de medida, garantindo uma excelente experiência de usuário.

---

**Tecnologias:**  
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?logo=vue.js&logoColor=white) ![Pinia](https://img.shields.io/badge/-Pinia-FFD02F?logo=vue.js&logoColor=white) ![Quasar](https://img.shields.io/badge/-Quasar-1976D2?logo=quasar&logoColor=white)

## ⚙️ Stack Técnica Esperada

**Conhecimentos obrigatorios**  
- [x] HTML5
- [x] CSS3
- [x] Javascript
- [x] Logica de programação
- [x] Raciocinio lógico 

**Diferenciais 🛠️**  
- [x] Node.js
- [x] Sequelize ORM
- [x] PostgreSQL
- [x] AWS  
- [x] Git
- [x] GitHub
- [x] Linux
- [x] Vue.js
- [x] Quasar Framework
- [x] Pinia (State Management)

## 🏆 Critérios de Avaliação

| Categoria          | Detalhes                                  |
|--------------------|-------------------------------------------|
| **Interface**      | Responsividade • UX intuitiva             |
| **Código**         | Clean Code • Componentização              |
| **Estado**         | Uso eficiente do Pinia para gerenciamento |
| **Extras**         | Testes                                    |


## 📋 Especificações Técnicas

### Tabela de Unidades de Medida

| Campo           | Regras                                      | Validações                    |
|-----------------|---------------------------------------------|-------------------------------|
| **id**          | Id • Imutável auto increment                | Gerado automaticamente        |
| **codigo_erp**  | Único • 5 caracteres (opcional)             | Regex: `^[A-Z0-9]{0,5}$`     |
| **sigla**       | Única • Obrigatória • 3 chars               | Exemplo: `KG`, `LTS`          |
| **descrição**   | Obrigatória • 100 caracteres                | Capitalizada                  |
| **status**      | Boolean (`true`=ativo)                      | Filtro automático quando `false` |



## 🖼️ Protótipos de Referência

| Tela Principal                  |
|---------------------------------|
| ![Listagem](https://github.com/user-attachments/assets/44b0d748-8015-4dfe-852c-067cb346af7a) |

| Modal de Cadastro               |
|---------------------------------|
| ![Cadastro](https://github.com/user-attachments/assets/ef33e15a-c2ca-4283-ab36-ae2157369cc4) |


## 💡 Dicas Valiosas

1. Use **Pinia** para gerenciar o estado global das unidades
2. Implemente **validações em tempo real** nos formulários
3. Componentize ao máximo para reutilização de código

## 📩 Processo de Revisão

- Implementação dos requisitos obrigatórios
- Organização do código
- Tratamento de edge cases
- Experiência do usuário

## 🚀 Submissão 
1. **Fork do Repositório**
2. **Realize suas modificações**
3. **Abra um Pull Request (PR)**

## ❓ Dúvidas ou Suporte

Se você tiver dúvidas ou precisar de ajuda, sinta-se à vontade para entrar em contato com nosso time ou abrindo uma issue marcando @GrupoRaotes/webgr-head.
