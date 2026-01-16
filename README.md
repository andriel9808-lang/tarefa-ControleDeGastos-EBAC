# Controle de Gastos Pessoais

Aplicação web desenvolvida para gerenciar gastos pessoais organizados por categorias. O projeto aplica conceitos modernos de JavaScript, incluindo Programação Orientada a Objetos (POO), ES Modules, manipulação do DOM e programação funcional. Projeto desenvolvido como atividade prática do curso da EBAC.

## Funcionalidades

* Adicionar gastos com valor e categoria
* Organizar gastos por categorias (Alimentação, Transporte, Lazer, Outros)
* Visualizar total de gastos por categoria
* Calcular total geral de todos os gastos
* Validação de valores negativos
* Interface responsiva e amigável

## Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript (ES6+)
* ES Modules
* POO (Programação Orientada a Objetos)
* Manipulação do DOM
* Programação Funcional

## Conceitos Aplicados

* **Modularização**: Código organizado em módulos ES6
* **Encapsulamento**: Uso de campos privados (#) nas classes
* **Getters**: Acesso controlado a propriedades privadas
* **Rest Operator**: Parâmetros flexíveis no construtor
* **Funções Puras**: Lógica sem efeitos colaterais
* **Programação Funcional**: Métodos como find() e reduce()
* **Event Handling**: Gerenciamento de eventos do formulário

## Estrutura do Projeto

```
├── index.html
├── styles.css
└── js/
    ├── app.js
    ├── classes.js
    └── utils.js
```

## Descrição dos Arquivos

* **index.html**: Estrutura HTML da aplicação
* **styles.css**: Estilização com design suave e responsivo
* **js/app.js**: Lógica principal e manipulação de eventos
* **js/classes.js**: Classes Categoria e ListaGastosPorCategoria
* **js/utils.js**: Funções utilitárias e atualização da interface

## Como Usar

1. Clone o repositório
2. Abra o arquivo `index.html` no navegador
3. Digite o valor do gasto
4. Selecione a categoria correspondente
5. Clique em "Adicionar"
6. Acompanhe os totais por categoria e o total geral

## Observações

O projeto utiliza ES Modules, portanto é necessário executar a aplicação através de um servidor local ou abrir diretamente no navegador que suporte módulos ES6.