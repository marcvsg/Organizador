## Organizador de Arquivos Automático
Este é um script Python desenvolvido em Jupyter Notebook que organiza automaticamente arquivos em diretórios específicos baseado em suas extensões.

## 📋 Funcionalidades
Organiza arquivos nas seguintes categorias:
- 📸 Imagens (jpg, jpeg, png, gif, bmp, webp, svg, tiff)
- 🎥 Vídeos (mp4, avi, mov, mkv, wmv, flv, webm, m4v)
- 📄 Documentos (pdf, doc, docx, xls, xlsx, ppt, pptx, txt, rtf, odt, csv)
- 🗜️ Arquivos Compactados (zip, rar, 7z, tar, gz, bz2)
- ⚙️ Executáveis (exe, msi, dmg, pkg, deb, rpm)
- 🎵 Áudio (mp3, wav, aac, flac, ogg, m4a, wma)
- 💻 Código (py, js, html, css, java, c, cpp, h, json, xml)

## 🚀 Como Usar
Abra o arquivo py.ipynb em um ambiente Jupyter Notebook
Configure o diretório fonte substituindo "CONFIGURE SEU DIRETÓRIO AQUI" pelo caminho completo da pasta que deseja organizar
Execute todas as células do notebook em sequência


## 💻 Requisitos
Python 3.x
Jupyter Notebook
Bibliotecas Python:
os
shutil
pathlib


## ⚠️ Observações ⚠️
O script criará automaticamente as pastas necessárias se elas não existirem
Arquivos serão movidos (não copiados) para suas respectivas pastas
Certifique-se de fazer backup dos seus arquivos antes de executar o script

## 🛠️ Como Funciona
O script utiliza a biblioteca pathlib do Python para manipulação de arquivos e diretórios de forma moderna e eficiente. Ele identifica a extensão de cada arquivo no diretório fonte e o move para a pasta apropriada baseado em um dicionário de categorias predefinidas.
