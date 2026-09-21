# 🚰 Classificador de Consumo de Água

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Sustentabilidade](https://img.shields.io/badge/Sustentabilidade-Água%20%26%20Meio%20Ambiente-4c1?style=for-the-badge)

## 📌 Sobre o Projeto
Este script em **Python** foi desenvolvido para a campanha de conscientização ambiental da companhia de saneamento local. O objetivo do sistema é classificar o perfil de consumo de água de diferentes imóveis (`comercial`, `casa` e `apartamento`) a partir do volume consumido em $m^3$, emitindo alertas educativos para incentivar o uso consciente dos recursos hídricos.

---

## 💡 Regras de Negócio

- **Comercial:** Aplica tarifa corporativa independentemente do consumo.
- **Apartamento:**
  - Consumo $< 10 m^3$: *Consumo econômico – excelente controle de água!*
  - Consumo de $10 m^3$ até $25 m^3$: *Consumo moderado – dentro do padrão residencial.*
- **Casa:**
  - Consumo $\le 25 m^3$: *Consumo moderado – dentro do padrão residencial.*
- **Demais casos (Consumo $> 25 m^3$ residencial):** *Consumo excessivo – adote medidas de economia e verifique vazamentos.*

---

## 🚀 Como Executar o Programa

### Pré-requisitos
- Ter o **Python 3.x** instalado em sua máquina.

### Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
