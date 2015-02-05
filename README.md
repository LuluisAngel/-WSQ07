# -WSQ07
Here's the code

    #include <iostream>
    using namespace std;
    
    int main (){
    	int x, y, z, validacion, resultado, suma;
    
    	do{
    		cout << "Introduce el numero más pequeño" << endl;
    		cin >> x;
    
    		cout << "Introduce el numero más grande" << endl;
    		cin >> y;
    
    		if (x<y){
    			validacion = 0;
    		}
    			else {
    				cout << endl << "Escribiste los numeros mal, vuelve a intentarlo" << endl << endl;
    				validacion = 10;
    			}
    
    	} while (validacion==10);
    
    	if (validacion==0){
    
    		z = (y-x)+1;
    
    		suma = 0;
    
    		for (int i=0; i<z; i++){
    			
    			resultado = (x + i); 	
    			
    			suma = suma + resultado;	//
    		}
    
    		cout << "La suma de " << x << " a " << y << " = " << suma;
    
    	}
    	return 0;
    }
