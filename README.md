# Biblioteca-POO

Sistema Controle e Administração de Biblioteca

Este é um projeto de controle de biblioteca em Java que permite a administração de livros, realização de empréstimos e pesquisas. O projeto utiliza uma interface gráfica desenvolvida com o Swing.

Funcionalidades
Cadastro de livros na biblioteca.
Remoção de livros da biblioteca.
Pesquisa de livros por título.
Listagem de todos os livros na biblioteca.
Listagem de livros em ordem alfabética.
Registro de empréstimos de livros.
Salvamento e carregamento de dados em arquivos.
Estrutura do Projeto
O projeto é dividido em vários pacotes e classes:

controller: Contém as classes que controlam a interface gráfica e a lógica do programa.
emprestimo: Contém a classe EmprestimoDosLivros que modela os empréstimos de livros.
entidades: Contém a classe Livro que representa um livro.
exceptions: Contém exceções personalizadas utilizadas no projeto.
gravador: Contém as classes para salvar e carregar os dados em arquivos.
mapa: Contém a interface SistemaControleDeBiblioteca e sua implementação SistemaControleDeBibliotecaMap.
Como Executar
Para executar o projeto, siga os passos abaixo:

Certifique-se de que você tem o Java Development Kit (JDK) instalado na sua máquina.
Clone ou baixe o repositório para o seu computador.
Abra o projeto em sua IDE Java de escolha.
Execute a classe BibliotecaGUI para iniciar o programa.
Uso do Programa
Na janela principal, você pode usar os botões para acessar as diferentes funcionalidades do programa, como cadastro, pesquisa, operações e salvar os dados.
Você pode cadastrar novos livros, pesquisar livros existentes, realizar operações de empréstimo e salvar os dados em arquivos.
Os dados dos livros e empréstimos são salvos nos arquivos "livros.ser" e "emprestimos.ser".
Ao sair do programa, os dados são carregados automaticamente na próxima execução.
Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) e enviar solicitações de pull (pull requests).

Autores
[Andrei Oliver, Raphael Sammy e Patryck Alphonse] 
Licença
Este projeto é licenciado sob a Licença MIT - consulte o arquivo LICENSE.md para detalhes.
