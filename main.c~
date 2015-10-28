#include <stdio.h>
#include <stdlib.h>

int main()
{
FILE *fp;

   fp = fopen("/home/feer/test.txt", "w+");
   //fprintf(fp, "This is testing for fprintf...\n");
   //fputs("This is testing for fputs...\n", fp);
   putw("holas",fp);
   fclose(fp);


    int tam = 7;
    int limite = tam*tam;
    int matriz[tam][tam];
    int x,y;
    x = tam / 2;
    y = tam / 2;
    int arriba, abajo, izquierda, derecha;
    int contador = 1;
	//comentario gay    
//derecha = 2;
    //arriba = 1;
    //izquierda = 2;
    //abajo = 1;
// nueva version de este programa

    while (contador < limite + 1){
    //movimiento derecha
            for (int i = 0; i < derecha; i++) {
                matriz[x][y] = contador;
                contador++;
                y++;
            }

            if (derecha + 2 < tam) {
                derecha += 2;
            } else {
                derecha++;
            }
            if(contador >= limite)
                break;
//posicionamos en el lugar correcto
            x--;
            y--;
            //movimiento arriba
            for (int i = 0; i < arriba; i++) {
                matriz[x][y] = contador;
                contador++;
                x--;

            }
            if (arriba + 2 < tam) {
                arriba += 2;
            } else {
                arriba++;
            }

            //posicionamos en el lugar correcto
            x++;
            y--;

            //movimiento izquierda
            for (int i = 0; i < izquierda; i++) {
                matriz[x][y] = contador;
                contador++;
                y--;

            }
            if (izquierda + 2 < tam) {
                izquierda += 2;
            } else {
                izquierda++;
            }

            //posicionamos en el lugar correcto
            x++;
            y++;
            //movimeinto abajo
            for (int i = 0; i < abajo; i++) {
                matriz[x][y] = contador;
                contador++;
                x++;

            }
            if (abajo + 2 < tam) {
                abajo += 2;
            } else {
                abajo++;
            }

    }

    return 0;
}
