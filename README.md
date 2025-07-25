
# BioBit + LLM Offline – Diagnóstico Inteligente

> 🧬 Diagnóstico explicável com IA local, por Diego Fernando Cruz  
> 🇧🇷 Desenvolvido em homenagem ao seu filho autista, Victor Katchor Cruz  
> 🇺🇸 Built in honor of his autistic son, Victor Katchor Cruz – from Brazil to the world!

---

## 🔍 O que este projeto faz / What this project does

✅ Gera **assinaturas binárias únicas** de exames (DNA, imagem, laudo, sinais)  
✅ Compara com um histórico de casos anteriores  
✅ Usa uma **LLM offline** (ex: Mistral, GPT4All) para gerar um laudo médico inteligente  
✅ **Roda totalmente offline**, ético, seguro, auditável  
✅ Saída bilíngue (Português / English)

---

## 📦 Requisitos / Requirements

- Python 3.8+
- Bibliotecas:
  ```bash
  pip install numpy pillow gpt4all
  ```
- Modelo LLM local (.gguf), ex:
  - `mistral-7b-openorca.Q4_0.gguf`  
    Baixar em: https://gpt4all.io

---

## 🧪 Arquivos esperados / Expected Files

| Tipo         | Exemplo              | Descrição |
|--------------|----------------------|-----------|
| DNA Fasta    | `tp53.fasta`         | Arquivo com sequência de DNA |
| Histórico    | `historico_casos.csv`| Lista com assinaturas anteriores e diagnósticos |
| Modelo LLM   | `.gguf`              | Modelo local para gerar laudo |

---

## ▶️ Como usar / How to use

1. Coloque o exame (`tp53.fasta`) e o `historico_casos.csv` na mesma pasta do script
2. Execute:
```bash
python biobit_llm_offline.py
```
3. Siga as instruções (nome do paciente, médico, etc)
4. O laudo inteligente será gerado e exibido no console

---

## ✏️ Como personalizar / How to customize

Deseja adicionar nome do paciente, data, ID, hospital?  
➡️ Use o input no início do script:
```python
paciente = input("Nome do paciente / Patient name: ")
```

Deseja gerar PDF ou salvar resultado?
➡️ Redirecione a saída ou use Python para salvar com `open('laudo.txt', 'w')`

---

## 🌍 Aplicações

- Hospitais, clínicas, pesquisa, universidade
- IA para diagnóstico de DNA, exames genéticos, apoio à triagem
- Inclusão de pacientes com autismo ou distúrbios raros

---

## ❤️ Sobre o autor / About the author

Diego Fernando Cruz é pai de Victor, um menino autista que inspirou este projeto.  
Ele desenvolveu o BioBit para tornar a ciência mais acessível, ética e humana.

> Nada é impossível para quem acredita e faz com amor.  
> Nothing is impossible for those who believe and build with love.

---

## 💳 Apoie o projeto / Support this project

**PIX (Brasil):** santander27@gmail.com  
**PayPal:** Diegocodigobits@gmail.com

## 🧬 Registro de Autoria – BioBit

**Arquivo:** `BioBit.py`  
**Hash SHA256:** `64DF0A8D1221F30D3C2A73E44D9923FD54E238DAD0DDBD6C62AE3C54E6C14DAF`  
**Autor:** Diego Fernando Cruz  
**Data:** 25/07/2025  
**Projeto dedicado a:** Victor Katchor Cruz  
**Descrição:** Motor biomédico inteligente que lê sequências de DNA (.fasta), gera assinaturas binárias únicas e utiliza LLM local para diagnósticos explicáveis em português e inglês.

> Esta assinatura digital serve como prova pública de autoria e originalidade, válida em disputas jurídicas e científicas.

