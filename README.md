# 📈 Simulador de Investimentos em Fundos Imobiliários (FIIs)

Desafio de projeto desenvolvido para a plataforma **DIO (Digital Innovation One)**, aplicando conceitos de Excel para modelagem financeira e automação de simulações de investimentos.

## 🎯 Objetivo do Projeto
O objetivo deste laboratório foi aplicar ferramentas e fórmulas do Excel para construir um simulador prático focado em Fundos Imobiliários. A ferramenta auxilia investidores a visualizarem o "efeito bola de neve" (reinvestimento de dividendos), permitindo prever o patrimônio acumulado e a renda passiva gerada ao longo do tempo através de variáveis customizáveis.

## 🧠 Lógica de Negócio e Fórmulas Aplicadas

A planilha simula o acúmulo de capital através de juros compostos e faz a alocação de ativos baseada no perfil do investidor. Abaixo estão as principais lógicas aplicadas:

### 1. Projeção de Patrimônio (Cenários)
O cálculo do patrimônio acumulado ao longo dos anos utiliza a fórmula de juros compostos para aportes sistemáticos através da função **VF (Valor Futuro)** do Excel:
- **Fórmula aplicada:** `=VF(C$19, Período_em_Meses, -C$17)`
- **Resultado obtido em 5 anos:** \$16.755,38.

### 2. Estimativa de Dividendos
Os dividendos mensais são calculados multiplicando o patrimônio total acumulado no período pela taxa de rendimento base da carteira (0,6% a.m. ou 0.006).
- **Fórmula aplicada:** `=Célula_Patrimônio * C$13`
- **Resultado obtido em 5 anos:** \$100,53 de renda passiva mensal.

### 3. Alocação por Tipo de FII
Distribuição do aporte de R\$ 200,00 com base nos percentuais recomendados para o perfil Moderado (Papel: 32%, Tijolo: 35%, Híbrido: 8%, FOFs: 5%, Desenvolvimento: 10% e Hotelaria: 10%).

## 📊 Visualização dos Dados
O repositório conta com gráficos integrados demonstrando o crescimento exponencial do patrimônio acumulado (Gráfico de Linhas) e a exata distribuição de ativos da carteira (Gráfico de Pizza).

---
Desenvolvido por Amanda Carvalho.
# simulador-investimento-fii
