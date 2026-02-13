# STEAM — Matemática, Dados e Ciências com Gráficos (Python)

Miniportfólio educacional com 4 atividades:
1. Matemática: função constante, 1º e 2º grau
2. Geografia/Dados: demografia por região do Brasil
3. Biologia: crescimento de plantas
4. Física: MRU e MRUV

## Como executar
1. Ative o ambiente:
   - .\.venv\Scripts\Activate.ps1
2. Rode o Jupyter:
   - python -m notebook
  
# STEAM — Aulas com Gráficos (Python)

Miniportfólio educacional com atividades de **Matemática, Geografia/Dados, Biologia e Física**, usando gráficos para facilitar a aprendizagem.

## Atividades (Notebooks)
- **01 Matemática:** função constante, 1º e 2º grau → `notebooks/01_matematica_funcoes.ipynb`
- **02 Demografia (Brasil):** população por região → `notebooks/02_geografia_demografia_brasil.ipynb`
- **03 Biologia:** crescimento de plantas (com luz vs sem luz) → `notebooks/03_biologia_crescimento.ipynb`
- **04 Física:** MRU e MRUV (posição, velocidade, aceleração) → `notebooks/04_fisica_mru_mruv.ipynb`

## Prévia dos gráficos

<p align="center">
  <img src="figures/funcoes.png" width="48%" />
  <img src="figures/demografia.png" width="48%" />
</p>

<p align="center">
  <img src="figures/biologia.png" width="48%" />
  <img src="figures/fisica_posicao.png" width="48%" />
</p>

## Como executar (Windows / PowerShell)
```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python -m jupyterlab
   -

---

## 3) Subir as imagens + README pro GitHub
No PowerShell:

```powershell
git add README.md figures/funcoes.png figures/demografia.png figures/biologia.png
git commit -m "Add preview images and improve README"
git push

