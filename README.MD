## **A criatividade é tão importante quanto a técnica!**

Nos últimos meses, entrei de cabeça nos estudos. Aprendi o que é modelagem lógica e física, a diferença entre "CHAR e VARCHAR", o que é "obrigatoriedade e cardinalidade", etc.

E aí, parti pra prática! 

Vou explicar um pouquinho: fiz a modelagem, criei um banco de dados chamado "Playlist", no MySQL, com quatro tabelas: “Artista, Música, Disco e Ouvintes" e inseri as informações. 

Sobre a modelagem: O relacionamento entre artista e música é (1, n), ou seja, é obrigatório inserir ao menos um artista e uma música, mas posso inserir várias músicas de um único artista. 

A relação entre artista e disco também é (1, n), é obrigatório inserir um artista e um disco, mas posso inserir mais álbuns (considerando que Tim Maia, Djavan e Roberta Campos têm mais de uma música). 

Além disso, criei uma tabela com dados reais do Spotify, com número de seguidores e execuções mensais.

Esses dados podem ser atualizados, com novos álbuns, fãs e execuções, mas o objetivo é apena me desafiar, colocando o conhecimento em prática. 