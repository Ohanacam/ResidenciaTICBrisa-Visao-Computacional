# AnemoVision

O **AnemoVision** é um sistema desenvolvido para automatizar a organização e filtragem de fotos de atendimentos em **usinas eólicas**, facilitando a busca por imagens específicas e melhorando a eficiência operacional, principalmente na criação de relatórios.

<div align="center">
    
![status](https://img.shields.io/badge/status-Finalizado-88CE02?style=for-the-badge)
</div>

## 📗 Sobre o Projeto

A **MKS Messtechnik Service** enfrentava desafios devido ao grande volume de imagens recebidas durante os atendimentos, muitas das quais não atendiam aos padrões de qualidade e organização necessários. Esse cenário dificultava a busca por imagens para a criação de relatórios e outros fins administrativos.

Para resolver esse problema, desenvolvemos o **AnemoVision**, um sistema avançado que utiliza técnicas de **visão computacional** e **Reconhecimento Óptico de Caracteres (OCR)** para automatizar a classificação e organização das fotos. O sistema identifica e categoriza imagens com base em características como:
- Tipo de dispositivo encontrado (ex.: anemômetro, odômetro, windvane)
- Número de série
- Data e hora do atendimento

Essas informações são armazenadas de forma estruturada e acessível, permitindo um gerenciamento eficiente do acervo de imagens da empresa.

![Demonstração](icons/gif_demonstracao.gif)

## Funcionalidades

- **Classificação Automática de Imagens**: Organiza as fotos automaticamente com base em metadados, como tipo de dispositivo e objetos presentes na imagem.
- **Reconhecimento Óptico de Caracteres (OCR)**: Detecta e extrai informações de texto das imagens, como data e hora.
- **Organização e Armazenamento de Dados**: Estrutura e armazena as imagens e seus metadados em pastas organizadas.
- **Interface de Usuário Amigável**: Interface simples e fácil de usar, com botões de navegação intuitivos.
- **Detecção de Objetos com Inteligência Artificial**: Utiliza modelos de **machine learning** para detectar objetos presentes nas imagens.

## 🎮 Interface

A interface do **AnemoVision** foi projetada para ser simples e eficiente, com dois botões principais:

1. **Carregar Pastas**: Permite ao usuário adicionar diretórios de imagens ao sistema. As fotos são automaticamente organizadas conforme metadados como o tipo de dispositivo, data, hora e localização.
   
2. **Ver / Buscar Imagens**: Oferece uma busca rápida e eficiente das imagens carregadas, permitindo filtrar por critérios específicos e acessar rapidamente as fotos desejadas.

## 📂 Como Usar

1. **Carregar Imagens**: Clique no botão "Carregar Pastas" e selecione o diretório de imagens a ser adicionado ao sistema.
2. **Buscar Imagens**: Utilize o botão "Ver / Buscar Imagens" para encontrar fotos organizadas com base nos critérios de busca.

Com o **AnemoVision**, a **MKS** consegue gerenciar de forma eficaz seu acervo de imagens, melhorando a produtividade e a precisão na criação de relatórios. A solução automatiza tarefas repetitivas e garante maior consistência e qualidade nos dados coletados, permitindo que os colaboradores se concentrem em atividades mais estratégicas.

---

## 🛠 Tecnologias

O projeto foi construído utilizando as seguintes ferramentas:

- [Yolo](https://github.com/ultralytics/yolov5) - Detecção de objetos com IA
- [Python](https://www.python.org/) - Linguagem de programação
- [EasyOCR](https://github.com/JaidedAI/EasyOCR) - Reconhecimento Óptico de Caracteres
- [OpenCV](https://opencv.org/) - Processamento de imagens
- [Pillow](https://python-pillow.org/) - Manipulação de imagens
- [Tkinter](https://docs.python.org/3/library/tkinter.html) - Desenvolvimento da interface gráfica

---

## 💻 Desenvolvedores
<div align="center">
<table>
    <tr>
        <td align="center">
            <a href="https://github.com/danielfklein">
                <br />
                <sub><b>DANIEL FELIPE KLEIN</b></sub>
            </a>
        </td>
        <td align="center">
            <a href="https://github.com/iggr1">
                <br />
                <sub><b>IGOR GABRIEL CAMARA</b></sub>
            </a>
        </td>
        <td align="center">
            <a href="https://github.com/Ohanacam">
                <br />
                <sub><b>OHANA CAMARGO DOS SANTOS</b></sub>
            </a>
        </td>
    </tr>
</table>
<div>
