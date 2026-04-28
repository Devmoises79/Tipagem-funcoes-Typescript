# 🧠 Tipagem de Funções em TypeScript

📌 Visão Geral

Este projeto tem como objetivo demonstrar o uso de tipagem estática em funções com TypeScript, reforçando boas práticas de desenvolvimento, legibilidade de código e previsibilidade de comportamento em aplicações JavaScript modernas.

O foco está na construção de funções seguras, bem definidas e com retornos explícitos, reduzindo erros em tempo de execução.

# ⚙️ Funcionalidades

- Tipagem explícita de parâmetros em funções
- Definição de tipos de retorno (number, string, void, union types)
- Uso de funções tradicionais e arrow functions
- Manipulação de parâmetros dinâmicos com rest operator (...args)
- Demonstração de retornos condicionais com múltiplos tipos

# 🧠 Conceitos Aplicados (Engenharia de Software)

- 🟦 TypeScript — Tipagem Estática
- Definição explícita de tipos em parâmetros
- Garantia de consistência de dados em tempo de compilação
- Prevenção de erros comuns de JavaScript

# 🔁 Tipos de Retorno

- number → retorno numérico explícito
- string → retorno textual
- void → funções sem retorno
- union types (string | number) → flexibilidade controlada

# ⚙️ Funções e Estruturas
- Funções tradicionais com function
- Arrow functions para sintaxe concisa
- Funções variádicas com ...numeros: number[]

# 🧮 Lógica e Fluxo

- Condicionais com retorno dinâmico
- Inferência controlada de tipos
- Decisões baseadas em fluxo de execução

# 🧩 Exemplos Técnicos do Projeto

- 📐 Função com retorno explícito:

```bash
function calculaArea(base: number, altura: number): number {
    return base * altura;
}
```

-  ⚡ Arrow function tipada:
```bash
const calculaArea2 = (base: number, altura: number): number => base * altura;
```

- 📦 Função com múltiplos argumentos:
```bash

function somar(...numeros: number[]): void {
    console.log(numeros);
}
```

🔀 Retorno com múltiplos tipos
```bash
function teste(): string | number {
    if (10 > 5) {
        return 'Dez maior que cinco';
    } else {
        return 5;
    }
}
```

# ⚠️ Observação Técnica

O projeto é focado em conceitos fundamentais de tipagem em TypeScript, não em arquitetura de aplicação. Ele serve como base para evolução em:

- APIs tipadas
- Sistemas escaláveis em Node.js
- Aplicações front-end com React + TypeScript

# 🚀 Tecnologias Utilizadas

- TypeScript
- Node.js (ambiente de execução)
- Compilador TS (tsc)
  
# 📂 Estrutura do Projeto

- funcoes.ts → implementação das funções tipadas
- tsconfig.json → configuração do TypeScript

# 👨‍💻 Objetivo do Projeto

Este projeto foi desenvolvido com foco em:

- Fortalecer fundamentos de tipagem estática
- Melhorar previsibilidade de código
- Aplicar boas práticas de engenharia de software
- Preparação para ambientes profissionais com TypeScript
