# desafio-1
Imagine que voce foi contratado para desenvolver um sistema para gerenciar os armarios de alunos de uma universidade. Inicialmente, voce tera que fazer uma prova de conceito para 8 armarios. Devido as limitacoes de memoria no dispositivo onde seu codigo sera embarcado, voce optou por utilizar um mapa de bits. Dessa forma, para cada armario voce ira associar um bit, sendo 0 para disponıvel e 1 para ocupado. Voce devera usar uma UNICA variavel do tipo char sem sinal para controle. Nao utilize vetores. O sistema funcionara da seguinte forma: Inicialmente, voce deve exibir um menu para o usuario com as seguintes opcoes: 
1. Ocupar armario. 
2. Liberar armario. 
3. Sair. 
Sempre que o usuario digitar a opcao 1, voce deve escolher um armario aleatoriamente dentre os disponıveis e ocupar, ou seja, colocar o bit correspondente na variavel de controle em 1. O programa deve iniciar com todos os armarios desocupados. Quando o usuario digitar a opcao 2, o programa deve pedir a posicao do armario para ser desocupado e colocar o bit correspondente em zero na variavel de controle. O programa deve sair quando a opcao 3 for a escolhida pelo usuario. Observe a ilustracao abaixo:  
• Utilize operadores bit-a-bit para ligar e desligar os bits na variavel de controle e controlar quais armarios estao livres e quais estao ocupados. Nao use vetores. 
• Para geracao de numeros aleatorios, pesquise sobre a funcao rand(). 
• Em cada rodada do programa, apresente os armarios que estao ocupados e os que estao livres.
