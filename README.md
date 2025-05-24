    # 💲 SIMULADOR DE INVESTIMENTOS IMOBILIÁRIOS 💲

## 🎯 Objetivo

Este projeto tem como propósito o desenvolvimento de um simulador de investimentos voltado para o mercado de fundos imobiliários, com base em dados fornecidos pelo usuário. O simulador visa responder de forma prática e analítica a perguntas cruciais no processo de tomada de decisão de investimentos, tais como:

- Valor e período do investimento;
- Taxa de rendimento esperada;
- Estimativas de patrimônio acumulado ao longo do tempo;
- Projeção de dividendos mensais;
- Simulação de cenários futuros;
- Adequação ao perfil de investidor;
- Sugestões de alocação de aportes mensais.

## 📚 Metodologia

O simulador foi desenvolvido utilizando recursos do Microsoft Excel, explorando funcionalidades como:

- Fórmulas financeiras e lógicas;
- Tabelas e nomeação de intervalos;
- Validação de dados para controle de entradas;
- Automação de cenários com base em parâmetros ajustáveis.

A ferramenta permite simulações robustas e adaptáveis a diferentes perfis de investimento, fornecendo insights que podem apoiar tanto investidores individuais quanto profissionais da área financeira.

## 🧱 Estrutura do Arquivo

A pasta de trabalho é composta por duas planilhas principais:

- **Invest.me**:  
  Planilha central do simulador, composta por seções para entrada de dados, definição de perfil de investidor e exibição de resultados simulados (projeções de patrimônio, dividendos e gráficos comparativos).

- **Apoio**:  
  Planilha auxiliar que contém tabelas de referência, como a matriz de perfis de investidor e suas respectivas sugestões de alocação de investimentos. Essa estrutura é fundamental para o funcionamento dinâmico e personalizado da planilha principal.


## 📈 Exemplo de Uso

### Cenário Simulado: Investidor Conservador com Foco em Renda Passiva

**Perfil do Investidor:** Conservador  
**Salário Mensal:** R$ 7.000  
**Aporte Mensal Disponível para Investimento:** R$ 1.200  
**Horizonte de Investimento:** 10 anos  
**Rentabilidade Esperada (média anual):** 9% a.a.  
**Reinvestimento de Dividendos:** Sim

Com base nos dados informados, o simulador realiza os seguintes cálculos e projeções:

- **Distribuição do Aporte Mensal:**
  - 30% em FIIs de papel (maior previsibilidade de renda)
  - 50% em FIIs de tijolo (potencial de valorização de patrimônio)
  - 10% em FIIS Híbridos (combinação equilibrada dos fatores acima)
  - 10% em FOFs (variedade de investimentos)

- **Patrimônio Acumulado ao final de 10 anos:**  
  Aproximadamente **R$ 510.896,85**, considerando reinvestimentos e efeito de juros compostos.

- **Renda Passiva Mensal Estimada ao final do período:**  
  Cerca de **R$ 3.831,75** em dividendos mensais isentos de imposto de renda, proporcionados pelos FIIs.

- **Benefícios adicionais estimados:**
  - Potencial de antecipar a liberdade financeira com reinvestimentos consistentes.
  - Proteção contra inflação, dado o foco em ativos indexados.

### Conclusão do Cenário

Este exemplo demonstra que, mesmo com aportes mensais relativamente modestos, a consistência e o direcionamento adequado conforme o perfil de risco podem gerar resultados expressivos no longo prazo. O simulador permite ao investidor visualizar esses cenários de forma personalizada, promovendo uma gestão estratégica de seus recursos.

---
>[!ATENÇÃO]
>**Nota:** Todos os valores são estimativas e não representam garantias de retorno. As decisões de investimento devem considerar também fatores externos como conjuntura econômica, variações de mercado e legislação vigente.

## 🏢 Tipos de Fundos Imobiliários

Os Fundos de Investimento Imobiliário (FIIs) são veículos coletivos que possibilitam o investimento em ativos ligados ao setor imobiliário, oferecendo ao investidor a oportunidade de receber renda passiva e participar da valorização de imóveis sem necessidade de aquisição direta. Abaixo estão os principais tipos de FIIs presentes no mercado brasileiro:

### 📄 Fundos de Papel

Também conhecidos como **FIIs de recebíveis**, investem majoritariamente em ativos financeiros lastreados no setor imobiliário, como **Certificados de Recebíveis Imobiliários (CRIs)** e **Letras de Crédito Imobiliário (LCIs)**.  
- **Objetivo:** geração de renda previsível e regular.  
- **Risco:** menor volatilidade, mas expostos a riscos de crédito e inflação.  
- **Perfil indicado:** conservador ou moderado.

### 🧱 Fundos de Tijolo

