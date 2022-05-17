 ## Números e Operações Matemáticas
    
 Possui 2 números principais: 
 → int: números inteiros, positivos ou negativos. Ex: -7 e 7;
 
 → float: números fracionários, positivos ou negativos. Ex: -7.1 e 7.1;
      Função type() identifica qual é o tipo de um número.
      
 → hex: número hexadecimal;
 
 → bin: número binário;
    
 → abs: retorna o valor absoluto (sempre positivo);
    
 → round: retorna o valor com arredondamento;
    
 → pow: potência do número;
    
 → str: sempre string;
    
 →len: retorna a quantidade de elementos de qualquer lista.
 
    
   | Operador Relacional | Significado |
   | --- | --- |
   | == | Igualdade/ Equivalência |
   | ! = | Desigualdade/Inequivalência |
   | > | Maior que |
   | < | Menor que |
   | > = | Maior que ou igual a |
   | < = | Menor que ou igual a |
   
    
   | Operador de Atribuição | Significado | Exemplo |
   | --- | --- | --- |
   | = | Atribuição | z = 10 |
   | + = | Soma | z += 10 (equivalente a z = z + 10) |
   | - = | Subtração | z -= 10 (equivalente a z = z - 10) |
   | *= | Multiplicação | z *= 10 (equivalente a z = z * 10) |
   | /= | Divisão | z /= 10 (equivalente a z = z / 10) |
   | %= | Módulo | z %= 10 (equivalente a z = z % 10) |
   | **= | Potência | z **= 10 (equivalente a z = z ** 10) |
   | //= | Divisão Inteira | z //= 10 (equivalente a z = z // 10) |
   
   
 ## Strings e Indexação em Python
    
 → String é uma sequência de caracteres imultáveis;
    
 → Python entende uma string sendo uma sequência de letras em uma ordem específica;
    
 → É usado a indexação(fatiamento) para obter um caractere específico de uma string;
    
 → É usado o [] para representar o índice de um objeto;
    
 → A indexação começa por 0;
    
   texto = "Python para Análise de Dados"
    
   texto[0] = P
    
   texto [1] = y
    
   texto [2] = t
    
 → Funções Built-in de Strings
    
 - As estruturas de dados possuem atributos e métodos, e os dois são acessados usando *ponto (.)*
        
   objeto.atributo
        
   objeto.método()
        
   objeto.método(parâmetros)
        
    
 ## Estruturas de Dados Python**
 
 Listas
       
 → Ao contrário de Strings, as listas são mútaveis, ou seja, os elementos dentro de uma lista podem ser alterados;
        
 → As listas são construídas com o uso de [] e vírgulas separando cada elemento da lista;
        
   lista = [item1, item2, ..., itemz]
        
 → Listas não tem tamanho fixo (o que significa que não precisamos especificar quão grande uma lista será);
        
 → Listas não tem restrições de tipo fixo
      
   
 ## Dicionários
        
 → Mapeamentos são uma coleção de objetos que são armazenados por uma chave, ao contrário de uma sequência de objetos armazenados por sua posição relativa;
        
 → Um dicionário Python consiste de uma chave e, em seguida, um valor associado. Esse valor pode ser quase qualquer objeto Python;
        
 → Dicionários são mapeamentos de chaves e valores:
        
   {chave1: valor1, chave2: valor2};
        
 → Os dicionários são construídos com o uso de chaves {} e vírgulas separando cada elemento do dicionário:
        
   dict = {k1:v1, k2:v2,  ..., kn:vn};
        
  ## Tuplas
        
→ As tuplas são imutáveis, não podem ser alteradas. Usa-se tuplas para apresentar dados que não devem ser alterados, como os dias da semana ou datas em uma calendário;
        
→ As tuplas são construídas com o uso de () e vírgulas separando cada elemento da tupla:
        
   tupla = (item1, item2, ..., itemz);
        
→ Tuplas são usadas quando é necessário imutabilidade. Se no programa precisa ter certeza que os dados não sofrerão alteração;
        
 ## Manipulação de listas
    
→ append(): Para adicionar um item ao final da lista;
    
→ len(): Calcular o tamanho da lista;
    
→ []: Acessar posições;
    
→ del(): Excluir um elemento;
    
→ clear(): Limpar a lista;
    
→ insert(): Para inserir um item de lista em um índice especificado;
    
→ extend(): Anexar elementos de outra lista à lista atual;
    
→ remove(): Remove o item especificado;
    
→ pop(): Remove o índice especificado;
    
→ sort(): Ordenar os valores;
    
→ copy(): Faz uma copia da lista;
    
→ index():Retorna o index do elemento da lista;
    
## Manipulação de Strings
    
→ replace(): Substitui parte da string por outro valor;
    
→ startswith(): Verifica como a string começa;
    
→ endswith(): Verifica como a string termina;
    
→ count(): Conta a quantidade de palavras/letras na string;
    
→ capitalize(): Retorna uma string onde o primeiro caractere é maiúsculo e o restante é minúsculo;
    
→ isdigit(): Retorna True se todos os caracteres forem numéricos, caso contrário, False;
    
→ isalnum(): Retornará True se todos os caracteres forem alfanuméricos, ou seja, letra do alfabeto (az) e números (0-9);
    
→ upper(): Transforma tudo em maiúsculo;
    
→ lower(): Transforma tudo em minúsculo;
    
→ find (): Encontra a primeira ocorrência do valor especificado e dá a posição;
    
→ strip(): Remove quaisquer caracteres iniciais (espaços no início) e finais (espaços no final);
    
→ split(): Separa a string em uma ou mais strings, baseando-se em um limitador.
