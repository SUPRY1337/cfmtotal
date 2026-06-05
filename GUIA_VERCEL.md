# 🚀 Guia: Colocar seu Site Online no Vercel (Permanente)

## O que é Vercel?
Vercel é uma plataforma **gratuita** que hospeda sites estáticos (como o seu) de forma permanente, rápida e segura. Seu site fica online 24/7 sem precisar manter um servidor ligado.

---

## 📋 Pré-requisitos
- Uma conta no **GitHub** (gratuita)
- Uma conta no **Vercel** (gratuita)
- Nada mais! Sem cartão de crédito necessário.

---

## ✅ Passo a Passo

### Passo 1: Criar uma Conta no GitHub (Se não tiver)
1. Acesse [github.com](https://github.com)
2. Clique em **"Sign up"** (Inscrever-se)
3. Preencha com seu email e crie uma senha
4. Confirme o email
5. Pronto! Você tem uma conta GitHub.

### Passo 2: Criar um Repositório no GitHub
1. Acesse [github.com/new](https://github.com/new)
2. Preencha assim:
   - **Repository name:** `site-prescricao` (ou qualquer nome)
   - **Description:** Clone de teste - Prescrição Eletrônica CFM
   - **Public:** Deixe marcado (para o Vercel conseguir acessar)
3. Clique em **"Create repository"**
4. Copie o link que aparecer (algo como: `https://github.com/seu-usuario/site-prescricao.git`)

### Passo 3: Fazer Upload dos Arquivos
Você tem 2 opções:

#### Opção A: Pelo Site do GitHub (Mais Fácil)
1. Abra seu repositório no GitHub
2. Clique no botão **"Add file"** > **"Upload files"**
3. Arraste todos os arquivos da pasta `site-permanente` para a área de upload
4. Clique em **"Commit changes"**

#### Opção B: Pelo Terminal (Para Desenvolvedores)
```bash
cd ~/site-permanente
git init
git add .
git commit -m "Primeira versão do site"
git branch -M main
git remote add origin https://github.com/seu-usuario/site-prescricao.git
git push -u origin main
```

### Passo 4: Conectar Vercel ao GitHub
1. Acesse [vercel.com](https://vercel.com)
2. Clique em **"Sign up"** (ou faça login se já tiver conta)
3. Escolha a opção **"Continue with GitHub"**
4. Autorize o Vercel a acessar suas contas do GitHub
5. Pronto! Você está conectado.

### Passo 5: Fazer Deploy do Site
1. No painel do Vercel, clique em **"New Project"** (Novo Projeto)
2. Procure pelo repositório **"site-prescricao"** (ou o nome que você deu)
3. Clique em **"Import"**
4. Deixe as configurações padrão e clique em **"Deploy"**
5. Aguarde 1-2 minutos...
6. **Pronto!** Seu site está online! 🎉

### Passo 6: Acessar seu Site
Após o deploy, o Vercel vai gerar uma URL assim:
```
https://site-prescricao-abc123.vercel.app
```

Você pode:
- ✅ Compartilhar esse link com qualquer pessoa
- ✅ Criar um QR Code apontando para esse link
- ✅ Deixar o site online para sempre (sem custos)

---

## 🔧 Atualizar o Site Depois

Se você quiser fazer mudanças no site:

1. **Edite os arquivos** no seu computador
2. **Faça upload** para o GitHub (mesmos passos do Passo 3)
3. **O Vercel atualiza automaticamente** em 1-2 minutos

Não precisa fazer nada mais! O Vercel detecta as mudanças e redeploy automaticamente.

---

## 🎯 Dicas Importantes

### Domínio Personalizado (Opcional)
Se você quiser um domínio tipo `seusite.com.br` em vez de `vercel.app`:
1. Compre um domínio em [Namecheap](https://www.namecheap.com/) ou [Registro.br](https://registro.br/)
2. No painel do Vercel, vá em **Settings** > **Domains**
3. Adicione seu domínio
4. Siga as instruções para apontar o DNS

### Certificado SSL (HTTPS)
O Vercel **já inclui HTTPS automaticamente**. Seu site é seguro por padrão! 🔒

### Limite de Tráfego
O Vercel permite até **100 GB de banda por mês** gratuitamente. Mais que suficiente para a maioria dos sites.

---

## ❓ Dúvidas Frequentes

**P: Meu site vai ficar online para sempre?**
R: Sim! Enquanto você não deletar o repositório no GitHub e o projeto no Vercel, ele fica online permanentemente.

**P: Preciso pagar algo?**
R: Não! Vercel é totalmente gratuito para sites estáticos.

**P: Posso ter múltiplos sites no Vercel?**
R: Sim! Você pode criar quantos repositórios quiser e fazer deploy de cada um.

**P: E se eu quiser tirar o site do ar?**
R: Basta deletar o projeto no painel do Vercel. Leva 2 cliques.

---

## 📞 Suporte
- **Documentação Vercel:** https://vercel.com/docs
- **Comunidade GitHub:** https://github.community

---

**Criado em:** 05/06/2026  
**Versão:** 1.0
