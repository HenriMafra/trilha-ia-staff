# 🧭 Trilha IA Staff — Engenharia & Pesquisa

Plataforma educacional imersiva estruturada em **3 Trilhas de Alta Performance** (Sistemas de IA & LLMOps, AppSec & AI Security, e Sistemas de Baixo Nível / GPU).

---

## 🔒 Segurança e Cifragem em Repouso

Este repositório opera sob o protocolo de **Cifragem de Ponta a Ponta em Repouso (Zero Plaintext Storage)**:
* **Algoritmo:** AES-256-GCM com autenticação criptográfica de integridade de 128 bits.
* **Derivação de Chave:** PBKDF2 com HMAC-SHA-256, 100.000 iterações e sal criptográfico pseudo-aleatório.
* **Execução em Borda:** O conteúdo é descriptografado exclusivamente em tempo de execução na memória volátil do navegador mediante autenticação da chave mestra autorizada.
* **Proteção contra Força Bruta:** Taxa de derivação endurecida e retardo progressivo de autenticação.
