# 🎨 Guia Completo - Cintila Design

## 📋 O que foi personalizado:

### ✅ **Informações de Contato:**
- **WhatsApp:** `5511987654321` (exemplo - você deve alterar)
- **Instagram:** `@cintiladesign_oficial` (exemplo - você deve alterar)
- **Experiência:** Adicionei "5 anos de experiência"
- **Descrições:** Melhorei as descrições dos serviços

---

## 🔧 **Como Alterar Cada Parte:**

### 1️⃣ **ALTERAR NÚMERO DO WHATSAPP**

**Onde encontrar:**
- Arquivo: `index.html`
- Linhas: 117, 184
- Arquivo: `script.js`
- Linha: 60

**Como alterar:**
```html
<!-- ANTES -->
<a href="https://wa.me/5511987654321">

<!-- DEPOIS (seu número real) -->
<a href="https://wa.me/5511999887766">
```

**⚠️ IMPORTANTE:** 
- Use o formato: `55` (Brasil) + `11` (DDD) + `999887766` (número)
- SEM espaços, SEM +, SEM parênteses
- Exemplo: `5511999887766`

### 2️⃣ **ALTERAR INSTAGRAM**

**Onde encontrar:**
- Arquivo: `index.html`
- Linhas: 131, 181

**Como alterar:**
```html
<!-- ANTES -->
<a href="https://instagram.com/cintiladesign_oficial">

<!-- DEPOIS (seu Instagram real) -->
<a href="https://instagram.com/seu_instagram_aqui">
```

### 3️⃣ **ALTERAR TEXTO "SOBRE NÓS"**

**Onde encontrar:**
- Arquivo: `index.html`
- Linha: 59

**Como alterar:**
```html
<p>A <strong>Cintila Design</strong> é uma empresa especializada em design gráfico e criação visual, dedicada a transformar suas ideias em arte. Com mais de 5 anos de experiência no mercado, oferecemos soluções criativas e profissionais para diversos segmentos, desde pequenas empresas até grandes corporações.</p>
```

### 4️⃣ **ALTERAR CORES**

**Onde encontrar:**
- Arquivo: `styles.css`

**Cores principais:**
```css
/* Cor principal (azul) */
#6366f1

/* Cor de destaque (verde) */
#10b981

/* Gradiente do hero */
#667eea e #764ba2
```

**Como alterar:**
1. Abra o arquivo `styles.css`
2. Use Ctrl+F para buscar a cor
3. Substitua pela cor desejada
4. Salve o arquivo

**Exemplo de cores:**
- Azul: `#3b82f6`
- Verde: `#22c55e`
- Roxo: `#8b5cf6`
- Rosa: `#ec4899`

### 5️⃣ **ALTERAR SERVIÇOS**

**Onde encontrar:**
- Arquivo: `index.html`
- Linhas: 72-90

**Como alterar:**
```html
<div class="service-item">
    <i class="fas fa-paint-brush"></i>
    <h4>SEU SERVIÇO AQUI</h4>
    <p>Descrição do seu serviço</p>
</div>
```

### 6️⃣ **ALTERAR TÍTULO DA PÁGINA**

**Onde encontrar:**
- Arquivo: `index.html`
- Linha: 6

**Como alterar:**
```html
<title>SEU TÍTULO AQUI - Design Gráfico e Criação Visual</title>
```

---

## 🧪 **COMO TESTAR A PÁGINA:**

### **Método 1: Abrir Direto no Navegador**
1. Navegue até a pasta onde estão os arquivos
2. Clique duas vezes no arquivo `index.html`
3. A página abrirá no seu navegador padrão

### **Método 2: Usar Live Server (Recomendado)**
1. **Instale o VS Code** (se não tiver)
2. **Instale a extensão "Live Server"**
3. **Abra a pasta no VS Code**
4. **Clique com botão direito no `index.html`**
5. **Selecione "Open with Live Server"**
6. **A página abrirá automaticamente**

