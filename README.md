# 🏢 Simulador de Financiamento - Vista Ponta Negra

Simulador interativo de financiamento imobiliário para o empreendimento **Vista Ponta Negra - Torre Maré**.

![Status](https://img.shields.io/badge/status-pronto-success)
![Versão](https://img.shields.io/badge/versão-1.0-blue)

## ✨ Funcionalidades

✅ **Seleção de Unidades**: Escolha entre 15 unidades diferentes (andares 1 a 28, tipos 2Q e 3Q)  
✅ **Ajuste de Entrada**: Use o slider ou digite o valor diretamente  
✅ **Cálculos em Tempo Real**:
- Valor de entrada (R$ e %)
- Financiamento CAIXA (até 90%)
- 1ª e última parcela (Sistema SAC)
- Parcelas com construtora
- Total de juros
- Fluxo completo em 3 fases

✅ **Configurações Personalizáveis**:
- Taxa de juros anual
- Prazo do financiamento (20 a 35 anos)
- Número de parcelas com construtora

✅ **Resumo Executivo**: Visão completa do investimento  
✅ **Design Profissional**: Dark theme responsivo para todos os dispositivos  

---

## 🚀 Como Usar

### Opção 1: Abrir Localmente (Mais Rápido)

1. Faça o download do arquivo `simulador_vista_ponta_negra.html`
2. Abra o arquivo no navegador (Chrome, Firefox, Edge, Safari)
3. **Funciona 100% offline!** Não precisa de internet

### Opção 2: Hospedagem Online (Recomendado para Compartilhar)

#### 🟢 **Netlify** (Mais Fácil - Drag & Drop)

1. Acesse: [https://netlify.com](https://netlify.com)
2. Faça login com GitHub, GitLab ou Email
3. Clique em **"Add new site"** → **"Deploy manually"**
4. Arraste o arquivo `simulador_vista_ponta_negra.html` para a área de upload
5. Pronto! Seu site estará no ar em segundos
6. Copie o link gerado (ex: `https://seu-site.netlify.app`)

**Alternativa via GitHub (Deploy Automático):**
```bash
# Se você já tem o repositório clonado
npm install -g netlify-cli
netlify login
netlify deploy --prod
```

#### 🔵 **Vercel** (Rápido e Profissional)

1. Acesse: [https://vercel.com](https://vercel.com)
2. Faça login com GitHub
3. Clique em **"Add New"** → **"Project"**
4. Importe este repositório ou faça upload manual
5. Vercel detecta automaticamente e faz o deploy
6. Link pronto em segundos!

**Via CLI:**
```bash
npm install -g vercel
vercel login
vercel --prod
```

#### 🟣 **GitHub Pages** (Gratuito e Integrado)

1. Faça fork ou clone deste repositório
2. Vá em **Settings** → **Pages**
3. Em **Source**, selecione a branch `main`
4. Clique em **Save**
5. Aguarde alguns minutos
6. Acesse: `https://seu-usuario.github.io/nome-do-repositorio/simulador_vista_ponta_negra.html`

#### 🟠 **Firebase Hosting** (Google)

```bash
# Instalar Firebase CLI
npm install -g firebase-tools

# Login
firebase login

# Inicializar projeto
firebase init hosting

# Deploy
firebase deploy
```

### Opção 3: Compartilhar Diretamente

#### 📧 Por Email/WhatsApp
- Envie o arquivo `simulador_vista_ponta_negra.html`
- Cliente abre no navegador
- Funciona offline perfeitamente

#### 🔗 Link Encurtado
Se hospedar online, crie um link curto:
- [Bit.ly](https://bitly.com)
- [TinyURL](https://tinyurl.com)
- [Rebrandly](https://rebrandly.com)

---

## 📱 Compatibilidade

✅ **Navegadores**:
- Chrome / Edge (recomendado)
- Firefox
- Safari
- Opera
- Qualquer navegador moderno

✅ **Dispositivos**:
- 💻 Desktop (Windows, Mac, Linux)
- 📱 Celular (Android, iOS)
- 📟 Tablet
- Layout 100% responsivo

---

## 🔧 Estrutura do Projeto

```
VistaMirantes/
│
├── simulador_vista_ponta_negra.html   # Arquivo principal (standalone)
├── README.md                           # Este arquivo
├── netlify.toml                        # Configuração Netlify (opcional)
└── vercel.json                         # Configuração Vercel (opcional)
```

**Importante**: O simulador é um arquivo HTML único e completo. Não precisa de CSS ou JS externos.

---

## 📊 Unidades Disponíveis

| Andar | Tipo | Área (m²) | Valor Base |
|-------|------|-----------|------------|
| 1     | 2Q   | 58,00     | R$ 458.832 |
| 4     | 2Q   | 58,00     | R$ 467.832 |
| 4     | 3Q   | 78,85     | R$ 634.757 |
| 5     | 2Q   | 58,00     | R$ 470.832 |
| 5     | 3Q   | 78,85     | R$ 637.757 |
| 10    | 2Q   | 58,00     | R$ 510.832 |
| 10    | 3Q   | 78,85     | R$ 677.757 |
| 15    | 2Q   | 58,00     | R$ 525.832 |
| 15    | 3Q   | 78,85     | R$ 692.757 |
| 20    | 2Q   | 58,00     | R$ 540.832 |
| 20    | 3Q   | 78,85     | R$ 707.757 |
| 25    | 2Q   | 58,00     | R$ 555.832 |
| 25    | 3Q   | 78,85     | R$ 722.757 |
| 28    | 2Q   | 58,00     | R$ 564.832 |
| 28    | 3Q   | 78,85     | R$ 731.757 |

---

## 💡 Dicas de Uso

### Para o Cliente:
1. **Começar Simples**: Selecione uma unidade e veja os valores padrão
2. **Ajustar Entrada**: Use o slider para ver como varia o financiamento
3. **Explorar Cenários**: Teste diferentes taxas e prazos
4. **Comparar Unidades**: Simule várias opções antes de decidir

### Para o Corretor:
1. **Hospede Online**: Use Netlify para ter um link profissional
2. **Link Curto**: Use bit.ly para facilitar o compartilhamento
3. **QR Code**: Gere um QR code do link para flyers/cartões
4. **Apresentação**: Mostre ao vivo durante visitas

---

## 🔐 Segurança e Privacidade

- ✅ **100% Client-Side**: Nenhum dado é enviado para servidor
- ✅ **Sem Cookies**: Não rastreia usuários
- ✅ **Sem Analytics**: Totalmente privado
- ✅ **Código Aberto**: Tudo visível no HTML

---

## 📞 Suporte

Para dúvidas sobre:
- **Implantação**: Consulte a documentação das plataformas
- **Funcionalidades**: Abra uma issue no GitHub
- **Vendas**: Entre em contato com a equipe comercial Vista Ponta Negra

---

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar.

---

## 🎯 Próximos Passos Recomendados

1. ✅ **Deploy Imediato**: Use Netlify drag-and-drop
2. 📊 **Adicionar Analytics** (opcional): Google Analytics ou Plausible
3. 🎨 **Personalizar Marca**: Adicione logo da construtora
4. 📧 **Integrar CRM**: Conecte com sistema de leads
5. 📱 **PWA**: Transforme em app instalável

---

<div align="center">

**🏗️ Vista Ponta Negra - Torre Maré**  
*Simulador desenvolvido para facilitar a experiência do cliente*

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/dronreef2/VistaMirantes)

</div>
