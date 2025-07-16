
# 🖼️ HTML - Inserindo Imagens (Capítulo 06 - Aula 04)

📅 Criado em: **15 de julho de 2025**  
📚 Matéria: **Desenvolvimento Web / HTML**  
✍️ Autor: **Marco**

---

## 🎯 TEMA: Como inserir imagens em documentos HTML

---

## 1. 🖼️ A Tag `<img>`

- Usada para **exibir imagens** em uma página web.
- É uma tag **vazia** (não possui fechamento).
- Exemplo simples:
  ```html
  <img src="caminho/para/imagem.jpg" alt="Descrição da imagem">
  ```

---

## 2. 🧩 Atributos Essenciais

### 🔗 `src` (source)
- Caminho da imagem (obrigatório).
- Pode ser **relativo** ou **absoluto**.
  ```html
  <img src="img/logo.png">
  ```

### ♿ `alt` (alternative text)
- Descrição da imagem (obrigatório).
- Essencial para **acessibilidade** e **SEO**.
- Aparece quando a imagem não é carregada.
  ```html
  <img src="logo.png" alt="Logotipo da empresa X">
  ```

---

## 3. 📏 Atributos de Dimensionamento

- Usados para definir largura e altura diretamente no HTML.
- Preferencialmente, use CSS. Mas no HTML:
  ```html
  <img src="foto.jpg" alt="Pessoa sorrindo" width="300">
  <img src="foto.jpg" alt="Pessoa sorrindo" height="200">
  ```

- Dica: use apenas `width` ou `height` para manter proporção.

---

## 4. ✅ Boas Práticas

- Sempre defina o atributo `alt`.
- Otimize o tamanho dos arquivos de imagem.
- Mantenha imagens organizadas em uma pasta (`img/` ou `images/`).
- Prefira **caminhos relativos** para flexibilidade.
- Entenda os formatos:
  | Formato | Uso |
  |--------|-----|
  | `.jpg` / `.jpeg` | Fotos com muitos detalhes |
  | `.png` | Transparência e ícones |
  | `.gif` | Animações simples |
  | `.svg` | Imagens vetoriais escaláveis |
  | `.webp` | Alta compressão, bom para performance |

---

## 5. 🧪 Exemplo Prático

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Imagem em HTML5</title>
</head>
<body>

    <h1>Minha Página com Imagens</h1>

    <img src="imagens/logo-empresa.png" alt="Logotipo da minha empresa" width="150">

    <p>Esta é a logo da nossa empresa, um ícone que representa nossos valores.</p>

    <img src="https://picsum.photos/400/250" alt="Paisagem aleatória com montanhas e rio" width="400" height="250">

    <p>Uma bela paisagem para ilustrar nosso conteúdo.</p>

    <img src="imagens/icone-info.png" alt="Ícone de informação" width="50">

    <p>Clique no ícone acima para mais informações.</p>

</body>
</html>
```

---

### 📌 Resumo Final

- Use `<img>` com os atributos `src` e `alt` sempre.
- Prefira caminhos relativos.
- Cuide da performance e da acessibilidade.
- Conheça os formatos ideais para cada situação.

---
