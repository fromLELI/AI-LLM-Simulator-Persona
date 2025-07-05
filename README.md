# AI-LLM-Simulator-Persona

---

# 🚀 AI Influencer Generator | SadTalker + Stable Diffusion + GPT-4o

Criei um **vídeos de influenciadores digitais** hiper-realistas de forma automatizada, unindo o poder de geração de imagem do Stable Diffusion, voz via IA (Google TTS) e animação facial com SadTalker. Pipeline orquestrado com automação inteligente, pronto para branding, campanhas, treinamento, onboarding digital ou comunicação de autoridade.

---

## Demonstração do Resultado

> **Veja abaixo o vídeo gerado automaticamente pelo pipeline:**

<div align="center">
  
<!-- Substitua o link pelo upload do seu vídeo .mp4 gerado -->
<video width="480" controls>
  <source src="results/2025_07_05_16.44.37.mp4" type="video/mp4">
  Seu navegador não suporta a exibição de vídeo.
</video>

</div>

---

## Por que usar esse projeto?

- **Autoridade Digital:** Crie avatares realistas e vídeos personalizados para sua marca, produto ou persona de influência.
- **Escalabilidade:** Automatize a produção de vídeos educativos, treinamentos, avatares para campanhas ou onboarding digital.
- **Inovação:** Integração de IA de última geração para imagens, áudio e sincronização labial (SadTalker).

---

## Stack & Tecnologias

- [x] **Stable Diffusion** (`diffusers`) – Geração de avatar realista
- [x] **SadTalker** – Animação labial/sincronização facial
- [x] **gTTS** – Voz IA multi-idioma (Google Text-to-Speech)
- [x] **OpenAI GPT-4o** – Engenharia de prompts e automação inteligente
- [x] **CUDA Support** – Geração acelerada por GPU (NVIDIA)

---

## Como funciona

1. **Prompt Engineering:** Descreva o avatar desejado (em português ou inglês). A IA gera um prompt refinado e assertivo para obter imagens de altíssima qualidade.
2. **Geração do Avatar:** Stable Diffusion converte o prompt em uma imagem realista, já no formato ideal para animação.
3. **Voz Personalizada:** Google TTS gera o áudio no idioma e estilo desejado.
4. **Animação SadTalker:** Integra tudo em um vídeo animado (.mp4) pronto para uso corporativo, marketing ou treinamento.

---

## Passo a Passo para rodar localmente

> **Pré-requisitos:**  
> Python 3.8+, GPU NVIDIA (recomendado), drivers CUDA, ffmpeg instalado no PATH

```bash
# Clone o repositório
git clone https://github.com/seuusuario/AI-Influencer-Generator.git
cd AI-Influencer-Generator

# Instale as dependências
pip install -r requirements.txt

# Baixe os modelos e pesos necessários
python download_models.py

# Execute o notebook ou o pipeline principal
# (Exemplo de uso no notebook: AI_Persona.ipynb)
