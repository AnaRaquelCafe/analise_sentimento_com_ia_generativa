# Guia: Deploy do Modelo de Análise de Sentimento

## 📋 Pré-requisitos

### 1. Ambiente Virtual
```bash
# Criar ambiente virtual
python -m venv .venv

# Ativar ambiente (macOS/Linux)
source .venv/bin/activate

# Ativar ambiente (Windows)
.venv\Scripts\activate
```

### 2. Instalar Dependências
```bash
# Instalar bibliotecas necessárias
pip install -r requirements.txt
```

### 3. Baixar Recursos NLTK
```bash
python -c "import nltk; nltk.download('stopwords'); nltk.download('punkt')"
```

## 🔧 Estrutura do Projeto

```
projeto/
├── sentiment_pipeline.pkl    # Modelo treinado
├── app_simples.py           # Aplicativo Streamlit principal
├── requirements.txt          # Dependências (otimizado para deploy)
└── passos_deploy.md        # Este guia
```

## 🎯 Passos para Deploy Local

### 1. Verificar Arquivos
- Confirme que `sentiment_pipeline.pkl` está na raiz do projeto
- Verifique se `app_simples.py` está configurado corretamente

### 2. Executar Localmente
```bash
streamlit run app_simples.py
```
