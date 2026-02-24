# Bússola Trader - Landing Page

Site de vendas profissional para o app Bússola Trader.

## 🚀 Como publicar no Vercel

### 1. Fazer upload dos arquivos

1. Acesse: https://vercel.com
2. Clique em "Add New" → "Project"
3. Clique em "Upload Files"
4. Faça upload de todos os arquivos desta pasta:
   - index.html
   - styles.css
   - script.js
5. Clique em "Deploy"

### 2. Conectar domínio

Depois que o site estiver publicado:

1. No painel do Vercel, vá em "Settings" → "Domains"
2. Clique em "Add Domain"
3. Digite: `bussola-trader.com.br`
4. O Vercel vai mostrar registros DNS para você configurar

### 3. Configurar DNS no Registro.br

1. Acesse: https://registro.br
2. Faça login
3. Vá em "Meus Domínios" → selecione `bussola-trader.com.br`
4. Clique em "DNS" ou "Servidores DNS"
5. Adicione os registros que o Vercel mostrou

**Registros típicos:**
```
Tipo: A
Nome: @
Valor: 76.76.21.21

Tipo: CNAME
Nome: www
Valor: cname.vercel-dns.com
```

6. Aguarde 10-30 minutos para propagar

### 4. Testar

Acesse `https://bussola-trader.com.br` e veja seu site no ar! 🎉

## 📝 Notas

- Os links dos botões já estão apontando para o app Mocha
- As redes sociais (Instagram/YouTube) estão prontas, basta criar as contas
- O site é 100% responsivo (funciona em mobile)

## 🎨 Personalização

Para mudar cores, edite as variáveis no `styles.css`:

```css
:root {
    --primary: #10B981;      /* Cor principal (verde)  */
    --bg-dark: #0F172A;      /* Fundo escuro */
    --bg-card: #1E293B;      /* Fundo dos cards */
}
```

## 📧 Contato

E-mail: contato@bussola-trader.com.br
