# 💻 Curso HTML Completo (4 Horas) - Guia Prático

Este repositório contém os códigos e exercícios práticos desenvolvidos durante o curso. O foco aqui é aprender a **usar** as tags HTML para criar páginas web.

## 🔗 Acesso ao Curso
> **[Clique aqui para assistir ao Curso HTML Completo (4 Horas)](https://www.youtube.com/watch?v=nPEpaft1y1k)**

---

## 📑 Guia Rápido de Tags (Cheat Sheet)

Abaixo está a lista das principais tags utilizadas durante o curso para consulta rápida.

### 📝 Textos e Formatação
| Tag | Função | Exemplo |
| :--- | :--- | :--- |
| `<h1>` a `<h6>` | Títulos (do maior para o menor) | `<h1>Título Principal</h1>` |
| `<p>` | Parágrafo de texto | `<p>Olá mundo!</p>` |
| `<strong>` | Deixa o texto em **negrito** (importante) | `<strong>Texto forte</strong>` |
| `<em>` | Deixa o texto em *itálico* (ênfase) | `<em>Texto em itálico</em>` |
| `<br>` | Quebra de linha | `Texto<br>Texto baixo` |
| `<hr>` | Linha horizontal separadora | `<hr>` |

### 🔗 Links e Mídia
| Tag | Função | Exemplo |
| :--- | :--- | :--- |
| `<a>` | Cria links para outras páginas | `<a href="google.com">Ir para Google</a>` |
| `<img>` | Exibe imagens | `<img src="foto.jpg" alt="Descrição">` |
| `<video>` | Exibe vídeos | `<video src="video.mp4" controls>` |
| `<audio>` | Toca áudios | `<audio src="som.mp3" controls>` |
| `<iframe>` | Incorpora mapas ou vídeos do YouTube | `<iframe src="..."></iframe>` |

### 📋 Listas
| Tag | Função |
| :--- | :--- |
| `<ul>` | Lista **sem** ordem (bolinhas) |
| `<ol>` | Lista **ordenada** (1, 2, 3...) |
| `<li>` | Item da lista (usado dentro de ul ou ol) |

### 📊 Tabelas
| Tag | Função |
| :--- | :--- |
| `<table>` | Cria a tabela |
| `<thead>` | Cabeçalho da tabela |
| `<tbody>` | Corpo da tabela |
| `<tr>` | Linha da tabela |
| `<th>` | Célula de título (negrito) |
| `<td>` | Célula de dados comum |

### 📝 Formulários
| Tag | Função |
| :--- | :--- |
| `<form>` | Área do formulário |
| `<input>` | Campo de entrada (texto, senha, email) |
| `<label>` | Legenda para o input |
| `<textarea>` | Caixa de texto grande |
| `<button>` | Botão clicável |
| `<select>` | Menu suspenso (dropdown) |
| `<option>` | Opção do menu suspenso |

### 📦 Estrutura (Divisões)
| Tag | Função |
| :--- | :--- |
| `<div>` | Divisão genérica (bloco) |
| `<span>` | Divisão genérica (em linha) |
| `<header>` | Cabeçalho do site |
| `<main>` | Conteúdo principal |
| `<footer>` | Rodapé |

---

## 🏗️ Estrutura Básica (Template)

Todo arquivo HTML criado no curso começa com essa estrutura obrigatória:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nome da Página</title>
</head>
<body>

    </body>
</html>
