![Alt text](https://g.gravizo.com/svg?%20digraph%20G%20{%20S%20-%3E%20S%20[label=%22_%22];%20S%20-%3E%20A;%20A%20-%3E%20S[label=%220-9%22];%20A%20-%3E%20A[label=%220-9%22];%20A%20-%3E%20B;%20B%20-%3E%20B%20[label=%22abc%22];%20B%20-%3E%20A;%20B%20-%3E%20S%20[label=%22abc%22];%20})

M -> A [label=" - "];
M -> A [label="0-9"];
A -> A [label="0-9"];
A -> B [label="."];
B -> B [label="0-9"];
B -> C [label="eE"];
C -> D [label="0-9"];
C -> E [label=" -"];
E -> D [label="0-9"];
D -> D [label="0-9"];
D -> F [label="0-9"];
D -> F [label="fFlL"];;
A -> F [label="0-9"];
B -> F [label="0-9"];


