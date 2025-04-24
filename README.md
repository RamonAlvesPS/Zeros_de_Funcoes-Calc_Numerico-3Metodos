# 🧮 Métodos Numéricos para Zeros de Funções

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12bUHSHdEeqKEBzPq7QSCK-PqjhUF0YDu)

Repositório com implementações em Python dos principais métodos numéricos para encontrar zeros de funções, desenvolvido como parte da disciplina de **Cálculo Numérico** na Engenharia de Controle e Automação.

---

## 🚀 **O que você vai encontrar aqui?**

### 📌 **Métodos Implementados**
1. **Bissecção**  
   *Divide e conquista: método robusto para isolamento de raízes.*  
2. **Cordas (Falsa Posição)**  
   *Interpolação linear inteligente entre intervalos.*  
3. **Newton-Raphson**  
   *Velocidade de foguete com derivadas numéricas!*  

### 📊 **Análises**
- Comparação de convergência entre métodos  
- Gráficos interativos de evolução das iterações  
- Exemplos aplicados (cálculo de taxas de juros, modelos físicos)  

---

## ⚙️ **Como usar?**

### Pré-requisitos
- Python 3.8+
- Bibliotecas: `numpy`, `matplotlib`

### Instalação
```bash
git clone https://github.com/RamonAlvesPS/Zeros_de_Funcoes-Calc_Numerico-3Metodos.git
cd Zeros_de_Funcoes-Calc_Numerico-3Metodos
pip install -r requirements.txt
```

## 📈 Exemplo de Uso
```
python
from metodos.bisseccao import bisseccao

def f(x):
    return x**3 - x - 1

raiz, erro, iteracoes, historico = bisseccao(f, 1, 2, tol=1e-6)
print(f"Raiz: {raiz:.6f} | Iterações: {iteracoes} | Erro: {erro:.2e}")
```

  - Saída:
   ```Raiz: 1.324718 | Iterações: 20 | Erro: 7.62e-07```

## 🛠 Estrutura do Projeto
```
.
├── metodos/               # Implementações dos métodos
│   ├── bisseccao.py
│   ├── cordas.py
│   └── newton_raphson.py
├── exemplos/              # Casos de uso práticos
│   ├── taxa_juros.py
│   └── modelos_fisicos.py
├── notebooks/             # Análises gráficas e comparativas
│   └── analise_convergencia.ipynb
├── requirements.txt       # Dependências
└── README.md
```

## 📜 Licença
Distribuído sob a licença MIT. Veja LICENSE para mais detalhes.

---

Desenvolvido com ☕ por Ramon Alves
(📚 Acesse o Google Colab)[] | (💻 Mais projetos no GitHub)[]

---

### ✨ **Destaques**
- **Visualização de Dados:** Gráficos comparativos de convergência  
- **Pronto para Produção:** Código modular e documentado  
- **Aplicações Reais:** Exemplos financeiros e físicos  

*"Resolver equações complexas nunca foi tão divertido!"* 😎
