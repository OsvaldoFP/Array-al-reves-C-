# Array-al-reves-C-
Este código en C++ solicita al usuario diez números, los almacena en un arreglo, y luego imprime el arreglo en el orden ingresado y al revés.


  
  
  
    #include<iostream>
    using namespace std;
    int main(){
    
    int i=0,j=0;
    int org[10];
    int alr[10];
    
    for(int cont=1;cont<=10;cont++){
        cout<<"Dame el numero "<<cont<<" : ";
		cin>>org[i];
		alr[j]=org[i];
		j++;
		i++;        
        }
          
    i=0;  
    cout<<"Arreglo original: ";
    for(int cont2=0;cont2<9;cont2++){
        cout<<org[i]<<", ";
        i++;
        }
        
    i=9;
    cout<<org[i];
    cout<<endl;
    
    j=9;
    cout<<"Arreglo al reves: ";
    for(int cont3=0;cont3<9;cont3++){
      	
        cout<<alr[j]<<", ";
 		j--;
        }
	j=0;
	cout<<alr[j];	 
    
    
    return 0;
    }
