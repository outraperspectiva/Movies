 # Aplicativo de Filmes
Este é um projeto de aplicativo para iOS  que permite aos usuários navegar por uma lista de filmes foi desenvolvido por 
Adonay Puszczynski (Adoonay).

## Funcionalidades
   - Visualizar uma lista de filmes em uma coleção.
   - Ver os detalhes de um filme específico.
   - Filtrar filmes por gênero.

## Arquitetura
  O projeto parece seguir o padrão de arquitetura MVVM (Model-View-ViewModel).
   - Model: Os objetos de modelo, como Movie.swift, representam os dados do aplicativo.
   - View: Os componentes de UI, como MoviesListViewController.swift e MovieCell.swift, exibem os dados na tela.
   - ViewModel: Os ViewModels, como MoviesListViewModel.swift, contêm a lógica de apresentação e preparam os dados para a View.

## Estrutura do Projeto
  O código-fonte está organizado da seguinte forma:
   - Movies/Scenes/: Contém as diferentes telas (cenas) do aplicativo, como a lista de filmes.
   - Movies/Commons/: Provavelmente contém código reutilizável e componentes comuns a todo o aplicativo.
   - MovieService.swift: Uma classe de serviço responsável por buscar os dados dos filmes, possivelmente de uma API remota.

## Tecnologias Utilizadas
   - Swift: A linguagem de programação principal.
   - UIKit: O framework da Apple para construir interfaces de usuário para aplicativos iOS.

## Como Executar o Projeto
   1. Abra o arquivo Movies.xcodeproj com o Xcode.
   2. Selecione um simulador de iPhone ou um dispositivo físico como destino.
   3. Clique no botão "Run" (ou pressione Cmd+R) para compilar e executar o aplicativo.
