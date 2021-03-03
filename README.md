![Alt text](https://g.gravizo.com/svg?%20digraph%20G%20{%20S%20-%3E%20S%20[label=%22_%22];%20S%20-%3E%20A;%20A%20-%3E%20S[label=%220-9%22];%20A%20-%3E%20A[label=%220-9%22];%20A%20-%3E%20B;%20B%20-%3E%20B%20[label=%22abc%22];%20B%20-%3E%20A;%20B%20-%3E%20S%20[label=%22abc%22];%20})


![Alt text](https://g.gravizo.com/svg?
  digraph G {
    S -> S [label="_"];
    S -> A;
    A -> S[label="0-9"];
    A -> A[label="0-9"];
    A -> B;
    B -> B [label="abc"];
    B -> A;
    B -> S [label="abc"];
  }
)
