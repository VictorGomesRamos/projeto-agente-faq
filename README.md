# Assistente de FAQ: prazos de entrega

Projeto de estudo que simula uma demanda de negócio: o time de atendimento
quer um assistente de IA que responda dúvidas sobre prazos de entrega e atrasos.

## O que foi feito
1. **Coleta:** dataset público de e-commerce brasileiro (Olist, no Kaggle).
2. **Limpeza (Python/pandas):** conversão de datas, verificação de duplicados,
   tratamento de pedidos não entregues, cruzamento de tabelas e análise de valores extremos.
3. **Indicadores:** prazo médio e % de atraso por estado.
4. **Base de conhecimento:** documento gerado a partir dos resultados.
5. **Agente de IA:** criado no Microsoft Copilot Studio, com instruções e base de conhecimento.
6. **Testes:** 15 perguntas (dentro do escopo, fora do escopo e armadilhas).
7. **Documentação:** objetivo, dados, limitações e riscos.

## Resultados
- Pedidos analisados: 96470
- Prazo médio geral: 10 dias
- Percentual de atraso geral: 8,1%

## Arquivos
- `analise_prazos_entrega.ipynb`: limpeza e análise em Python
- `base_conhecimento.pdf`: documento usado pelo agente
- `prints/`: imagens do agente e dos gráficos

## Dados
Fonte: [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).
Os arquivos originais não estão neste repositório. Baixe-os no link acima.

## Limitações
Dados estáticos e de exemplo, sem conexão com sistemas em tempo real e sem
consulta a pedidos individuais ou dados pessoais.

## Ferramentas
Python, pandas, Google Colab, Microsoft Copilot Studio.
