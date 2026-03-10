# Miniguia de Estudos: Benjamin Graham e o Investimento em Valor

Este repositório foi criado como parte do Desafio da DIO em parceria com a Riachuelo (BOOTCAMP CiberSegurança).  
O objetivo é organizar um caderno temático sobre Benjamin Graham, considerado o pai do investimento em valor, explorando seus princípios, critérios e metáforas que ajudam investidores a tomar decisões racionais e seguras.

## Contexto e Objetivos
- Entender a filosofia de Benjamin Graham e sua aplicação prática no mercado financeiro.  
- Diferenciar investimento de especulação.  
- Explorar os perfis de investidor defensivo e empreendedor.  
- Consolidar critérios objetivos para seleção de ações.  
- Criar um guia de prompts reutilizáveis para revisões futuras.

## Curadoria de Fontes
As 10 fontes utilizadas no NotebookLM exploram:
- Filosofia do investimento em valor.  
- Estratégias de cálculo do valor intrínseco.  
- Critérios de Graham para investidores defensivos.  
- Metáfora do "Sr. Mercado" e sua aplicação prática.  
- Importância da margem de segurança e dos dividendos consistentes.  

## Engenharia de Prompts e "Cicatrizes"
Exemplos de perguntas estratégicas testadas:
- **Quais são os 7 critérios de Graham para investidores defensivos?**  
- **Como o conceito de 'Sr. Mercado' ajuda a lidar com a volatilidade?**  
- **Como calcular o valor intrínseco de uma ação usando a fórmula de Graham?**  
- **Qual a diferença entre investidor defensivo e empreendedor?**  
- **Quais são os principais pilares da metodologia de Graham?**

### Dificuldades encontradas:
- Respostas iniciais muito genéricas → solução: adicionar contexto sobre perfil do investidor.  
- Fórmula de Graham exigiu detalhamento matemático → solução: pedir exemplos numéricos.  
- Metáfora do "Sr. Mercado" → precisou de explicação prática com cenários reais.

### Resumos Estruturados
- **Investimento vs. Especulação**: Investimento exige análise profunda, segurança do capital e retorno satisfatório; especulação busca apenas ganhos rápidos com flutuações de preço.  
- **Margem de Segurança**: Comprar ativos abaixo do valor intrínseco para proteger contra incertezas.  
- **Sr. Mercado**: Metáfora que ilustra a irracionalidade das oscilações de preço; o investidor inteligente aproveita o pessimismo para comprar barato.  
- **Perfis de Investidor**:  
  - Defensivo - busca estabilidade, baixo risco e empresas consolidadas.  
  - Empreendedor - dedica tempo à análise detalhada para encontrar oportunidades subvalorizadas.  
- **Fórmula de Graham para Valor Intrínseco**:  
  \[
  Valor\ Intrínseco = \sqrt{22,5 \times LPA \times VPA}
  \]  
  Onde LPA = Lucro por Ação e VPA = Valor Patrimonial por Ação.

### Glossário
- **Valor Intrínseco**: Estimativa do valor real de uma ação com base em fundamentos.  
- **Margem de Segurança**: Diferença entre preço pago e valor intrínseco.  
- **Número de Graham**: Fórmula usada para calcular o valor justo de uma ação.  
- **Liquidez Corrente**: Capacidade da empresa de pagar dívidas de curto prazo.  
- **Dividendos**: Parte dos lucros distribuída aos acionistas.

### Prompts Reutilizáveis
- *"Liste os 7 critérios de Graham para investidores defensivos."*  
- *"Explique a metáfora do Sr. Mercado com exemplos práticos."*  
- *"Calcule o valor intrínseco de uma ação com LPA = 5 e VPA = 20."*  
- *"Compare os perfis de investidor defensivo e empreendedor."*  
- *"Resuma os pilares da metodologia de Graham em tópicos."*

Exemplo de Cálculo do Valor Intrínseco (Número de Graham)
Benjamin Graham propôs uma fórmula para estimar o valor justo de uma ação:
Valor\  Intrínseco=\sqrt{22,5\times LPA\times VPA}
- LPA (Lucro por Ação): Lucro líquido dividido pelo número de ações.
- VPA (Valor Patrimonial por Ação): Patrimônio líquido dividido pelo número de ações.
- O fator 22,5 vem da regra de Graham: P/L ≤ 15 e P/VPA ≤ 1,5 → 15 × 1,5 = 22,5.

Exemplo Numérico
Suponha uma empresa com os seguintes dados:
- LPA = 5
- VPA = 20
Aplicando a fórmula:
Valor\  Intrínseco=\sqrt{22,5\times 5\times 20}
Valor\  Intrínseco=\sqrt{2250}
Valor\  Intrínseco\approx 47,43

Interpretação
- Se o preço atual da ação for R$ 30, ela está subvalorizada (abaixo do valor intrínseco).
- Se o preço atual for R$ 60, ela está sobrevalorizada (acima do valor intrínseco).
- O investidor defensivo buscaria comprar apenas quando o preço de mercado estiver bem abaixo do valor intrínseco, garantindo a margem de segurança.
