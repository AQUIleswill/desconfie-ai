# desconfie.AI — Aplicativo Mobile (HTML) + Back-end Python (FastAPI + Gemini)

Este pacote entrega o **visual exato de aplicativo de celular** do pitch conectado diretamente ao **back-end Python** com o **Prompt Oficial do Desconfie**.

## Estrutura de Pastas
```text
desconfie_ai_mobile_app/
├── server.py              # Back-end Python (FastAPI + Gemini + BrasilAPI + RDAP + SQLite + TTS)
├── templates/
│   └── index.html         # Interface Mobile idêntica aos slides do PowerPoint
├── system_prompt.txt      # Prompt Oficial do agente Desconfie
├── requirements.txt       # Dependências Python
└── README.md              # Este guia
```

## Como Rodar
1. Instale as dependências:
```bash
pip install -r requirements.txt
```
2. Configure sua chave da Gemini API:
```bash
export GEMINI_API_KEY="SUA_CHAVE_AQUI"
```
3. Inicie o servidor:
```bash
python server.py
```
4. Abra no navegador (ou pelo celular na mesma rede Wi-Fi):
`http://localhost:8000`