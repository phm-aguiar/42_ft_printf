# 42_ft_printf

## Descrição
Este projeto é uma reimplementação da função printf original da biblioteca C. O objetivo é aprender a usar funções variáticas e a biblioteca `<stdarg.h>`.

## Funcionalidades
Suporte às flags básicas:

- `%s`: imprime uma string
- `%d`: imprime um número inteiro decimal
- `%p`: imprime um endereço de memória
- `%x`: imprime um número inteiro hexadecimal com letras minúsculas
- `%X`: imprime um número inteiro hexadecimal com letras maiúsculas
- `%c`: imprime um caractere
- `%i`: imprime um número inteiro decimal ou hexadecimal, dependendo do valor do argumento

Suporte às flags de formatação:

- `' '`: imprime um espaço antes do valor
- `+`: imprime um sinal positivo antes do valor, se o valor for positivo
- `0`: imprime zeros à esquerda do valor, se o valor for inteiro

## Como usar
Para usar a função `ft_printf`, basta chamá-la da mesma forma que a função `printf` original. Por exemplo:

```c
#include "ft_printf.h"

int main()
{
    printf("Hello, world!\n");
    ft_printf("Hello, world!\n");
    return (0);
}
```

Este código irá imprimir a seguinte saída:

```bash
Hello, world!
Hello, world!

```


## Testes
O projeto em breve terá um conjunto de testes para garantir que a função ft_printf esteja funcionando corretamente. Porem ele ja foi testado pelos testes automaticos da francinette.

## Desafios
Implementar suporte para as flags restantes da função printf original.
Implementar suporte para formatação de números flutuantes.
Implementar suporte para formatação de strings com formatação.

## Autor
Este projeto foi criado por phenriq2 cadet at 42.



## Licença
Este projeto é licenciado sob os termos da [Licença MIT](LICENSE). Consulte o arquivo [LICENSE](LICENSE) para obter detalhes sobre os direitos e limitações da licença.

---

**Nota:** Este projeto foi criado por phm-aguiar como parte do curso software engineer na 42sp. Sinta-se à vontade para contribuir, relatar problemas ou fornecer feedback para melhorias. Estou ansioso para colaborar com a comunidade de desenvolvedores.
