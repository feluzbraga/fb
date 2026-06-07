# Fernanda Braga — Site Portfolio

Site trilíngue (PT / EN / ES) hospedado gratuitamente no GitHub Pages.

## 📁 Estrutura de arquivos

```
fernandabraga-site/
├── index.html       ← site completo (único arquivo)
├── fernanda.png     ← sua foto
├── logo.png         ← logo da marca
└── README.md        ← este guia
```

---

## 🚀 Como publicar no GitHub (passo a passo)

### 1. Criar conta no GitHub
Acesse https://github.com e crie uma conta gratuita se ainda não tiver.

### 2. Criar repositório
- Clique em **"New repository"**
- Nome do repositório: `fernandabraga-site` (ou qualquer nome)
- Deixe como **Public**
- Clique em **"Create repository"**

### 3. Fazer upload dos arquivos
- Na página do repositório, clique em **"uploading an existing file"**
- Arraste todos os 4 arquivos: `index.html`, `fernanda.png`, `logo.png`, `README.md`
- Clique em **"Commit changes"**

### 4. Ativar GitHub Pages
- Vá em **Settings** → **Pages** (menu lateral esquerdo)
- Em "Source", selecione **"Deploy from a branch"**
- Branch: **main** / Folder: **/ (root)**
- Clique em **Save**

### 5. Aguardar publicação
Em 1–2 minutos, o site estará disponível em:
`https://SEU_USUARIO.github.io/fernandabraga-site/`

---

## 🌐 Conectar seu domínio fernandabraga.com.br

### No GitHub Pages:
- Settings → Pages → Custom domain
- Digite: `www.fernandabraga.com.br`
- Marque **"Enforce HTTPS"**
- Salve

### No painel do seu provedor de domínio (onde comprou o domínio):
Adicione estes registros DNS:

**CNAME** (para www):
```
Nome:  www
Valor: SEU_USUARIO.github.io
```

**A records** (para o domínio raiz, se quiser):
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

Aguarde até 24h para propagação do DNS.

---

## ✏️ Como editar o conteúdo

Abra o `index.html` em qualquer editor de texto (Bloco de Notas, VS Code, etc.).

- **Textos**: Edite diretamente no objeto `i18n` no final do arquivo (tem as 3 línguas: pt, en, es)
- **Foto**: Substitua o arquivo `fernanda.png` por uma nova foto com o mesmo nome
- **Cores**: As cores da marca estão no início do CSS em `:root { ... }`
- **Contato**: Procure por `wa.me/5511938024100` e `feluzbraga@gmail.com` para atualizar

---

## 🎨 Identidade visual aplicada

- **Roxo**: #5A2D82
- **Rosa**: #B46AA0  
- **Dourado**: #D4A14A
- **Creme**: #F2E9E4
- **Fonte**: Poppins (Google Fonts)
