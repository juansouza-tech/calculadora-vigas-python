# calculadora-vigas-python
Script em Python para verificação de momento fletor e conversão de cargas em vigas bi apoiadas.

# 🏗️ Calculadora e Verificador de Vigas em Python
Este é um script desenvolvido em Python para automatizar a verificação inicial de vigas biapoiadas, visando otimizar a rotina de cálculos estruturais básicos de engenharia.

## 🚀 Funcionalidades
- **Entrada de Dados:** Recebe o vão da viga e a carga distribuída (com tratamento contra erros de digitação, convertendo automaticamente vírgulas em pontos).
- **Conversão Automática:** Converte a carga de kN/m para kgf/m instantaneamente.
- **Cálculo Estrutural:** Aplica a fórmula matemática para encontrar o Momento Fletor Máximo (M = q.l^2/8).
- **Sistema de Alerta Lógico:** Utiliza estruturas condicionais ('if/elif/else') para classificar a segurança da viga (Aprovada, Atenção ou Reprovada) com base nos esforços.
- **Execução Nativa:** Código blindado e adaptado para correr de forma autónoma diretamente no terminal do Windows.

## 🛠️ Tecnologias Utilizadas
- **Python 3:** Lógica de programação, variáveis, manipulação de strings, operadores matemáticos e estruturas de decisão.
