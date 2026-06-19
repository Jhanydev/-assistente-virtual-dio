
# 🤖 Assistente Virtual com Inteligência Artificial - Desafio DIO

https://colab.research.google.com/drive/1jyZNEyoFyGWj7XVXQIcOd-pEXuIWiFJt?authuser=1

## 📌 OBJETIVO

Desenvolver um assistente virtual que utiliza técnicas de Processamento de Linguagem Natural (PLN) para interagir com usuários através de voz e texto, executando ações como pesquisas na Wikipedia, abertura do YouTube e busca por farmácias próximas.

---

## 🛠️ TECNOLOGIAS UTILIZADAS

| Tecnologia | Descrição |
|------------|-----------|
| Google Colab | Ambiente de desenvolvimento 100% online |
| SpeechRecognition | Reconhecimento de fala (STT) |
| gTTS | Google Text-to-Speech - Síntese de voz |
| Wikipedia API | Pesquisa e extração de conteúdo |
| Webbrowser | Abertura de URLs |
| Pydub | Processamento de áudio |

---

## 🎯 FUNCIONALIDADES IMPLEMENTADAS

- ✅ Reconhecimento de comandos por voz (Speech-to-Text)
- ✅ Respostas faladas (Text-to-Speech)
- ✅ Pesquisa na Wikipedia com leitura dos resultados
- ✅ Abertura do YouTube via navegador
- ✅ Busca de farmácias no Google Maps
- ✅ Sistema de saudação e despedida
- ✅ Menu de ajuda interativo

---

## 📊 ESTRUTURA DO CÓDIGO

assistente-virtual-dio/
│
├── assistente_virtual.ipynb # Notebook principal
├── README.md # Documentação
│
└── funções/
├── falar() → Converte texto em áudio
├── ouvir() → Captura e transcreve voz
├── processar() → Interpreta e executa ações
└── main() → Loop principal


---

## 💡 DIFERENCIAIS

- **100% online** - Rodando no Google Colab, sem instalação
- **Voz ou texto** - Duas formas de interação
- **Código modular** - Fácil de entender e expandir
- **Respostas inteligentes** - Busca informações em tempo real

---

## 🚀 COMO EXECUTAR

### Opção 1: Google Colab (Recomendado)

1. Acesse o link: https://colab.research.google.com/drive/1jyZNEyoFyGWj7XVXQIcOd-pEXuIWiFJt?authuser=1
2. Clique em **"Runtime" > "Run all"**
3. Digite seus comandos ou use o microfone

### Opção 2: Localmente

```bash
# Instalar dependências
pip install gtts speechrecognition pydub wikipedia

# Executar o notebook
jupyter notebook assistente_virtual.ipynbhttps://colab.research.google.com/drive/1jyZNEyoFyGWj7XVXQIcOd-pEXuIWiFJt?authuser=1
