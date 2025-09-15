MauiAppMinhasCompras - Agenda 6
Repositório do aplicativo de controle de compras desenvolvido para a Agenda 06 da disciplina Desenvolvimento de Sistemas III do curso Técnico em Desenvolvimento de Sistemas.

Este projeto consiste em um aplicativo multiplataforma para cadastro e gerenciamento de uma lista de compras, aplicando conceitos de persistência de dados local, interface de usuário moderna e manipulação de listas dinâmicas.

🎯 Objetivo do Projeto
O objetivo principal desta atividade era desenvolver um aplicativo CRUD (Criar, Ler, Atualizar, Deletar) funcional utilizando .NET MAUI. O sistema deveria permitir ao usuário gerenciar uma lista de produtos, armazenando os dados localmente para que as informações não se perdessem ao fechar o aplicativo.

✨ Recursos Implementados (Requisitos da Agenda)
Para atender aos requisitos da atividade, as seguintes funcionalidades e tecnologias foram implementadas:

✅ Entrada de Dados: Utilização de componentes Entry para a inserção de nome, quantidade, preço e categoria do produto.

✅ Listagem Dinâmica: Exibição dos produtos cadastrados em uma CollectionView, que se atualiza automaticamente.

✅ Layout Moderno: A interface foi construída com Frames, cores e sombras para criar um visual limpo, agradável e polido.

✅ Design Responsivo: A interface se adapta a diferentes tamanhos de tela, garantindo a compatibilidade com dispositivos Android, iOS e Windows.

✅ Persistência de Dados com SQLite: Implementação de um banco de dados SQLite para armazenar, consultar, atualizar e deletar os produtos de forma local no dispositivo.

✅ Ações de Contexto: Uso de ContextActions na ListView para permitir que o usuário edite e remova itens da lista com um simples gesto (arrastar ou clique longo).

✅ Confirmação de Ações: Utilização de DisplayAlert para solicitar a confirmação do usuário antes de excluir um item, evitando remoções acidentais.

✅ Navegação para Edição: Implementação do evento ItemSelected para navegar para uma nova tela (ou modificar a tela atual) com os dados do item selecionado, permitindo sua edição.

✅ Atualização da Lista: Adicionado o recurso de "Puxar para Atualizar" (Pull to Refresh) para recarregar a lista de produtos do banco de dados.

✅ Filtros e Relatórios:

Filtro por Categoria: Adicionado um componente Picker para que o usuário possa filtrar e visualizar produtos de uma categoria específica.

Relatório de Gastos: Criação de uma funcionalidade que calcula e exibe o total gasto em cada categoria, oferecendo um resumo financeiro inteligente.

🛠️ Tecnologias Utilizadas
Tecnologia	Finalidade
.NET MAUI	Framework principal para o desenvolvimento do aplicativo multiplataforma.
C#	Linguagem de programação utilizada para toda a lógica do aplicativo, regras de negócio e acesso aos dados.
XAML	Linguagem de marcação para a construção declarativa da interface do usuário e do layout das telas.
SQLite	Sistema de banco de dados leve e embarcado, utilizado para a persistência dos dados localmente no dispositivo.

