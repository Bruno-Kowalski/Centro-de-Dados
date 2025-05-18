# 📈 Simulação de Tráfego de Dados em um Centro de Dados

## 📘 Descrição do Projeto

Esse projeto é uma simulação matemática voltada para a gestão do tráfego de dados em centros de dados. Usando conceitos de Progressão Aritmética (PA) e Progressão Geométrica (PG), o sistema mostra como o tráfego de rede se comporta em dias normais e também em momentos de pico, como em falhas no sistema ou lançamentos de novos produtos.

A aplicação foi feita com HTML5 e JavaScript, e os gráficos foram criados com a biblioteca Chart.js.

## 🎯 Objetivos da Atividade

- Modelar o tráfego de dados em um data center considerando dois comportamentos:
- Aumento linear (PA) em dias normais
- Crescimento exponencial (PG) durante picos não programados
- Simular e exibir graficamente o tráfego diário em diferentes cenários
- Explorar os conceitos de funções matemáticas e séries numéricas
- Compreender o impacto da PG na previsão de tráfego

## 🔧 Tecnologias Utilizadas

- HTML5
- JavaScript 
- Chart.js para visualização gráfica

### 📌 Premissas

- Tráfego inicial: `100 GB`
- Aumento diário em dias normais: `+10 GB` (Progressão Aritmética)
- Durante picos não programados, o tráfego dobra a cada dia (Progressão Geométrica de razão 2)
- Após o pico, a progressão volta a ser aritmética, partindo do último valor calculado

### 📊 Tabela de Exemplo (com picos nos dias 3 e 7)

| Dia | Tipo            | Tráfego (GB) |
|-----|------------------|--------------|
| 0   | Normal           | 100          |
| 1   | Normal           | 110          |
| 2   | Normal           | 120          |
| 3   | Pico (início 1)  | 100          |
| 4   | Pico             | 200          |
| 5   | Pico             | 400          |
| 6   | Pós-pico         | 410          |
| 7   | Pico (início 2)  | 100          |
| 8   | Pico             | 200          |
| 9   | Pico             | 400          |

## 📊 Resultado Visual

O gráfico gerado representa o tráfego diário com variações reais baseadas na lógica matemática definida. Ele facilita a análise visual de padrões de sobrecarga e recuperação.

## 🤝 Contribuições

Sinta-se à vontade para sugerir melhorias ou propor novos cenários de simulação.
