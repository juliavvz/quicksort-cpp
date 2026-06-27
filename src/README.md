# Quick Sort em C++

Implementação do algoritmo Quick Sort em C++.

## Entrada

```
{49, 38, 58, 87, 34, 93, 26, 13}
```

## Como compilar e executar

```bash
g++ quicksort.cpp -o quicksort
./quicksort
```

## Saída esperada

```
Vetor antes da ordenacao: 49, 38, 58, 87, 34, 93, 26, 13
Vetor apos a ordenacao:  13, 26, 34, 38, 49, 58, 87, 93
```

## Como funciona

O Quick Sort escolhe um pivô (último elemento), particiona o vetor colocando menores à esquerda e maiores à direita, e aplica o processo recursivamente em cada metade.

- **Melhor/médio caso:** O(n log n)  
- **Pior caso:** O(n²)
