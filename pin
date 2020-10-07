#include <stdio.h>
#include <stdlib.h>

int main(int argc, char *argv[]) {
	int pin, tentativi, nuovo;

	
	tentativi=1;
	printf("tentativo n%d \nPIN: ",tentativi); scanf("%d",&pin);
	
	while(pin!=64578 && tentativi<3){ // pin!=64578
	
		printf("ERR tentativo n%d \n",tentativi);
		
		tentativi++;
		
		printf("\ntentativo n%d \nPIN: ",tentativi);
		
		scanf("%d",&pin);
	
	}
	
	if (pin!=64578){
	
		printf("ERR tentativo n%d \n",tentativi);
	
	}
	
	nuovo=8;
	
	if(tentativi!=3 && pin==64578){
		
		printf("\nVuoi campiare il PIN? \n1=si\n0=no\n: "); scanf("%d",&nuovo);
	  
	}
		
	if (nuovo==1){
	  
	  printf("\nNuovo PIN: "); scanf("%d",&pin);
	  
	}else if(nuovo==0){
		
		printf("\nIl PIN rimane invariato buona giornata\n :)");
			
	}else if(pin!=64578 && tentativi==3){
		
		printf("\nPIN non valido.\nHai sbagliato per %d volte.\nERROR:\nX_X",tentativi);
		
	}else if(pin==64578 && tentativi==3){
		
		printf("\nBravo ci sei riuscito in %d tentativi\n",tentativi);
		
	}
  
	if (nuovo==1){
		
		printf("\nEcco il Nuovo PIN: %d\n",pin);
	  
	}
			
		return 0;
	}
