# 📱 Como colocar o Aura Farm na Play Store
## Guia passo a passo — só precisa de navegador!

---

## PASSO 1 — Criar conta no GitHub (grátis, 5 min)

1. Acesse: https://github.com
2. Clique em **"Sign up"**
3. Digite seu e-mail, crie uma senha e um nome de usuário
4. Confirme o e-mail que vai chegar na sua caixa

---

## PASSO 2 — Criar o repositório (onde fica o projeto)

1. Após fazer login, clique no **"+"** no canto superior direito
2. Clique em **"New repository"**
3. No campo **"Repository name"** escreva: `aura-farm`
4. Deixe marcado como **Public**
5. Clique em **"Create repository"**

---

## PASSO 3 — Subir os arquivos (arrastar e soltar)

Você vai subir os arquivos deste ZIP no GitHub.
Os arquivos são:
- `www/index.html`
- `package.json`
- `capacitor.config.json`
- `.gitignore`
- `.github/workflows/build.yml`

**Como subir:**
1. Na página do repositório que você criou, clique em **"uploading an existing file"**
2. Arraste a pasta `aura-farm-github` inteira pra área que aparecer
   *(ou suba os arquivos um por um)*
3. Clique em **"Commit changes"**

> ⚠️ IMPORTANTE: a pasta `.github` começa com ponto — ela precisa ser enviada também!
> Se o seu computador esconder ela, procure como "mostrar arquivos ocultos" no Windows.

---

## PASSO 4 — Compilar o APK na nuvem (automático!)

1. Após subir os arquivos, clique na aba **"Actions"** no topo da página
2. Você vai ver o workflow **"Compilar APK - Aura Farm"** rodando automaticamente
3. Aguarde uns **5 a 10 minutos** (vai aparecer um círculo amarelo girando)
4. Quando ficar verde ✅, clique nele
5. Role a página até a seção **"Artifacts"**
6. Clique em **"aura-farm-apk"** para baixar o APK!

---

## PASSO 5 — Testar no seu celular

1. Mande o arquivo `app-debug.apk` pro seu celular (WhatsApp, e-mail, Drive)
2. No celular, vá em **Configurações → Segurança → Instalar apps desconhecidos**
   e ative para o app que você vai usar pra abrir o arquivo
3. Abra o APK e instale — o Aura Farm vai aparecer como app de verdade!

---

## PASSO 6 — Publicar na Play Store

Para subir na Play Store, o Google exige um APK **assinado** (diferente do de teste).
Quando chegar nessa etapa, chame o Claude no chat — ele vai gerar os arquivos
de assinatura e configurar tudo pra você!

O que você vai precisar nessa hora:
- Conta no Google Play Console: https://play.google.com/console (R$ 125, único)
- Ícone do app (1024x1024 px) — o Claude pode criar pra você
- Screenshots do jogo (o Claude também ajuda)
- Conta no AdMob para os anúncios: https://admob.google.com (grátis)

---

## ❓ Deu algum erro?

Se aparecer alguma mensagem vermelha no GitHub Actions, copia o texto e manda
pro Claude no chat — ele resolve!
