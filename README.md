# 🤖 NLW Operator - Computer Vision & AI Hub 🚀

Bem-vindo ao **NLW Operator Vision**, um repositório dedicado à exploração de fronteiras em Visão Computacional e Inteligência Artificial Generativa. Este projeto reúne as ferramentas mais potentes da atualidade para análise, detecção e segmentação de imagens.

---

## 🎨 Visão Geral do Projeto

Este ecossistema foi projetado para demonstrar implementações práticas de modelos de Deep Learning e LLMs Multimodais. Utilizamos frameworks líderes como **Google Gemini**, **PyTorch**, **Hugging Face** e **MediaPipe**.

### 🧪 Notebooks Disponíveis

| Notebook | Tecnologia | Descrição |
| :--- | :--- | :--- |
| `gemini_vision.ipynb` | **Google Gemini 2.5 Flash** | Extração de dados estruturados de imagens usando AI Multimodal. |
| `yolos_detection.ipynb` | **Hugging Face (YOLOS)** | Detecção de objetos baseada em Transformers (Object Detection). |
| `clipseg_segmentation.ipynb` | **Hugging Face (CLIPSeg)** | Segmentação de imagens via texto (Zero-Shot Segmentation). |
| `mobilenet_classification.ipynb`| **MobileNetV3 (timm)** | Classificação ultra-rápida e eficiente de imagens. |
| `mediapipe_object_detection.ipynb`| **Google MediaPipe** | Detecção de objetos otimizada para dispositivos móveis e web. |

---

## 🛠️ Tecnologias & Bibliotecas

O projeto utiliza um stack moderno focado em performance e facilidade de desenvolvimento:

*   **Google Generative AI SDK**: Integração com Gemini Pro/Flash.
*   **Hugging Face Transformers**: Modelos state-of-the-art portados para fácil uso.
*   **MediaPipe**: Framework do Google para ML em dispositivos.
*   **PyTorch**: O "motor" por trás da maioria dos modelos de visão.
*   **Pydantic**: Validando e estruturando as respostas da IA.
*   **Timm**: Biblioteca premium de modelos de visão pré-treinados.
*   **OpenCV**: Manipulação de imagem e vídeo em tempo real.

---

## 🚀 Como Começar (Quick Start)

### 1. Preparação do Terreno
Este projeto utiliza o **`uv`**, o gerenciador de pacotes Python mais rápido do mercado.

```bash
# Instale o uv se ainda não tiver
pip install uv

# Clone o repositório
git clone https://github.com/Luisfsiq/nlwoperator.git
cd nlwoperator
```

### 2. Configurando o Ambiente
Crie e ative seu ambiente virtual com apenas um comando:

```bash
uv venv
# No Windows (PowerShell):
.venv\Scripts\activate
# No Linux/macOS:
source .venv/bin/activate

# Instale as dependências
uv pip install -r pyproject.toml
```

### 3. Configuração de API
Crie um arquivo `.env` na raiz do projeto:
```env
GOOGLE_API_KEY=SUA_CHAVE_AQUI
```
> [!TIP]
> Você pode obter sua chave gratuita no [Google AI Studio](https://aistudio.google.com/app/apikey).

---

## 📂 Estrutura de Pastas

*   `images/`: Local para colocar suas fotos de teste.
*   `*.ipynb`: Notebooks interativos para experimentação.
*   `pyproject.toml`: Definição de dependências e metadados do projeto.
*   `.env`: Configurações sensíveis (não commitada se estiver no .gitignore).

---

## 👤 Autor

Desenvolvido com foco em aprendizado prático durante o evento **NLW Operator**.

*   **GitHub**: [@Luisfsiq](https://github.com/Luisfsiq)
*   **Repositório**: [nlwoperator](https://github.com/Luisfsiq/nlwoperator)

---
<p align="center">
  Feito com 💙 por Luisfsiq
</p>
