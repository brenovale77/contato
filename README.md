# Site de contato — Breno Vale

Este pacote contém um site estático simples para publicar no GitHub Pages.

## Arquivos

- `index.html`: página principal com botão "Salvar contato".
- `contato.vcf`: arquivo vCard usado para salvar o contato.
- `qr-preview.png`: QR Code de exemplo apontando para a URL genérica `https://SEU_USUARIO.github.io/contato/`.

## Dados incluídos

- Nome: Breno Vale
- Cargo: Diretor Presidente
- Empresa: ABRINT
- E-mail: presidente@abrint.com.br
- Telefone/WhatsApp: +5561982770898
- Site: https://www.abrint.com.br
- LinkedIn: substituir `https://www.linkedin.com/in/SEU-USUARIO-LINKEDIN/` pelo link real.

## Como publicar no GitHub Pages

1. Crie um repositório público chamado, por exemplo, `contato`.
2. Faça upload de `index.html` e `contato.vcf` na raiz do repositório.
3. Vá em `Settings` > `Pages`.
4. Em `Build and deployment`, selecione `Deploy from a branch`.
5. Escolha o branch `main` e a pasta `/root`.
6. Salve.
7. A página ficará parecida com:
   `https://SEU_USUARIO.github.io/contato/`

## Onde trocar o LinkedIn

Troque o link em dois lugares:

### 1. No arquivo `index.html`

Procure por:

```html
https://www.linkedin.com/in/SEU-USUARIO-LINKEDIN/
```

Substitua pelo seu link real.

### 2. No arquivo `contato.vcf`

Procure por:

```text
URL;TYPE=LinkedIn:https://www.linkedin.com/in/SEU-USUARIO-LINKEDIN/
X-SOCIALPROFILE;TYPE=linkedin:https://www.linkedin.com/in/SEU-USUARIO-LINKEDIN/
```

Substitua pelo seu link real.

## Importante sobre QR Code

Depois que a página estiver publicada, o ideal é gerar um QR Code apontando para a URL final do site, por exemplo:

`https://SEU_USUARIO.github.io/contato/`

Assim você poderá atualizar telefone, e-mail, foto ou LinkedIn no GitHub sem precisar trocar o QR Code.
