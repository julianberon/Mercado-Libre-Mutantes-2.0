# 🧬 Mutant Detection API

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://example.com) [![Java](https://img.shields.io/badge/Java-17-blue)](https://adoptopenjdk.net/) [![License](https://img.shields.io/badge/license-MIT-lightgrey)](LICENSE)

## 📝 Descripción

Proyecto Java **Spring Boot** que expone una API REST para detectar si una secuencia de ADN corresponde a un mutante. La lógica identifica **más de una secuencia de cuatro letras iguales** `(A, T, C, G)` en horizontal, vertical o diagonal.

## 🛠️ Tecnologías

| Tecnología | Versión |
|---|---|
| **Java** | 17 |
| **Spring Boot** | - |
| **Maven** | - |
| **Spring Data JPA** | H2 en memoria |
| **Swagger/OpenAPI** | Documentación automática |

## ⚡ Inicio Rápido

### Compilar y ejecutar tests

```powershell
./mvnw.cmd -B clean test
