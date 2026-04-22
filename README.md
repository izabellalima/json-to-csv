# JSON â†’ CSV Converter

Uma ferramenta rÃ¡pida e segura para converter JSON em CSV, totalmente no seu navegador.

## ðŸš€ Features

- **ConversÃ£o instantÃ¢nea** â€” JSON â†’ CSV em tempo real
- **100% privado** â€” seus dados nunca saem do browser
- **Drag & drop** â€” arraste um arquivo .json
- **Separadores configurÃ¡veis** â€” vÃ­rgula, tab, ponto e vÃ­rgula
- **Preview em tabela** â€” veja os primeiros 50 registros
- **Download automÃ¡tico** â€” com BOM UTF-8 para Excel reconhecer acentos
- **Suporte a estruturas aninhadas** â€” detecta arrays automaticamente

## ðŸ“– Como usar

1. Abra `index.html` no seu navegador
2. Cole seu JSON no painel esquerdo (ou arraste um arquivo)
3. O CSV aparece automaticamente no painel direito
4. Clique em "Download CSV" para baixar

## ðŸ’¡ Exemplos de entrada

**Array simples:**
```json
[
  {"nome": "Iza", "idade": 28},
  {"nome": "Dev", "idade": 30}
]
```

**Objeto com array aninhado:**
```json
{
  "data": {
    "rows": [
      ["-JH40966...", 1],
      ["-tuA3AbRINr...", 1]
    ]
  }
}
```

**Objeto Ãºnico:**
```json
{
  "id": 1,
  "nome": "Izabella",
  "email": "iza@example.com"
}
```

## ðŸ“ License

Libre para usar, modificar e compartilhar.
