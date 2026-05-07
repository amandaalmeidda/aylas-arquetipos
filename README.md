# Elenco de Arquétipos · Espaço Aylas

Formulário interativo para categorizar cães em 7 arquétipos de personalidade.

**Acesso:** [https://amandaalmeidda.github.io/aylas-arquetipos/](https://amandaalmeidda.github.io/aylas-arquetipos/)

## Funcionalidades

- ✅ 7 arquétipos pré-configurados
- ✅ Upload de fotos para cada cão
- ✅ Preenchimento de nome e raça
- ✅ Envio para Google Apps Script
- ✅ Design Olmeda Agency

## Como Usar

1. Abra [https://amandaalmeidda.github.io/aylas-arquetipos/](https://amandaalmeidda.github.io/aylas-arquetipos/)
2. Para cada esquadrão, adicione os cães que se encaixam
3. Coloque nome, raça e tire uma foto
4. Clique em "Enviar para a Amanda"

## Configuração do Apps Script

O formulário envia dados para um Google Apps Script. Para ativar:

1. Crie um projeto no [Google Apps Script](https://script.google.com)
2. Cole a URL do script em `const SCRIPT_URL` no arquivo `index.html`
3. O script receberá um JSON com dados dos cães

**Estrutura do payload:**
```json
{
  "responder": "Nome de quem preencheu",
  "timestamp": "2026-05-07T...",
  "archetypes": {
    "painel_solar": { "name": "O Painel Solar", "dogs": [...] },
    ...
  }
}
```

## Design System

Usa tokens de design da Olmeda Agency:
- Primary: `#37254c` (roxo)
- Lilac: `#CFC1E8`
- Tipografia: Cormorant Garamond + Inter

---

**Mantido por:** Amanda Almeida · Olmeda Agency
