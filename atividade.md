# GitHub
**GitHub** é uma plataforma de hospedagem de código-fonte 
com controle de versão usando o Git. Ele permite que 
programadores, utilitários ou qualquer usuário cadastrado 
na plataforma contribuam em projetos privados e/ou Open 
Source de qualquer lugar do mundo.
<!--Texto retirado da wikipedia-->
* _Git_
* _GitHub_
* _Microsoft_
* _Social Code Hosting_
## Compra do GitHub pela Microsoft
Em 4 de junho de 2018, a **Microsoft** anunciou a compra da 
plataforma por US$ 7,5 bilhões, equivalente a R$ 27,225 bilhões 
_com dólar a "3,63" dia 06/06/2018_ . Satya Nadella, diretor executivo 
da **Microsoft**, reafirma a nova postura da **Microsoft** frente ao código aberto, 
dizendo: "A **Microsoft** é uma empresa que desenvolve em primeiro plano e, ao 
unir forças com o **GitHub**, fortalecemos nosso compromisso com a liberdade, a 
abertura e a inovação dos desenvolvedores. ~~Microsoft e código aberto?~~
<!-- Texto retirado da wikipedia-->
1. **Git**
2. **GitHub**
3. **Microsoft**
4. **Social Code Hosting**

### sub titulo 2
#### sub titulo 3
##### sub titulo 4

##### Logo a seguir, temos um simples código em C

#include <stdio.h>
#include <time.h>

int fat(int n){
	if(n==1)
		return 1;
	else{
		return n*fat(n-1);
	}
}

int main(){
	int fatorial, i, n;
	srand( (unsigned)time(NULL) );
	n = rand() % 5 + 1;
	fatorial = fat(n);
	for(i = 0; i < fatorial; i++)
		printf("%d: Ola Github\n",(i+1));
	
}




