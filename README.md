# 🔐 Cifra de César

Projeto de criptografia em **C**: você escreve uma palavra e o programa a embaralha, transformando-a em outra palavra criptografada.

##  Objetivo

Implementar a **Cifra de César**, uma das técnicas de criptografia mais antigas que existem. Cada letra do texto original é substituída por outra letra que está um número fixo de posições à frente no alfabeto (a chamada *chave* ou *deslocamento*).

Exemplo com deslocamento 3:

```
A → D    B → E    C → F    ...    X → A    Y → B    Z → C
```

##  Funcionalidades

- Recebe uma palavra digitada pelo usuário
- Embaralha as letras aplicando o deslocamento da cifra
- Exibe a palavra criptografada
- Mantém o comportamento circular do alfabeto (depois do `Z` volta para o `A`)

## 🛠️ Tecnologias

<div data-importer="techs" align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="35" alt="c logo"  />
  <img width="12" />
</div>
<br>
- Compilador GCC (ou qualquer compilador C compatível)

##  Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/YagoMarcal/Cifra-de-Cesar.git
   cd Cifra-de-Cesar
   ```
2. Compile o código (ajuste o nome do arquivo `.c` se for diferente):
   ```bash
   gcc main.c -o cifra
   ```
3. Execute:
   ```bash
   ./cifra
   ```
   No Windows: `cifra.exe`

## Exemplo de uso

```
Digite uma palavra: CASA
Palavra criptografada: FDVD
```

> O resultado depende do deslocamento utilizado no código.

## O que este projeto pratica

- Manipulação de strings e vetores de caracteres em C
- Tabela ASCII e operações com `char`
- Estruturas de repetição
- Conceitos básicos de criptografia

## 👤 Autor

Feito por **Yago Marçal** — [@YagoMarcal](https://github.com/YagoMarcal)
