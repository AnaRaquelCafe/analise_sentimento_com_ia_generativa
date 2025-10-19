# 🤖 Análise de Sentimento - App Streamlit

Aplicativo simples para análise de sentimento usando o modelo treinado com PySentimiento.

## 🚀 Como Executar

1. **Instalar dependências:**
```bash
pip install -r requirements.txt
```

2. **Executar o aplicativo:**
```bash
streamlit run app_simples.py
```

## 📋 Funcionalidades

- **Análise Individual**: Digite um texto e veja o sentimento.

## 📁 Arquivos Necessários

- `app_simples.py` - Aplicativo principal
- `sentiment_pipeline.pkl` - Modelo treinado (opcional)
- `requirements.txt` - Dependências

## 💡 Como Usar

1. Abra o aplicativo no navegador.
2. Digite um texto.
3. Clique em "Analisar Sentimento".
4. Veja os resultados e faça download se necessário.

## 🔧 Tecnologias Utilizadas

- **Streamlit**: Interface web
- **PySentimiento**: Modelo de análise de sentimento
- **NLTK**: Processamento de linguagem natural
- **Pandas**: Manipulação de dados

## ⚠️ Notas Importantes

- O aplicativo funciona mesmo sem o arquivo `sentiment_pipeline.pkl`
- Na primeira execução, o modelo será baixado automaticamente
- Para análise em lote, use colunas com nomes contendo 'text' ou 'comentario'