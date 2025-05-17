# Projeto de Sugestão Alimentar Inteligente - Imersão IA Alura & Google Gemini

## 🚀 Sobre o Projeto

Este projeto inovador, desenvolvido durante a 3ª edição da Imersão IA da Alura em parceria com o Google Gemini, oferece uma solução inteligente para otimizar suas escolhas alimentares. Ao fornecer uma lista de alimentos e um objetivo específico (como **perder peso** ou **economizar na compra**), o sistema gera um relatório personalizado com sugestões de substituições alimentares baseadas em dados atualizados de inflação e informações nutricionais relevantes.

## ✨ Funcionalidades e Casos de Uso

Imagine poder adaptar sua dieta de forma inteligente, economizar nas compras do supermercado ou até mesmo auxiliar um restaurante na atualização estratégica do cardápio. Este projeto torna isso possível através das seguintes funcionalidades:

* **Substituições Inteligentes:** Receba sugestões de alimentos alternativos para os itens da sua lista.
* **Otimização por Objetivo:** As substituições são personalizadas de acordo com o seu objetivo:
    * **Economia:** Prioriza alimentos mais acessíveis financeiramente, considerando a inflação atual.
    * **Saúde:** Sugere opções nutricionalmente mais vantajosas.
* **Relatórios Detalhados:** Apresenta as justificativas para cada substituição, incluindo dados de inflação e informações nutricionais.
* **Visualmente Atraente:** O relatório é enriquecido com uma imagem gerada pelo Gemini, tornando a informação mais agradável e intuitiva.

## 🧠 Como o Relatório é Gerado

O sistema utiliza uma arquitetura inteligente com múltiplos agentes orquestrados pelo poder do Google Gemini:

1.  **Coleta de Dados de Inflação:** Através da ferramenta de consulta do Google, o Gemini busca os valores mais recentes da inflação dos alimentos.
2.  **Análise Econômica:** Um agente especializado em economia identifica alimentos mais baratos que podem substituir os itens da lista com maior inflação.
3.  **Avaliação Nutricional:** Um agente nutricionista analisa o perfil nutricional dos alimentos, sugerindo opções mais saudáveis para as substituições.
4.  **Geração do Relatório:** Um agente final consolida todas as informações coletadas e gera um relatório textual claro e informativo.
5.  **Geração de Imagem:** O Gemini também é utilizado para criar uma imagem relevante dos alimentos, enriquecendo visualmente o relatório.

## ⚙️ Como Executar o Projeto

Você pode experimentar este projeto facilmente utilizando o Google Colab. Basta seguir estes passos:

1.  Acesse [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1XlzJViDfsUsDATgXVjpD6tDBVfgWzGlQ?usp=sharing).
2.  Faça o upload do notebook do projeto (se disponível) ou crie um novo.
3.  Insira sua **API Key do Google AI Studio** no local indicado no código.
4.  Execute as células do notebook para interagir com o sistema.

## 📄 Exemplo de Relatório
![image](https://github.com/user-attachments/assets/de6c74e4-bcee-45e0-a88a-f794e06f337d)


Aqui estão os textos detalhados para cada alimento, considerando a inflação, substituições econômicas e opções mais saudáveis para ganho de peso:

**1. Pão**

*   **Descrição:** O pão é um alimento básico, geralmente feito de farinha, água e fermento, consumido em diversas culturas como acompanhamento ou base para sanduíches.
*   **Inflação e Substituição Econômica:** Embora não haja dados específicos de inflação para o pão, a inflação geral de alimentos e bebidas em Abril/2025 foi de 0,82%, com um acumulado de 5,53% nos últimos 12 meses. Uma alternativa mais econômica é a tapioca, que pode gerar uma economia de 15-20%.
*   **Substituição Saudável:** Para um ganho de peso mais saudável, a aveia em flocos é uma excelente opção. Rica em carboidratos complexos e fibras, oferece um bom aporte calórico e pode ser facilmente adicionada a diversas refeições como frutas, iogurtes ou mingaus.

**2. Ovo**

*   **Descrição:** O ovo é um alimento nutritivo, rico em proteínas e gorduras essenciais, utilizado em inúmeras preparações culinárias.
*   **Inflação e Substituição Econômica:** Similar ao pão, não há dados específicos de inflação para o ovo, mas podemos considerar a inflação geral de alimentos e bebidas. A proteína de soja texturizada (PTS) surge como uma alternativa econômica, com uma economia estimada de 25-30%.
*   **Substituição Saudável:** O amendoim e a pasta de amendoim são substituições saudáveis e eficazes para ganho de peso. São ricos em calorias, proteínas e gorduras saudáveis, fáceis de consumir e versáteis para incluir na dieta.

**3. Frango**

*   **Descrição:** O frango é uma carne branca magra, rica em proteínas, amplamente consumida por ser uma opção acessível e versátil.
*   **Inflação e Substituição Econômica:** Sem dados inflacionários específicos, utiliza-se a inflação geral de alimentos. A sardinha enlatada é uma alternativa mais barata, com uma economia estimada de 20-25%.
*   **Substituição Saudável:** O salmão, embora mais caro, é uma excelente fonte de proteína e gorduras ômega 3, promovendo o ganho de massa muscular e fornecendo energia de alta qualidade.

**4. Batata**

*   **Descrição:** A batata é um tubérculo rico em carboidratos, amplamente utilizado como fonte de energia em diversas dietas.
*   **Inflação e Substituição Econômica:** A batata-inglesa teve uma inflação mensal significativa de 18,29% em Abril/2025. A mandioca se apresenta como uma alternativa mais econômica, com uma economia potencial de 30-35%.
*   **Substituição Saudável:** A batata doce é uma excelente opção para substituir a batata-inglesa, especialmente para quem busca ganho de peso saudável. É um carboidrato complexo de baixo índice glicêmico, fornecendo energia de forma gradual e rica em fibras e vitaminas.
