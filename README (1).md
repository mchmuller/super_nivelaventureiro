
# 💡 Projeto Super Trunfo em C – Versão Interativa

Este projeto é a continuação do Super Trunfo em C, agora com **menu interativo** e **comparação de atributos** entre cartas. O foco deste desafio é aplicar estruturas de decisão (`switch` e `if-else`) para criar um jogo mais dinâmico e realista.

##  Conceitos aplicados

- Operadores relacionais e lógicos
- Estrutura `switch-case`
- Estruturas condicionais encadeadas (`if-else`)
- Cálculo de densidade demográfica
- Exibição formatada e lógica de comparação

##  O que o programa faz

- Armazena dados de **duas cartas** do Super Trunfo com informações de cidades fictícias
- Calcula a densidade demográfica (população / área)
- Exibe um **menu interativo** para o jogador escolher o atributo de comparação:
  - População
  - Área
  - PIB
  - Pontos turísticos
  - Densidade demográfica
- Compara os atributos e exibe o vencedor com base nas regras:
  - Em geral: vence quem tem o **maior valor**
  - Densidade demográfica: vence quem tem o **menor valor**
  - Em caso de empate: exibe "Empate!"

##  Como compilar e executar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/super_trunfo.git
cd super_trunfo
```

2. Compile o programa:
```bash
gcc super_trunfo_interativo.c -o super_trunfo_interativo
```

3. Execute:
```bash
./super_trunfo_interativo
```

##  Exemplo de uso

```
=== MENU DE COMPARAÇÃO ===
1. População
2. Área
3. PIB
4. Pontos turísticos
5. Densidade demográfica
Escolha o atributo para comparação: 1

Comparando: São Paulo (Código: A01) vs Rio de Janeiro (Código: B02)
Atributo: População
São Paulo: 12325000
Rio de Janeiro: 6748000
Resultado: São Paulo venceu!
```

## ✅ Requisitos atendidos

- [x] Menu com `switch`
- [x] Comparações com `if-else` aninhado
- [x] Regras de comparação específicas
- [x] Exibição clara e completa do resultado
- [x] Código limpo, funcional e comentado

---

Desenvolvido por: **Michele Cardoso**  
Curso: Ciência da Computação – Estácio  
Data: Julho/2025