Investem diretamente em **imóveis físicos** com fins de exploração comercial ou locação, como shopping centers, galpões logísticos, hospitais, lajes corporativas e agências bancárias.  
- **Objetivo:** renda por aluguel e valorização dos imóveis.  
- **Risco:** sujeitos à vacância e à desvalorização do imóvel.  
- **Perfil indicado:** moderado a agressivo.

### ⚙️ Fundos Híbridos

Possuem **estratégia diversificada**, investindo simultaneamente em ativos físicos (tijolo) e financeiros (papel).  
- **Objetivo:** combinar estabilidade de renda com potencial de valorização.  
- **Risco:** depende da alocação interna; tende a ser balanceado.  
- **Perfil indicado:** investidores com perfil moderado.

### 🧳 Fundos FOFs (Fund of Funds)

São fundos que investem **em cotas de outros FIIs**, atuando como uma carteira diversificada dentro do próprio segmento.  
- **Objetivo:** diversificação e gestão profissional.  
- **Risco:** podem ter maiores taxas de administração; dependem da performance dos fundos investidos.  
- **Perfil indicado:** iniciantes ou investidores que buscam diversificação com menor esforço.

### 🏗️ Fundos de Desenvolvimento

Investem em **projetos imobiliários em construção ou incorporação**, com o objetivo de lucrar com a venda dos imóveis após sua conclusão.  
- **Objetivo:** valorização do capital.  
- **Risco:** alto, por conta de atrasos, variações de custo e risco de mercado.  
- **Perfil indicado:** agressivo, com foco em longo prazo.

### 🏨 Fundos de Hotelaria

Investem em **empreendimentos hoteleiros**, com a receita atrelada à performance da operação dos hotéis.  
- **Objetivo:** participação nos lucros da atividade hoteleira.  
- **Risco:** alta sensibilidade à sazonalidade e ao turismo.  
- **Perfil indicado:** agressivo, com tolerância a volatilidade.

### 🔍 Fontes utilizadas

- B3 – Bolsa de Valores do Brasil: [https://www.b3.com.br](https://www.b3.com.br)
- CVM – Comissão de Valores Mobiliários: [https://www.gov.br/cvm](https://www.gov.br/cvm)
- Clube FII: [https://www.clubefii.com.br](https://www.clubefii.com.br)
- XP Investimentos – "Guia dos Fundos Imobiliários", 2023.
- Suno Research – "Tipos de FIIs: conheça os principais e suas características", 2024.

## ⚠️ Limitações e Possíveis Expansões

### 🔻 Limitações Atuais

Embora o simulador atenda a uma ampla gama de usuários e ofereça projeções úteis, algumas limitações devem ser consideradas:

- **Premissas fixas de rentabilidade:**  
  A taxa de rendimento utilizada nas simulações é estática, o que não reflete a volatilidade real do mercado de fundos imobiliários.

- **Ausência de tributação detalhada:**  
  O simulador assume isenção de IR sobre dividendos de FIIs, conforme a regra vigente. No entanto, não contempla possíveis cenários de mudanças fiscais ou incidência de imposto sobre ganhos de capital.

- **Falta de dados históricos:**  
  A ferramenta não utiliza séries históricas de FIIs, o que limitaria análises baseadas em performance passada ou variações de mercado.

- **Distribuição baseada em perfis genéricos:**  
  O modelo de alocação utiliza perfis padronizados (conservador, moderado e agressivo), o que pode não refletir todas as nuances comportamentais e objetivos específicos de cada investidor.

- **Interface técnica:**  
  Apesar de intuitiva, a ferramenta ainda exige certo domínio básico do Excel, o que pode limitar o uso por parte de iniciantes absolutos.

### 🚀 Possíveis Expansões Futuras

Para tornar o simulador mais robusto e versátil, as seguintes melhorias estão sendo consideradas:

- **Simulação de cenários econômicos dinâmicos:**  
  Permitir que o usuário selecione diferentes cenários macroeconômicos (inflação, Selic, risco-país) para impactar a projeção de resultados.

- **Integração com dados externos (via Power Query ou VBA):**  
  Automatizar a coleta de preços de cotas, indicadores de FIIs e dividend yields, aumentando a precisão e atualidade das simulações.

- **Cálculo de imposto sobre ganho de capital:**  
  Incluir uma aba para controle e simulação da venda de cotas, com cálculo automático de IR conforme regras da Receita Federal.

- **Painel interativo com gráficos de comparação entre tipos de FIIs:**  
  Tornar as análises visuais mais completas, com dashboards comparativos que ajudem na tomada de decisão.

- **Perfil personalizado de investidor:**  
  Substituir o modelo de perfil genérico por um questionário que defina automaticamente o perfil com base em parâmetros comportamentais e objetivos financeiros.

- **Versão Web (em Python ou Power BI):**  
  Expandir o simulador para uma interface web, permitindo acessibilidade multiplataforma e maior escalabilidade da ferramenta.
