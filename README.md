# 🎬 Huobao Drama - AI Short Drama Platform / Plataforma de Mini-series con IA

<div align="center">

**Full-stack AI short drama production platform based on Go + Vue3**
**Plataforma de producción automatizada de mini-series basada en Go + Vue3**

[![Go Version](https://img.shields.io/badge/Go-1.23+-00ADD8?style=flat&logo=go)](https://golang.org)
[![Vue Version](https://img.shields.io/badge/Vue-3.x-4FC08D?style=flat&logo=vue.js)](https://vuejs.org)
[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

[English](#-english) • [Español](#-español) • [Quick Start / Inicio Rápido](#-quick-start--inicio-rápido)

</div>

---

## 🇺🇸 English

### 📖 Project Overview
**Huobao Drama** is an AI-powered short drama production platform that automates the entire workflow: from script generation and character design to storyboarding and final video composition.



### 🎯 Core Value
* **🤖 AI-Driven**: Parse scripts using LLMs to extract characters, scenes, and storyboard metadata.
* **🎨 Intelligent Creation**: AI-generated character portraits and consistent scene backgrounds.
* **📹 Video Generation**: Automatic storyboard video generation using Text-to-Video and Image-to-Video models.
* **🔄 Integrated Workflow**: A complete production pipeline from creative idea to final export.

### 🛠️ Technical Architecture
The project follows **Domain-Driven Design (DDD)** principles:
* **API Layer**: Gin (HTTP)
* **Application Layer**: Business Logic
* **Domain Layer**: Core Models & Logic
* **Infrastructure Layer**: Database (SQLite) & External AI Services

---

## 🇪🇸 Español

### 📖 Descripción del Proyecto
**Huobao Drama** es una plataforma de producción de mini-series (short dramas) impulsada por IA que automatiza todo el flujo de trabajo: desde la creación del guion y el diseño de personajes hasta el storyboard y la composición final del video.

### 🎯 Valor Principal
* **🤖 Impulsado por IA**: Análisis de guiones mediante LLMs para extraer personajes, escenas y metadatos técnicos.
* **🎨 Creación Inteligente**: Generación de retratos de personajes y fondos de escena consistentes mediante IA.
* **📹 Generación de Video**: Conversión automática de storyboards a video mediante modelos de Texto-a-Video e Imagen-a-Video.
* **🔄 Flujo Integrado**: Pipeline de producción completo, desde la idea inicial hasta el archivo final.

### 🛠️ Arquitectura Técnica
El proyecto utiliza un diseño orientado a dominios (**DDD**):
* **Capa de API**: Gin (HTTP)
* **Capa de Aplicación**: Lógica de Negocio
* **Capa de Dominio**: Modelos y lógica central
* **Infraestructura**: Base de datos (SQLite) y servicios de IA externos

---

## 🎥 Demo / 作品展示

<div align="center">

| Example 1 / Ejemplo 1 | Example 2 / Ejemplo 2 |
| :---: | :---: |
| [Watch Video 1](https://ffile.chatfire.site/cf/public/20260114094337396.mp4) | [Watch Video 2](https://ffile.chatfire.site/cf/public/fcede75e8aeafe22031dbf78f86285b8.mp4) |

</div>

---

## 🚀 Quick Start / Inicio Rápido

### 📋 Prerequisites / Requisitos

| Software | Version | Note / Nota |
|----------|---------|-------------|
| **Go** | 1.23+ | Backend runtime |
| **Node.js** | 18+ | Frontend build |
| **FFmpeg** | 4.0+ | **Required** for video / **Obligatorio** para video |

### 📥 Setup / Instalación

```bash
# Clone the repository / Clonar el repositorio
git clone [https://github.com/chatfire-AI/huobao-drama.git](https://github.com/chatfire-AI/huobao-drama.git)
cd huobao-drama

# Install Backend dependencies / Instalar Backend
go mod download

# Install Frontend dependencies / Instalar Frontend
cd web
npm install
cd ..
