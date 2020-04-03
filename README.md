# Miskatonic-university
#include <iostream>
#include <fstream>

using namespace std;

int main(){
     ofstream FILE;
     FILE.open("text.txt");
     FILE << ".Э.Д.В.А.Р.Д. .Н.И.Г.М.А.";
     FILE.close();
    return 0 ;
}
