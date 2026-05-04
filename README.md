# lnpg-cap8-selecao
Atividades do dia 30/02/2026

Ian Gabriel da Silva Santos

LLM: Gemini

## Análise: como sou iniciante em programação a única linguagem que tenho como referência é python, como uma língua que "domino". Em loops a quantidade de linhas não é tão discrepante, sendo Haskell a mais complicada de compreender a primeira vista, as outras consigo ter uma noção. Não somente em loops, mas em todos os outros códigos python é mais intuitivo, mais fácil de entender. 
  ## Na questão de loops, por exemplo, em Haskell:
      let kStart = (j + 13) `div` 27
      let loop k = if k <= 10 
              then loop (k + 1) -- i é calculado mas não persiste sem estado
              else k
    (Gerado por LLM)
  ## Enquanto em python:
     k = (j + 13) // 27
     while k <= 10:
     k += 1
     i = 3 * k - 1
     O loop em python é simples, facilmente identificável. Apesar de que a quantidade de linhas é igual, a maneira como o algoritmo é construido é mais simplório. De maneira mais "enxuta", concisa, o código se torna mais facilmente de ler e se tornar habitual. Em outro exemplo é o for:
     Em C#:
    for (int i = 0, j = 17; i < n; i++, j--) sum += i * j + 3;

     Em C++:
     for (int i = 0, j = 17; i < n; i++, j--) sum += i * j + 3;

    ## Em Python:
    ### for i, j in zip(range(n), range(17, 17 - n, -1)):
    sum += i * j + 3

    Apesar do número maior de linhas, Python continua sendo mais intuitivo.
