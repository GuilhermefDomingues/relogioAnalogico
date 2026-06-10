# Relógio Analógico

Projeto desenvolvido com HTML, CSS e JavaScript que reproduz o funcionamento de um relógio analógico em tempo real. Os ponteiros são atualizados automaticamente utilizando a API nativa de datas do JavaScript.

## 🚀 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript

## ✨ Funcionalidades

- Relógio analógico funcional
- Atualização em tempo real
- Ponteiro de segundos
- Ponteiro de minutos
- Ponteiro de horas
- Design moderno
- Animação suave dos ponteiros

## 📂 Estrutura do Projeto

```bash
AnalogClock/
│
├── index.html
│
├── css/
│   └── style.css
│
└── img/
    └── icone.png
```

## 🎯 Como Executar

1. Clone ou baixe o projeto.
2. Abra a pasta do projeto.
3. Execute o arquivo `index.html` no navegador.

## 📚 Conceitos Praticados

- Manipulação de datas com JavaScript
- Objeto Date()
- setInterval()
- Transform Rotate
- Transform Origin
- CSS Position
- Animações visuais
- Atualização dinâmica de elementos

## 💡 Objetivo

Praticar manipulação de tempo utilizando JavaScript e desenvolver componentes visuais interativos que atualizam informações em tempo real.

## ⚙️ Funcionamento

O relógio utiliza o objeto `Date()` para capturar:

- Horas
- Minutos
- Segundos

Em seguida, converte esses valores em graus para rotacionar os ponteiros através da propriedade:

```javascript
transform: rotateZ()
```

criando o efeito de um relógio analógico real.

## 👨‍💻 Autor

Desenvolvido por Guilherme Domingues.
