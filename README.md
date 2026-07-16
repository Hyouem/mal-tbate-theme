# TBATE MyAnimeList Theme

![Uploading Captura de tela 2026-07-16 132600.png…]()

Tema personalizado para a lista Classic do MyAnimeList, inspirado em **The Beginning After The End**, com:

- fundo widescreen do Arthur;
- lista translúcida;
- menu lateral à esquerda;
- lista posicionada à direita;
- paleta em tons de roxo;
- sem imagens extras nos títulos ou no menu.

---

## Nome do repositório

O repositório deve ser criado como:

```text
mal-tbate-theme
```

Na conta:

```text
Hyouem
```

O repositório deve ser:

```text
Public
```

A branch principal deve ser:

```text
main
```

---

## Arquivos que devem ser enviados

Depois de extrair o pacote, envie estes arquivos para o repositório:

```text
mal-tbate-theme/
├── assets/
│   └── arthur-background-widescreen.jpg
├── TBATE_MAL_FINAL.css
├── TBATE_MAL_FINAL.txt
└── README.md
```

### Importante

A pasta deve continuar se chamando exatamente:

```text
assets
```

A imagem deve continuar com o nome:

```text
arthur-background-widescreen.jpg
```

Não envie somente o arquivo ZIP para o GitHub.

Primeiro extraia o ZIP e depois envie os arquivos e a pasta `assets`.

---

## Como enviar para o GitHub

1. Abra o repositório `Hyouem/mal-tbate-theme`.
2. Clique em **Add file**.
3. Clique em **Upload files**.
4. Arraste para a página:
   - a pasta `assets`;
   - `TBATE_MAL_FINAL.css`;
   - `TBATE_MAL_FINAL.txt`;
   - `README.md`.
5. Confira se a imagem aparece no caminho:

```text
assets/arthur-background-widescreen.jpg
```

6. Em **Commit message**, use:

```text
Add final TBATE MAL theme
```

7. Clique em **Commit changes**.

---

## Como confirmar se a imagem está funcionando

Depois do commit, abra este endereço no navegador:

```text
https://raw.githubusercontent.com/Hyouem/mal-tbate-theme/main/assets/arthur-background-widescreen.jpg
```

Se a imagem abrir normalmente, o caminho está correto.

---

## Como aplicar no MyAnimeList

1. Abra o arquivo:

```text
TBATE_MAL_FINAL.txt
```

2. Copie todo o conteúdo.
3. Acesse o MyAnimeList.
4. Vá em:

```text
Profile
→ List Style Design
→ Advanced CSS List Design
```

5. Apague o CSS antigo.
6. Cole o conteúdo completo do arquivo `TBATE_MAL_FINAL.txt`.
7. Clique em **Update CSS**.
8. Confirme que sua lista está vinculada ao Style ID correto em:

```text
Change My List Style
```

9. Abra sua lista e atualize usando:

```text
Ctrl + F5
```

---

## Arquivos do projeto

### `TBATE_MAL_FINAL.css`

Versão final do código CSS.

Pode ser usada para edição e manutenção do tema.

### `TBATE_MAL_FINAL.txt`

Mesmo conteúdo do CSS, preparado para copiar e colar no editor do MyAnimeList.

### `assets/arthur-background-widescreen.jpg`

Imagem de fundo utilizada pelo tema.

### `README.md`

Instruções de instalação e organização do repositório.

---

## Atenção

O CSS depende deste endereço:

```text
https://raw.githubusercontent.com/Hyouem/mal-tbate-theme/main/assets/arthur-background-widescreen.jpg
```

Por isso, não altere:

- o nome da conta;
- o nome do repositório;
- o nome da branch;
- o nome da pasta `assets`;
- o nome da imagem.

Caso algum desses nomes seja alterado, o endereço da imagem dentro do CSS também precisará ser atualizado.
