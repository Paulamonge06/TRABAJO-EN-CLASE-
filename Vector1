#include <stdio.h>
int main(){
    FILE *archivo=NULL;
    FILE *archivoun=NULL;
    char buffer[100];
    double pi;
    int temp,aux;

    archivo=fopen("vector.txt","r+");
    archivoun=fopen("vectorun.txt","w");

    if(archivo==NULL){
        printf("No se puede abrir el archivo");
        return -1;
    }
    for(int i=0; i<100; i++){
        fscanf(archivo, "%d",&temp);
        aux=temp*3;
    fprintf(archivoun, "%d\n",aux);
    }
    fclose(archivo);
    fclose(archivoun);
    return 0;
}