### **Método 3: Usar Python (Avançado)**
```bash
# No terminal, dentro da pasta do projeto:
python -m http.server 8000

# Depois acesse: http://localhost:8000
```

---

## 📱 **COMO TESTAR RESPONSIVIDADE:**

### **No Navegador:**
1. Abra a página
2. Pressione `F12` (ou Ctrl+Shift+I)
3. Clique no ícone de celular/tablet
4. Teste diferentes tamanhos de tela

### **Teste em Dispositivos:**
- **Desktop:** 1920x1080
- **Tablet:** 768x1024
- **Mobile:** 375x667

---

## 🚀 **COMO COLOCAR ONLINE:**

### **OPÇÃO 1: NETLIFY (Mais Fácil) ⭐**

1. **Acesse:** [netlify.com](https://netlify.com)
2. **Clique:** "Sign up" (criar conta)
3. **Escolha:** "Deploy manually"
4. **Arraste:** A pasta inteira com os arquivos
5. **Aguarde:** O deploy (alguns segundos)
6. **Pronto:** Seu site estará online!

**Vantagens:**
- ✅ Gratuito
- ✅ Fácil de usar
- ✅ HTTPS automático
- ✅ URL personalizada

### **OPÇÃO 2: VERCEL**

1. **Acesse:** [vercel.com](https://vercel.com)
2. **Clique:** "Sign up"
3. **Clique:** "New Project"
4. **Arraste:** A pasta com os arquivos
5. **Clique:** "Deploy"

### **OPÇÃO 3: GITHUB PAGES**

1. **Crie conta:** [github.com](https://github.com)
2. **Crie repositório:** "New repository"
3. **Upload:** Os arquivos
4. **Ative Pages:** Settings > Pages
5. **Escolha:** "Deploy from a branch"

---

## 🔍 **COMO VERIFICAR SE ESTÁ FUNCIONANDO:**

### **Testes Essenciais:**
1. ✅ **Página carrega** sem erros
2. ✅ **Menu mobile** funciona (hambúrguer)
3. ✅ **Botão WhatsApp** abre o app
4. ✅ **Link Instagram** abre o perfil
5. ✅ **Formulário** redireciona para WhatsApp
6. ✅ **Responsivo** funciona em mobile
7. ✅ **Animações** funcionam suavemente

### **Teste de Performance:**
- **Google PageSpeed:** [pagespeed.web.dev](https://pagespeed.web.dev)
- **GTmetrix:** [gtmetrix.com](https://gtmetrix.com)

---

## 🛠️ **PROBLEMAS COMUNS E SOLUÇÕES:**

### **Problema: Página não carrega**
**Solução:** Verifique se todos os arquivos estão na mesma pasta

### **Problema: Estilos não aparecem**
**Solução:** Verifique se o arquivo `styles.css` está na pasta

### **Problema: WhatsApp não abre**
**Solução:** Verifique o formato do número (sem +, sem espaços)

### **Problema: Instagram não abre**
**Solução:** Verifique se o link está correto

### **Problema: Formulário não funciona**
**Solução:** Verifique se o arquivo `script.js` está na pasta

---

## 📊 **ESTRUTURA DOS ARQUIVOS:**

```
cintila/
├── index.html          # Página principal
├── styles.css          # Estilos e cores
├── script.js           # Funcionalidades
├── README.md           # Documentação
└── GUIA_COMPLETO.md    # Este guia
```

---

## 🎯 **PRÓXIMOS PASSOS:**

1. **Personalize** as informações de contato
2. **Teste** localmente
3. **Ajuste** cores e textos
4. **Coloque online** usando Netlify
5. **Compartilhe** o link!

---

## 📞 **DICAS EXTRAS:**

- **Backup:** Sempre mantenha uma cópia dos arquivos
- **Teste:** Teste em diferentes navegadores
- **Mobile:** Priorize a experiência mobile
- **Velocidade:** Mantenha as imagens otimizadas
- **SEO:** Use títulos e descrições claras

---

**🎨 Cintila Design - Transformando ideias em arte visual!**



