# Calculadora de TMB Atlética

Projeto simples de calculadora de Taxa Metabólica Basal (TMB) com estilo escuro e foco em público esportivo.

## Descrição

Esta página fornece cálculo de TMB usando a fórmula de Mifflin-St Jeor.
Ela também calcula o GET (gasto energético total) a partir do nível de atividade selecionado.

## Funcionalidades

- Seleção de sexo biológico (masculino / feminino)
- Entrada de idade, peso e altura
- Escolha do nível de atividade
- Escolha de modalidade esportiva com textos de contexto
- Resultado de TMB e GET com metas calóricas
- Rodapé com links para Matbel Nutrition e GitHub do desenvolvedor

## Como usar

1. Abra `index.html` em um navegador moderno.
2. Preencha os campos de `Idade`, `Peso` e `Altura`.
3. Selecione o nível de atividade e a modalidade principal.
4. Clique em `Calcular TMB`.

## Estrutura do projeto

- `index.html` — página principal com todo o HTML, CSS e JavaScript embutidos
- `logo.jpg` — imagem do logo usada no cabeçalho
- `vercel.json` — configuração de deploy para Vercel

## Deploy

O deploy usa Vercel como hosting estático. A configuração já está pronta em `vercel.json`.

Para forçar um novo deploy, faça push para o branch `main` do repositório GitHub conectado ao Vercel.

## Observações

- O logo é referenciado como `logo.jpg` em minúsculas para funcionar corretamente em ambientes sensíveis a maiúsculas (Vercel/Linux).
- Não há dependências externas além da fonte Google Fonts.
