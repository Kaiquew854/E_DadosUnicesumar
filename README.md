# E_DadosUnicesumar

A ANTT (Agência Nacional de Transportes Terrestres) concedeu a empresa rodoviária Blugin Tur a autorização de funcionamento para os 5 (cinco) destinos ilustrados pela figura a seguir

![image](https://user-images.githubusercontent.com/80990220/201474245-7696cb81-5af2-4c18-9426-a6fecbdc7f4d.png)

Porém, devido a pandemia em 2020 e parte de 2021, a empresa vai diminuir esses destinos, passando a operar os destinos que representam o menor custo organizacional.

No contexto da figura, os vértices 1, 2, 3, 4 e 5 representam, respectivamente, as cidades que a companhia rodoviária opera hoje. O trajeto é representado pelas arestas que liga (1 a 2), (1 a 3), (2 a 3), (2 a 5), e assim por diante.
O custo (peso) entre cada conexão está representado por 2. Porém, de fato, o valor real do custo são os 7 primeiros dígitos do seu RA multiplicado por 100, na sequência: (1-2), (1-3), (2-3), (2-5), (3-4), (3-5), (4-5).

Exemplo:
RA 2025703-5 = Utilizar 2025703
RA 202570-5 = Em caso de 6 digitos, acrescentar o digito 1, neste exemplo teremos 2025701

Considerando o contexto apresentado da empresa rodoviária Blugin Tur, imagine que você é um desenvolvedor da empresa e ficou responsável por elaborar  o caminho de menor custo saindo da cidade 1 e chegando na cidade 5. Para atender a esta demanda você decidiu utilizar o algoritmo de Dijkstra, para indicar os destinos que continuarão sendo operados pela companhia o seu respectivo peso. 

Passos para realizar o mapa:
1 - Desenvolva um programa em linguagem C e salve com a extensão (.c) que informe os caminhos saindo de 1 e chegando em 5.
1.1 - Neste código, você deverá informar:
      - o número de vértices,
      - depois a aresta de origem, a aresta de destino, e
      - o custo correspondente aos digitos de seu RA para as rotas (lembre-se que após digitar o custo, temos uma operação a ser realizada).
1.2 - Imprimir todos os destinos com os seus respectivos pesos.

2 - Após a impressão (item 1.2) tirar um print da sua tela de forma que pegue todos os destinos.
   - Neste print marque o (s) caminho (s) de menor custo saindo de 1 e chegando em 5.
   - Salve com extensão (.doc), (.docx), (.pdf), (.png) e (.jpg).
   
   ![image](https://user-images.githubusercontent.com/80990220/201474296-cdeca20d-9548-4d28-827c-497b9c89b7a7.png)
