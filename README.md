<!--refs-->
[graficos]: /readme_refs/tipos_graficos.png
<!-------->

# Data Visualization com python
---

## Sobre

Repositório criado para apresentar as bibliotecas para visualização de dados com a linguagem python, que são elas,`matplotlib` e `seaborn`.
E buscando entender qua tipo de gráfico é mais adequada para cada situação.


## Criando seu ambiente virtual e ativando

Para criação do seu ambiente virtual, use o seguinte comando no prompt, na pasta do projeto:

```bash
	python -m venv venv
```

Para ativação do ambiente virtual, use este comando:

- PowerShell:

```bash
	venv/Scripts/Activate.ps1
```

- CMD:

```bash
	venv/Scripts/activate.bat
```

### Baixando dependências

Abra o prompt e escreva o seguinte comando para cada um dos projetos.

```bash
	pip install -r requirements.txt
```

## Entendendo tipos de visualizações

Na imagem abaixo, apresentamos um diagrama com diversos tipos de **visualização de dados** (criado por [Andrew Abela](https://extremepresentation.com/wp-content/uploads/choosing-a-good-chart-09-1.pdf)) em que é possível perceber que os gráficos mais comuns podem ser dividos em **4 subgrupos**:

- Comparação
- Distribuição
- Relacionamento
- Composição
---

![graficos]

---

### Comparação 📊
É amplamente utilizado quando queremos **comparar diferentes valores e atributos** dentro dos dados, uns com os outros. 

O tipo pode variar dependendo dos dados. Por exemplo: 

- Os nossos dados possuem uma variável temporal? 
 - Quantos períodos de tempo possuímos?
- Quantas variáveis e categorias os nossos dados apresentam? 

#### Visualizações mais comuns: Gráficos de colunas, barras e linhas
---

### Distribuição 🧮
É utilizado quando queremos entender **como as observações individuais são distribuídas** dentro de nosso conjunto de dados. 

O tipo pode variar dependendo dos dados. Por exemplo: 
- Quantas variáveis estou representando? 
- Possuo muitas ou poucas observações?

#### Visualizações mais comuns: histogramas de colunas e linhas e gráficos de dispersão.
---

### Relacionamento 🔀
É indicado quando estamos interessados em saber como os valores e atributos estão se relacionando entre si.

Para esse tipo, os gráficos de dispersão geralmente são usados quando traçamos a relação entre duas variáveis, e os gráficos de bolhas quando três variáveis estão envolvidas.

#### Visualizações mais comuns: Gráficos de dispersão e gráficos de bolhas
---

### Composição 📦
É utilizado quando queremos saber **como os dados são compostos**, ou seja, quais características gerais estão presentes no conjunto de dados. 

Existem algumas variações dependendo dos dados. Por exemplo:
- Os nossos dados são dinâmicos (mudam de acordo com o tempo)? 
  - Quantos períodos de tempo possuímos?
- Em dados estáticos, nós temos valores que são acumulados?

#### Visualizações mais comuns: Gráficos de colunas empilhadas, área e de pizza
----

## <center> :construction: Em Construção :construction: 

<details>
<summary> Links Úteis </summary>

*   [Infogram | Como escolher o gráfico certo para seus dados?](https://infogram.com/pt/pagina/escolha-grafico-de-visualizacoes-certo)
*   [Biuwer | Como escolher o melhor gráfico para os seus dados? (em inglês e espanhol)](https://biuwer.com/en/blog/how-to-choose-the-right-chart-for-your-data/)
*   [Data Viz Project | Coleção de visualizações de dados (em inglês)](https://datavizproject.com/)
*   [From data to Viz | Ache o gráfico que precisa (em inglês)](https://www.data-to-viz.com/)
*   [O Catálogo de Visualização de Dados (em inglês, espanhol e outras línguas)](https://datavizcatalogue.com/index.html)
*   [DisplayR Blog | O que é Overplotting? (em inglês)](https://www.displayr.com/what-is-overplotting/)
</details>

### Bibliotecas utilizadas
---
<div align="center">
<img src="/readme_refs/matplotlib.png" alt="matplotlib" border-radius="20%" width="230">

<img src="/readme_refs/seaborn_icon.png" alt="seaborn" width="240" height="56" >
</div>

