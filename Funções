#include <iostream>
using namespace std;

//Funções de leiuras.
void ler_vetor(string *vet, int tam) {
    for(int i = 0; i < tam; i++){
        cout << "Digite o nome do time: ";
        getline(cin, vet[i]); //O uso do getline permite pegar a linha inteira apesar de espaços
        cout << endl;
    }
}
void ler_matriz(int mat[3][3], int lin, int col, string vet[]) {
    for(int i=0; i < lin; i++) {
        for(int j=0; j < lin; j++) {
            cout << "Digite o resultado do " << j + 1 << "º jodo do" << vet[i] << ": ";
            cin >> mat[i][j];
            cout << endl;
        }
    }
}

//Funções para imprimir.
void printar_vetor(string vet[], int tam) {
    for(int i = 0; i < tam; i++)
        cout << vet[i] << " ";
    cout << endl;
}
void printar_matriz(int mat[3][3], int lin, int col, string vet[]) {
    for(int i=0; i < lin; i++) {
        cout << vet[i] << ": ";
        for(int j=0; j < lin; j++) {
            cout << mat[i][j] << " ";
        }
        cout << endl;
    }    
}

int main(){
    //Declaração de Variáveis
    string times[TIMES_TAM];
    int tabela[TIMES_TAM][TIMES_TAM];
    int linha = 2, coluna = 2;

    ler_vetor(times, linha);
    imprimir_vetor(times, linha);
    ler_matriz(tabela, linha, coluna, times);
    imprimir_matriz(tabela, linha, coluna, times);
}
