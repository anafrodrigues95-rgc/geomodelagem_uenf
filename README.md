# Trabalho de GeoModelagem e Visão Computacional - Açaí e Barbeiro

Este repositório contém o desenvolvimento prático da análise integrada da produção de açaí no Estado do Pará, combinando geoprocessamento, dados meteorológicos, modelagem espacial e visão computacional.

## 🎓 Informações Acadêmicas

* **Instituição:** Universidade Estadual do Norte Fluminense Darcy Ribeiro (UENF)
* **Laboratório:** LAMET - Laboratório de Meteorologia
* **Programa:** Mestrado em Clima e Energia
* **Disciplina:** GeoModelagem do Potencial Energético e do Microclima Urbano
* **Professora:** Dra. Raquel Jahara Lobosco
* **Desenvolvido em Dupla por:** Ana Flávia Rodrigues Barcelos Cordeiro & Rayane Pereira de Souza

---

## 🗺️ Parte 1 – Mapeamento Climático

> 🚀 [Clique aqui para abrir o Notebook da Parte 1 (Mapas_acai.ipynb)](./Mapas_acai.ipynb)

Nesta etapa, criamos os mapas climáticos sazonais do Estado do Pará utilizando a biblioteca **Cartopy** em Python, destacando a principal região produtora de açaí (Igarapé-Miri, Cametá, Abaetetuba e entorno).

### 📍 Área de Estudo e Cobertura da Terra
Abaixo apresenta-se a delimitação da região produtora do Baixo Tocantins em foco e o respectivo mapeamento de uso e cobertura do solo:

<p align="center">
  <img src="./Regiao_produtora.jpeg" width="45%" alt="Região Produtora"/>
  <img src="./Mapa_usoecobertura.jpeg" width="45%" alt="Uso e Cobertura da Terra"/>
</p>

Foram processados dados meteorológicos da base **Copernicus (ERA5/ERA5-Land)** referentes ao ano de 2024 (horário das 15h). Abaixo estão os mapas sazonais gerados para cada variável atmosférica:

### 🌧️ Precipitação ou Índice Pluviométrico
<img width="1600" height="1333" alt="Precipitacao_4_estacoes" src="https://github.com/user-attachments/assets/8b524ed6-4505-4eaf-992b-6c697917175f" />

### 🌡️ Temperatura do Ar (ºC)
<img width="1600" height="1333" alt="Temperatura_4_estacoes" src="https://github.com/user-attachments/assets/a9596f08-561b-4f80-b523-d4a8de806cff" />


### 💨 Intensidade do Vento (m/s)
<img width="1600" height="1333" alt="Vento_4_estacoes" src="https://github.com/user-attachments/assets/ef97590b-bfe5-4ae7-9c34-0e976b6e4d82" />


### 💧 Umidade Relativa (%)
<img width="1600" height="1333" alt="Umidade_4_estacoes" src="https://github.com/user-attachments/assets/c9c8124d-2007-4c37-813e-e7b3db4de977" />

---

## 👁️ Parte 2 – Visão Computacional com YOLO

> 🚀 [Clique aqui para abrir o Notebook da Parte 2 (acaibarbeiro.ipynb)](./acaibarbeiro.ipynb)


Aplicação de visão computacional utilizando a biblioteca **YOLO/Ultralytics** para detectar elementos associados à produção de açaí e ao risco sanitário. O modelo foi treinado para realizar a detecção visual do inseto vetor (barbeiro/triatomíneo) e das estruturas do fruto (açaí, cacho).

---

## 📊 Parte 3 – Análise Integrada entre Clima e Produção de Açaí

Abaixo apresenta-se a tabela comparativa correlacionando os dados meteorológicos do Copernicus com os aspectos ecológicos e biológicos observados na região produtora de Igarapé-Miri, Abaetetuba e Cametá.


### 📈 Tabela Comparativa Sazonal (Dados Reais ERA5-Land 2024)

| Estação | Precipitação (mm/dia) | Temperatura (°C) | Umidade (%) | Vento (m/s) | Índice de Produção |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **Verão** | 4.48 | 30.06 | 68.22 | 2.03 | Baixo |
| **Outono** | 12.25 | 29.29 | 76.66 | 1.34 | Muito Baixo |
| **Inverno** | 1.31 | 32.54 | 50.11 | 2.00 | Médio |
| **Primavera** | 0.32 | 35.11 | 39.63 | 2.38 | Alto |

### 📉 Gráfico de Correlação Sazonal

<img width="989" height="690" alt="grafico_clima_x_indice_de_producao" src="https://github.com/user-attachments/assets/36b4c580-171d-473e-9a1a-cc6be94983c0" />


---

## 📄 Relatório Final

O relatório final detalhado com toda a fundamentação teórica, metodologia e análise aprofundada dos resultados foi gerado em formato PDF e pode ser consultado na documentação do projeto.

Relatório final com todos os dados e análise
![Geomodelagem, Clima e Produção de Açaí (1).pdf]
