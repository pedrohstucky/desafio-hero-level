# Desafio Hero Level - Dio

Este é um projeto simples em JavaScript que classifica o nível de um herói com base na quantidade de experiência (XP). O usuário insere o nome do Herói e quantidade de XP, e o programa retorna o nível correspondente.

## Lógica de Classificação

A classificação é baseada na seguinte tabela de XP:

0 a 1.000 = Ferro
1.001 a 2.000 = Bronze
2.001 a 5.000 = Prata
5.001 a 7.000 = Ouro
7.001 a 8.000 = Platina
8.001 a 9.000 = Ascendente
9.001 a 10.000 = Imortal
10.001+ = Radiante

## Como executar o programa

- [Node.js](https://nodejs.org/) instalado em sua máquina

### Instalação
1. Clone o repositório:
```bash
git clone https://github.com/pedrohstucky/desafio-hero-level.git
cd desafio-hero-level
```

### Instale as dependências:
```bash
npm install prompt-sync
```

### Execução:
```bash
node src/index.js
```