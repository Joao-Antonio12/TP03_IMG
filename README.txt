Para instalar a biblioteca SDL2:

*UNBUNTU/DEVIAN:
sudo apt-get install libsdl2-dev

*macOS:
brew install dsl2



*COMPILAR:

gcc -o visualizador_grafo main.c grafo.c leitura.c lista.c grafo_imagem.c -lSDL2 -lm

*CRIA UM EXECUTÁVEL CHAMADO: "visualizador_grafo"

*PARA RODAR O PROGRAMA:
./visualizador_grafo [número_do_livro]

*LEMBRADO QUE:
./visualizador_grafo 1    # Para analisar "A Guerra dos Tronos"
./visualizador_grafo 2    # Para analisar "A Fúria dos Reis"
./visualizador_grafo 3    # Para analisar "A Tormenta de Espadas"
./visualizador_grafo 4    # Para analisar "O Festim dos Corvos"
./visualizador_grafo 5    # Para analisar "A Dança dos Dragões"


