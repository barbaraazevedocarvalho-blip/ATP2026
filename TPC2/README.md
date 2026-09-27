## Manifesto do TPC2

Bárbara Azevedo Carvalho

A114311

<img width="1600" height="1155" alt="WhatsApp Image 2026-09-15 at 22 41 29" src="https://github.com/user-attachments/assets/f2db256c-b5ef-4305-b323-c3d91eaecd23" />

## Resumo
O objetivo deste TPC foi desenvolver duas modalidades do jogo de **"Adivinha o número" (entre 1 e 100)** em Python:

**Modalidade 1 (O Computador Adivinha)**:
O utilizador pensa num número e o programa tenta adivinhá-lo.
Utilizou-se o algoritmo de pesquisa binária através de um ciclo while, onde o programa calcula continuamente o ponto médio do intervalo (inferior + superior) // 2 com base no feedback do utilizador ("maior", "menor" ou "igual").
O programa contabiliza o número de tentativas e descarta entradas inválidas.

**Modalidade 2 (O Utilizador Adivinha)**:
O programa gera um número aleatório entre 1 e 100 recorrendo à função random.randint(1, 100).
O utilizador introduz palpites sucessivos e o programa responde com "maior!" ou "menor!".
O ciclo termina quando o utilizador acerta, exibindo o número total de tentativas utilizadas.
