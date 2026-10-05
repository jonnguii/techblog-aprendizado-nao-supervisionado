# TechBlog - Aprendizado Não Supervisionado

Projeto de blog técnico sobre aprendizado não supervisionado, com foco no algoritmo K-Means e na explicação visual de conceitos de clustering, similaridade e segmentação de dados.

## Autores

- Jean Carlos
- João Guilherme
- Samuel Allan

## Site publicado

- https://techblog-aprendizado-nao-supervisio.vercel.app


## Visão geral

Este projeto foi desenvolvido a partir da ideia de transformar um notebook de apresentação em uma página web técnica, didática e visualmente clara. O objetivo era traduzir conceitos de machine learning para uma linguagem acessível, com uma narrativa em formato de blog e uma identidade visual moderna.

A referência principal do conteúdo foi o notebook `apresentacao_kmeans_final.ipynb`, que contém a explanação sobre K-Means, o método do cotovelo e a importância da padronização dos dados antes do treinamento.

## Quadro de Observação

### 1) Duas páginas de referência analisadas

1. IBM — "Machine Learning"  
   A página foi analisada por sua clareza na explicação conceitual, uso de linguagem acessível e estrutura visual bem organizada. Inspirou a forma como apresentamos o problema do aprendizado não supervisionado em linguagem didática.

2. MLU-Explain / Distill  
   Essas referências foram observadas pela abordagem visual e explicativa de algoritmos de machine learning. Elas influenciaram a organização dos blocos de texto, a lógica de apresentação dos conceitos e a forma como os gráficos e exemplos eram expostos ao leitor.

### 2) Três decisões técnicas e de design adotadas

- Adotamos uma estrutura de blog técnico em múltiplas seções porque o conteúdo precisa ser lido em sequência, com introdução, explicação conceitual, exemplo prático e conclusão.
- Usamos Tailwind CSS e estilos minificados porque isso permite uma interface moderna, consistente e mais leve, com melhor manutenção e desempenho de carregamento.
- Decidimos utilizar uma linguagem menos tecnica e mais parecida com o que usamos no cotidiano. Dessa forma, todo o público-alvo é capaz de entender os conceitos apresentados.

### 3) Uma decisão que não foi adotada

- Não adotamos uma abordagem com animações pesadas, vídeo background ou múltiplos elementos gráficos em movimento. Essa escolha foi feita para manter o foco no conteúdo técnico e evitar prejuízo na performance, legibilidade e acessibilidade da página.

## Como rodar localmente

### Opção 1: abrir diretamente no navegador

Basta abrir o arquivo `index.html` em qualquer navegador moderno.

### Opção 2: servir localmente via Python

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000/
```

## Estrutura do projeto

```text
.
├── index.html
├── css/
│   ├── style.css
│   └── tailwind.min.css
├── img/
│   └── ai-svgrepo-com.svg
├── apresentacao_kmeans_final.ipynb
├── README.md
├── LICENSE
└── tailwind.config.js
```

## Avaliação de desempenho (Lighthouse)

O projeto foi auditado com a ferramenta oficial Google Lighthouse, alcançando nota máxima em vários critérios. A avaliação reforça que as otimizações aplicadas na página tiveram impacto positivo na qualidade geral do site.

| Métrica | Pontuação | Status |
| :--- | :---: | :---: |
| Performance | 99 / 100 | 🟢 Excelente |
| Acessibilidade | 100 / 100 | 🟢 Excelente |
| Boas Práticas | 100 / 100 | 🟢 Excelente |
| SEO | 100 / 100 | 🟢 Excelente |

Esses resultados refletem decisões como a redução de CSS e scripts desnecessários, uso de carregamento diferido, otimização visual e manutenção de uma estrutura semântica acessível para leitura e navegação.

## Créditos

- Conteúdo e estrutura inspirados no notebook de apresentação sobre aprendizado não supervisionado.
- Design e desenvolvimento da página web em HTML + Tailwind CSS.
- Simulação e explicação conceitual baseadas no algoritmo K-Means.
- Agradecimentos à comunidade de pesquisa e documentação de aprendizado de máquina, especialmente às referências consultadas em IBM, Distill, MLU-Explain e materiais do scikit-learn.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.
