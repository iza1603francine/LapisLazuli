<p align="center">
  <img src="https://img.shields.io/static/v1?label=Android&message=Studio&color=3DDC84&style=for-the-badge&logo=android"/>
  <img src="https://img.shields.io/static/v1?label=Kotlin&message=1.9%2B&color=7F52FF&style=for-the-badge&logo=kotlin"/>
  <img src="https://img.shields.io/static/v1?label=Room&message=2.x&color=FFA500&style=for-the-badge&logo=sqlite"/>
  <img src="https://img.shields.io/static/v1?label=Status&message=Em%20Desenvolvimento&color=yellow&style=for-the-badge"/>
  <img src="https://img.shields.io/static/v1?label=License&message=MIT&color=green&style=for-the-badge"/>
</p>

<h1 align="center">🧠 Diário Interativo de Saúde Mental</h1>

---

## 📑 Índice

- [📝 Descrição](#-descrição)
- [🎯 Objetivo](#-objetivo)
- [📜 Licença](#-licença)
- [🗺️ Estrutura do Projeto](#️-estrutura-do-projeto)

---

## 📝 Descrição

O **Diário Interativo de Saúde Mental** é um aplicativo Android desenvolvido com foco em bem-estar e autocuidado.  
Através de um **calendário interativo**, o usuário registra sentimentos, pensamentos e acontecimentos diários.  
As anotações podem ser **exportadas para PDF**, facilitando o acompanhamento terapêutico e pessoal.

---

## 🎯 Objetivo

- Estimular o autoconhecimento por meio da escrita diária.  
- Registrar o estado emocional ao longo do tempo.  
- Gerar relatórios e visualizações úteis para o acompanhamento da saúde mental.  
- Oferecer uma interface acessível, privada e intuitiva.  

---

## 📜 Licença

MIT License

Copyright (c) 2025 iza.francine

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

## 🗺️ Estrutura do Projeto

```plaintext
diario-saude-mental/
├── data/              → Entidade, DAO e banco de dados Room
├── repository/        → Lógica de acesso aos dados
├── viewmodel/         → ViewModel com LiveData
├── ui/                → Telas (XML ou Compose)
├── util/              → Utilitários (PDF, datas, cores)
├── res/               → Layouts, drawables e valores
├── AndroidManifest.xml
└── build.gradle

---



