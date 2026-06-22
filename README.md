# Gallery Plus

# 📸 Galeria+ | Rocketseat Study Project

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="ReactJS" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS" />
  <img src="https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=react-query&logoColor=white" alt="React Query" />
</p>

---

## 📸 Demonstração da Aplicação

<p align="center">
  <img src="preview/dashboard-preview.jpg" alt="Página Inicial do Galeria+" width="49%" />
  <img src="preview/dashboard-preview1.jpg" alt="Detalhes da Imagem" width="49%" />
</p>

## 💻 Sobre o Projeto

O **Galeria+** é uma aplicação de gerenciamento e visualização de fotos desenvolvida como um projeto de estudo aprofundado em **ReactJS** através da plataforma **Rocketseat**. 

A aplicação simula um ecossistema real de upload, listagem dinâmica e categorização de imagens por álbuns, focando em boas práticas de componentização, gerenciamento de estado e consumo de APIs assíncronas.

## 🚀 Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias e ecossistema de bibliotecas:

* **![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ReactJS** – Biblioteca principal para construção da interface baseada em componentes.
* **![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) TypeScript** – Tipagem estática para garantir consistência dos dados (como as interfaces de `Photo` e `Album`).
* **![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwind-css&logoColor=white) Tailwind CSS & Tailwind Variants** – Estilização utilitária escalável com suporte nativo a variantes complexas de componentes.
* **![React Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat&logo=react-query&logoColor=white) TanStack Query (React Query)** – Gerenciamento de estado assíncrono, cache inteligente de dados da API e sincronização de estado.
* **![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat&logo=react-hook-form&logoColor=white) React Hook Form** – Performance e validação flexível de formulários (como no upload de novos arquivos).
* **![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat&logo=react-router&logoColor=white) React Router DOM** – Roteamento dinâmico para transição entre a timeline principal e as páginas de detalhes.

## 🛠️ Principais Conceitos Praticados

* **Manipulação de Arquivos no Client-Side:** Uso de `URL.createObjectURL` e gerenciamento de memória com `URL.revokeObjectURL` para previews de imagem em tempo real antes do upload.
* **Otimização de Renderização:** Prevenção de quebras no DOM através de chaves únicas estruturadas (`key`) combinando identificadores e indexadores para lidar com payloads da API.
* **Arquitetura Baseada em Hooks:** Abstração das regras de negócio e requisições HTTP em React Hooks customizados reutilizáveis (como `usePhotos` e `useAlbums`).
* **Uso de Skeletons e Estados de Loading:** Interfaces resilientes que exibem placeholders visuais estruturados enquanto as promises da API não são resolvidas.

## 🔧 Como Executar o Projeto

```
pnpm install
```

Em seguida, execute o servidor backend em um terminal.
```
pnpm dev-server
```

Em outro terminal, execute o servidor frontend.
```
pnpm dev
```
