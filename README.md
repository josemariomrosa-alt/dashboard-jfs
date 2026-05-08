# Dashboard — Transferências Internacionais
### Empresas Agrícolas Grupo JFS

Dashboard de monitorização de transferências internacionais. Ficheiro único HTML, sem dependências de servidor.

---

## 🚀 Como usar no GitHub Pages

1. Crie um repositório no GitHub (ex: `dashboard-transferencias`)
2. Faça upload do ficheiro `index.html` para a raiz do repositório
3. Vá a **Settings → Pages**
4. Em *Branch*, seleccione `main` e pasta `/root`
5. Clique **Save**
6. O dashboard fica disponível em:
   `https://<o-seu-utilizador>.github.io/dashboard-transferencias/`

---

## 📋 Funcionalidades

- **KPIs** — Total de processos, pagos, falta documentos, em curso, média de dias e totais por moeda (USD / EUR / ZAR)
- **3 abas** — Todas / Entregues ao Banco / Por Entregar
- **Filtros** — Por moeda, por banco (BIM / MOZA) e pesquisa livre
- **3 datas por processo** — Início, Entrega no Banco, Processamento (formato DD/MM/AAAA)
- **Contagem de dias** — Calcula automaticamente os dias entre Início e Processamento (verde ≤7d / amarelo ≤21d / vermelho >21d)
- **Edição completa** — Clique em qualquer linha para editar todos os campos no painel lateral
- **Adicionar / Apagar** — Formulário para novos processos e botão de apagar com confirmação

---

## 📁 Estrutura

```
index.html   ← ficheiro único, tudo incluído (HTML + CSS + JS)
README.md    ← este ficheiro
```

---

## 🔒 Nota sobre os dados

Os dados são guardados **em memória** enquanto a página está aberta. Para persistência permanente, seria necessário integrar um backend ou Google Sheets API. Recomenda-se exportar regularmente para Excel se necessário.

