# Tópicos Avançados em Pesquisa Operacional

> 🇺🇸 [English Version](README.md)

Este repositório contém algoritmos práticos, técnicas de simulação e códigos desenvolvidos durante a disciplina de **Tópicos Avançados em Pesquisa Operacional** (nível de Mestrado) no Instituto Federal da Paraíba (IFPB), ministrada pelo Prof. Thiago Gouveia da Silva.

Como aluno da graduação convidado a cursar esta disciplina de pós-graduação, mantenho este repositório como um diário de bordo técnico (*devlog*) para documentar meu processo de aprendizado, experimentos e implementações em C++.

## Tecnologias & Requisitos
* **Linguagem:** C++ (C++17 ou C++20)
* **Compilador:** `g++`

## Registro de Aulas
As aulas estão organizadas cronologicamente utilizando o padrão ISO 8601 (`YYYY-MM-DD`):
| Data | Tópico | Descrição |
| :--- | :--- | :--- |
| `2026-08-31` | [Simulação de Monte Carlo](./2026-08-31-monte-carlo) | Implementação em C++ de técnicas de simulação de Monte Carlo usando a biblioteca padrão `<random>`. |

## Compilação e Execução
Para compilar e executar o código de qualquer aula usando o `g++`:
```bash
# 1. Clonar o repositório
git clone [https://github.com/TheoNogueiraVirginio/advanced-operations-research.git](https://github.com/TheoNogueiraVirginio/advanced-operations-research.git)

# 2. Navegar até a pasta da aula
cd advanced-operations-research/2026-08-31-monte-carlo

# 3. Compilar com o padrão C++17 e otimização -O2
g++ -std=c++17 -O2 main.cpp -o main

# 4. Executar o binário
./main
