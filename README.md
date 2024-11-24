# Projeto Integrador - Sistema de Gestão Universitária

## Descrição
Este projeto tem como objetivo a construção de um sistema de gestão para uma universidade, onde usuários podem realizar cadastros de **Pessoa Física**, **Pessoa Jurídica**, **Professores**, **Fornecedores** e **Alunos**. O sistema foi modelado utilizando UML e será prototipado através de ferramentas como Figma/Miro.

## Diagramas
Os diagramas de UML, desenvolvidos na primeira parte do projeto, estão incluídos aqui para referência. Esses diagramas representam o fluxo de dados do sistema e as relações entre as diferentes entidades, como:
- **Diagrama de Caso de Uso**
- **Diagrama de Classe**

### Diagrama de Caso de Uso
Para representar a estrutura do sistema, o diagrama de casos de uso inclui cinco funcionalidades principais, correspondentes aos tipos de cadastro. Essas funcionalidades são:
1. **Cadastro de Pessoa Física**
   - O usuário pode cadastrar informações de uma pessoa física, como nome, CPF, endereço e telefone.
2. **Cadastro de Pessoa Jurídica**
   - O usuário pode cadastrar informações de uma empresa, como nome da empresa, CNPJ, endereço e telefone.
3. **Cadastro de Professores**
   - O usuário pode cadastrar informações de professores, como nome, CPF, departamento e titulação.
4. **Cadastro de Fornecedores**
   - O usuário pode cadastrar fornecedores, incluindo informações como nome da empresa fornecedora, CNPJ e ramo de atividade.
5. **Cadastro de Alunos**
   - O usuário pode cadastrar alunos, incluindo dados como nome, CPF, matrícula e curso.

Essas funcionalidades são executadas por um único ator: o **Administrador** do sistema, que tem acesso a todos os cadastros.

### Diagrama de Classe
O sistema inclui a seguinte estrutura de classes:
- **Pessoa Física (Classe Base)**
  - **Atributos**: nome, CPF/CNPJ, endereço, telefone
  - **Métodos**: cadastrar(), editar(), excluir()
- **Aluno (Subclasse de Pessoa)**
  - **Atributos**: matrícula, curso
  - **Métodos**: consultarHistorico(), inscreverCurso()
- **Professor (Subclasse de Pessoa)**
  - **Atributos**: departamento, titulação
  - **Métodos**: cadastroNotas(), editarNotas()
- **Fornecedor (Subclasse de Pessoa Jurídica)**
  - **Atributos**: ramo de atividade, contatos comerciais
  - **Métodos**: cadastrarProduto(), consultarPedido()
- **Pessoa Jurídica (Subclasse de Pessoa)**
  - **Atributos**: CNPJ, razão social
  - **Métodos**: cadastroPJ(), editarPJ()

Para ilustrar as informações citadas acima, segue a imagem mostrando como funcionariam as relações das classes e seus atributos:

![image](https://github.com/user-attachments/assets/5ac14ca6-bec4-48d3-9413-4f03873075e7)

## Contribuidores
- Lucas Alberti Machado
- Sergio Augusto do Espirito Santo
- Alexandre Costa Ribeiro
- Gabriela de Valnisio Ferreira de Andrade
- Pedro Henrique Armelin de Sa
- Bruno Rafael de Mendonça Simas
- João Rafael de Oliveira de Macedo
- Izabel Raridja Santos Guimarães

## Licença
Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
