# NLW Operator - Inteligência Artificial Visionária 🚀

Este repositório contém uma coleção de notebooks interativos demonstrando as capacidades mais modernas de Visão Computacional e IA Generativa, utilizando o Google Gemini, PyTorch e Hugging Face.

## 📋 Conteúdo do Projeto

O projeto está dividido em notebooks especializados:

1.  **`gemini_vision.ipynb`**: Análise de imagens com o Google Gemini 1.5 Flash usando **Output Estruturado** (Pydantic).
2.  **`mobilenet_classification.ipynb`**: Classificação de imagens (Top-5) usando a arquitetura eficiente **MobileNetV3** (via biblioteca `timm`).
3.  **`yolos_detection.ipynb`**: Detecção de objetos em tempo real usando **YOLOS** (You Only Look at One Sequence) baseado em Transformers.
4.  **`clipseg_segmentation.ipynb`**: Segmentação de imagens **Zero-shot** usando linguagem natural (texto para máscara).

---

## 💻 Requisitos e Instalação

Este projeto utiliza o gerenciador de pacotes moderno **`uv`** para garantir velocidade e reprodutibilidade.

### 1. Pré-requisitos
*   **Python 3.10 ou superior** installed.
*   **Git** instalado.
*   **Google Gemini API Key**: [Obtenha aqui](https://aistudio.google.com/app/apikey).

### 2. Clonando o Repositório
```bash
git clone https://github.com/Luisfsiq/nlwoperator.git
cd nlwoperator
```

### 3. Configurando o Ambiente (Windows, macOS e Linux)

Recomendamos o uso do `uv` para criar o ambiente virtual:

**Para Windows (PowerShell):**
```powershell
pip install uv
uv venv
.venv\Scripts\activate
uv pip install -r pyproject.toml
```

**Para macOS / Linux:**
```bash
pip install uv
uv venv
source .venv/bin/activate
uv pip install -r pyproject.toml
```

### 4. Variáveis de Ambiente
Crie um arquivo chamado `.env` na raiz do projeto e adicione sua chave do Gemini:
```env
VITE_GOOGLE_API_KEY=SUA_CHAVE_AQUI
```

---

## 🛠️ Tecnologias Utilizadas

*   **Google Generative AI SDK**: Para integração com o Gemini.
*   **PyTorch**: Framework base para os modelos de Deep Learning.
*   **Timm (PyTorch Image Models)**: Para modelos de classificação otimizados.
*   **Hugging Face Transformers**: Para modelos YOLOS e ClipSeg.
*   **Pydantic**: Para garantir que as respostas da IA sejam estruturadas corretamente.
*   **Matplotlib/PIL**: Para visualizações ricas de gráficos e segmentações.

---

## 🚀 Como Executar
1.  Coloque as imagens que deseja analisar dentro da pasta `images/`.
2.  Abra o VS Code.
3.  Selecione cada notebook `.ipynb`.
4.  Certifique-se de selecionar o Kernel do ambiente virtual criado (`.venv`).
5.  Execute as células!

---

## 👤 Autor
Desenvolvido durante a trilha NLW Operator.
GitHub: [@Luisfsiq](https://github.com/Luisfsiq)
