🎯 Otimização de Campanhas Publicitárias Digitais - Empresa MYK

📚 Descrição do Projeto

Este projeto foi desenvolvido com o objetivo de analisar e otimizar o desempenho das campanhas publicitárias digitais da empresa MYK , utilizando técnicas avançadas de ciência de dados e machine learning. A iniciativa busca maximizar o ROI (Retorno sobre Investimento) das campanhas publicitárias e direcionar estratégias de anúncios de forma mais eficiente.

🎯 Objetivos Principais

Identificar os principais fatores que influenciam o comportamento de clique em anúncios.
Otimizar o direcionamento de campanhas com base em características demográficas e comportamentais.
Desenvolver um modelo preditivo para estimar a probabilidade de conversão.
Segmentar a base de usuários para personalização de estratégias de marketing.
Quantificar o impacto financeiro das otimizações propostas.

📊 Questões Chave de Negócio

O projeto aborda as seguintes questões críticas:

Perfil Etário e Conversão : Qual a relação entre a idade do usuário e a probabilidade de clicar em anúncios?
Engajamento e Conversão : Como o tempo diário gasto no site influencia as taxas de clique?
Impacto Socioeconômico : De que forma o nível de renda média da região do consumidor afeta a probabilidade de clique?
Comportamento Digital : Qual a relação entre o tempo médio diário de uso da internet e a probabilidade de conversão?
Segmentação Estratégica : Como podemos usar padrões de uso da internet e tempo no site para criar segmentos de usuários com maior probabilidade de conversão?

🔧 Metodologia

1. Análise Exploratória de Dados (EDA)
Foram realizadas análises descritivas e visualizações para entender a distribuição das variáveis, como:
Tempo gasto no site (Daily Time Spent on Site)
Idade (Age)
Renda média da região (Area Income)
Uso diário da internet (Daily Internet Usage)
Análise de palavras-chave nos tópicos de anúncios (Ad Topic Line) e sua relação com cliques.
2. Modelagem Preditiva
Foi utilizado um modelo de Regressão Logística para prever a probabilidade de cliques em anúncios.
Variáveis numéricas foram padronizadas e variáveis categóricas foram codificadas usando One-Hot Encoding .
O modelo foi avaliado com métricas como:
AUC-ROC
Precisão
Recall
3. Sistema de Scoring
Implementado um sistema de scoring para priorizar campanhas para públicos com maior probabilidade de conversão.
📈 Resultados Principais
Variáveis Mais Relevantes :
Idade (Age) : Impacto positivo na probabilidade de clique.
Uso Diário da Internet (Daily Internet Usage) : Impacto negativo.
Renda Média (Area Income) : Impacto negativo.
Tópicos de Anúncios : Alguns tópicos específicos, como "Synergized cohesive array", apresentaram maior taxa de cliques.
Ganhos Financeiros Potenciais :
Redução de custos com anúncios ineficazes: R$30.000/ano .
Aumento na taxa de conversão: R$100.000/ano .
Otimização do ROI: R$70.000/ano .
Acurácia do Modelo :
Acurácia geral: 96% .
AUC-ROC: 0.988 .
🛠️ Como Executar o Projeto
Pré-requisitos
Python 3.x
Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn, wordcloud, pycountry_convert
Instale as dependências com o comando:

bash
Copiar
1
pip install pandas numpy matplotlib seaborn scikit-learn wordcloud pycountry_convert
Estrutura do Projeto
Copiar
1
2
3
4
5
├── advertising.csv          # Dataset principal
├── main.py                  # Código principal para análise e modelagem
├── Plano_Estrategico_5W2H.pdf # Resumo do plano estratégico
├── Ganhos_Financeiros_Potenciais.pdf # Resumo dos ganhos financeiros
└── Scrum_Projeto_Scoring.pdf # Detalhes do Scrum do projeto
Execução
Clone este repositório:
bash
Copiar
1
git clone https://github.com/seu-usuario/nome-do-repositorio.git
Navegue até o diretório do projeto:
bash
Copiar
1
cd nome-do-repositorio
Execute o script principal:
bash
Copiar
1
python main.py
📄 Documentação Adicional
Plano Estratégico (5W2H) : Disponível em Plano_Estrategico_5W2H.pdf.
Ganhos Financeiros Potenciais : Disponível em Ganhos_Financeiros_Potenciais.pdf.
Scrum do Projeto : Disponível em Scrum_Projeto_Scoring.pdf.
🤝 Contribuições
Contribuições são bem-vindas! Siga os passos abaixo:

Faça um fork deste repositório.
Crie uma branch com sua feature ou correção:
bash
Copiar
1
git checkout -b feature/nova-feature
Envie suas alterações:
bash
Copiar
1
git push origin feature/nova-feature
Abra um Pull Request.
📜 Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.
