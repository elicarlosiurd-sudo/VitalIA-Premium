# VitalIA Premium — Saúde com Inteligência 🧬

Aplicativo web de saúde e nutrição com integração Telegram, scanner de código de barras, coach IA e muito mais!

## ✨ Funcionalidades

- 🥗 **Diário Alimentar** — Registre suas refeições e acompanhe macros
- 🤖 **Coach IA** — Assistente inteligente com suporte a voz (STT/TTS)
- 📱 **Scanner de Código de Barras** — Escaneie produtos e analise nutrição
- 📖 **Receitas Recomendadas** — Receitas balanceadas em 4 idiomas
- 📈 **Progresso com Gráficos** — Acompanhe sua evolução em tempo real
- 💧 **Hidratação** — Controle de ingestão de água
- 📱 **Integração Telegram** — Receba notificações e atualizações no Telegram
- 🌍 **Internacionalização** — Suporte a PT, EN, ES, RU
- 🎨 **Dark Mode Verde Vagalume** — Design moderno e responsivo

## 🚀 Como Usar

### No Navegador
1. Abra `index.html` em um navegador moderno
2. Faça login ou use modo demonstração
3. Explore todas as funcionalidades

### No Telegram
1. Crie um bot no Telegram (@BotFather)
2. Adicione o link do app Web App
3. Conecte-se via botão "Conectar Telegram" na Home

## 📁 Estrutura

```
app-VitalIA-Premium/
├── index.html              # App completo (HTML + CSS + JS puro)
├── data/
│   ├── receitas_pt.json    # Receitas em Português
│   ├── receitas_en.json    # Receitas em English
│   ├── receitas_es.json    # Receitas em Español
│   └── receitas_ru.json    # Receitas em Русский
└── README.md               # Este arquivo
```

## 🔧 Tecnologias

- HTML5 + CSS3 + JavaScript Puro (sem frameworks)
- QuaggaJS (Scanner de Código de Barras)
- Chart.js (Gráficos)
- Telegram Web App SDK
- Web Speech API (STT/TTS)
- localStorage (Persistência)

## 📱 Compatibilidade

- ✅ iOS (Safari, Expo Go, PWA)
- ✅ Android (Chrome, Firefox, Expo Go)
- ✅ Web (Chrome, Firefox, Safari, Edge)
- ✅ Telegram Web App

## 🎯 Deploy

### Vercel
```bash
vercel deploy
```

### Netlify
```bash
netlify deploy --prod
```

### GitHub Pages
```bash
git push origin main
```

## 📞 Telegram Integration

Para conectar com Telegram:

1. Crie um bot: @BotFather
2. Configure Web App URL
3. Clique "Conectar Telegram" no app
4. Receba notificações de saúde em tempo real

## 📊 Auditoria

Todas as funcionalidades foram testadas e validadas:
- ✅ Câmera
- ✅ Microfone
- ✅ Síntese de Voz
- ✅ Reconhecimento de Fala
- ✅ localStorage
- ✅ Scanner de Código
- ✅ Gráficos
- ✅ i18n (4 idiomas)
- ✅ Telegram Integration
- ✅ Persistência de Dados

## 📄 Licença

MIT — Livre para usar e modificar

---

**Desenvolvido com ❤️ por VitalIA Team**
