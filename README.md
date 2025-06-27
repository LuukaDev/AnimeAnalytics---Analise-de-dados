# 🎌 Análise de Consumo de Animes: Gêneros, Países e Títulos Mais Assistidos

Este projeto analisa dados de consumo de animes ao redor do mundo com o objetivo de responder perguntas chave sobre **gêneros mais assistidos**, **países com maior tempo de visualização** e **animes com mais horas assistidas**. A análise foi desenvolvida utilizando **Python, Pandas e Plotly**.


![AnaliseAnime1](https://github.com/user-attachments/assets/9b5f72de-b233-43bb-a9f9-0334d364dc6c)
![AnaliseAnime3](https://github.com/user-attachments/assets/f2411aa8-9399-4a44-b7f2-54e6808f8bb2)


---

## 🎯 Problemas Resolvidos na Análise

- **Qual é o gênero de anime mais assistido?**  
  Identificar o gênero com o maior número de horas assistidas no total.

- **Qual país mais consome animes?**  
  Determinar qual país possui o maior tempo total de visualização.

- **Quais são os 10 animes mais assistidos?**  
  Listar os 10 títulos com maior número de horas assistidas.

---

## 📊 Base de Dados

O conjunto de dados foi carregado a partir do arquivo `Tabela_Animes.xlsx`, contendo as seguintes colunas principais:

- `Name` — Nome do anime  
- `Release_Date` — Data de lançamento  
- `Genre` — Gênero principal  
- `Watch_Count` — Quantidade de vezes assistido  
- `Total_Hours_Watched` — Total de horas assistidas  
- `Country_Most_Views` — País com mais visualizações

---

## 🔍 Principais Resultados

### ✅ Gênero de Anime Mais Assistido

| Gênero     | Horas Assistidas |
|------------|------------------|
| Adventure  | 16.892,23        |
| Comedy     | 14.438,64        |
| Fantasy    | 14.238,64        |

🎯 **Resultado**: O gênero mais assistido é **Adventure**.

---

### 🌍 País que Mais Consome Animes

| País     | Horas Assistidas |
|----------|------------------|
| USA      | 30.016,99        |
| Germany  | 20.144,21        |
| Brazil   | 13.278,27        |
| France   | 7.934,09         |

🎯 **Resultado**: O país que mais consome animes é **USA**.

---

### 🏆 Top 10 Animes Mais Assistidos

| Anime               | Horas Assistidas | País com Mais Visualizações |
|---------------------|------------------|------------------------------|
| Fairy Tail          | 9313.35          | USA                          |
| Black Clover        | 8022.36          | Brazil                       |
| Death Note          | 7561.66          | USA                          |
| Fullmetal Alchemist | 7128.31          | France                       |
| My Hero Academia    | 7110.33          | Germany                      |
| One Punch Man       | 5563.10          | USA                          |
| Hunter x Hunter     | 5007.89          | USA                          |
| Bleach              | 4814.77          | Germany                      |
| Naruto              | 4402.73          | Brazil                       |
| Sword Art Online    | 4385.66          | Germany                      |

---

## 📈 Gráficos Demonstrativos

### 🔹 Total de Horas Assistidas por País

Gráfico de barras horizontal com a soma total de horas assistidas por país. Os dados são ordenados do país com maior consumo para o menor.

### 🔹 Top 10 Animes Mais Assistidos

Gráfico interativo com os 10 animes mais assistidos, segmentado por país de maior visualização.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **Pandas**
- **Plotly Express**
- **Google Colab / Jupyter Notebook**
- **Excel (.xlsx)**

---

## 💡 Conclusão

A análise revelou que o gênero **Adventure** é o mais consumido globalmente, com destaque para o mercado dos **Estados Unidos**, que lidera em tempo de visualização. Títulos como **Fairy Tail**, **Black Clover** e **Death Note** se destacam como os animes mais assistidos globalmente, indicando preferências consolidadas entre os públicos de diferentes países.

---
