# Char-tuto-IGA
/* I )gets / puts 
1 ) gets : peut être utilisé comme un scanf mais uniquement pour les chaine de caractères , et sans utiliser & et %c .
2 ) puts : peut être utilisé comme un printf mais uniquement pour les chaine de caractères et sans utiliser %c .*/

 II ) //stract : utiliser pour fusioner le continue de deux tableau
//exemple sur "stract"
#include<stdio.h>
#include<stdlib.h>
#include<string.h>

int main()
{
char nom[25],prenom[25] , *nom_complet;
 gets (nom);
get (prenom);
nom_complet=strcat(nom,prenom); // fusioner deux tableau (nom[n] et prenom[m])
puts(nom_complet);
system ("pause");
return 0;
}

III ) //strlen : utiliser pour calculer la taille d'une chaine de caracter 
//exemple sur "strlen"
#include<stdio.h>
#include<stdlib.h>
#include<string.h>

int main()
{
char nom[50];
int n;
 gets (nom);
n = strlen(nom);
printf(" la taille de votre nom est %d " , n);
system("pause");
return 0;
}

IV ) //strrev(nom_du_char ) : inverser la chaine de caracter 
//exemple sur strrev :
#include<stdio.h>
#include<stdlib.h>
#include<string.h>

int main()
{
char nom[50] , *nominv;

 gets (nom);
nominv = strrev(nom);

printf("  %s " , nominv);
system("pause");
return 0;
}


V ) // strcmp (tex1 , tex2) : comparer 2 chaines de caracter [Ali>Alaoui car i>a] 
exemple sur strcmp :
#include<stdio.h>
#include<stdlib.h>
#include<string.h>

int main()
{
char tex1[25] , tex2[25];
gets(tex1);
gets(tex2);
if(strcmp(tex1,tex2)<0)
{
  printf(" %s est inferieure a %s \n" , tex1 , tex2);
}
else if (strcmp(tex1,tex2)<0)
{
  printf(" %s est superieure a %s \n" , tex1 , tex2);
}
else
{
  printf(" %s et %s son egaux \n" , tex1 , tex2);
  system("pause");
return 0;
}

VI ) strcpy(tex1,tex2) // copie le contenu d'une chaine dans une autre de tex2 a tex1
exemple sur strcpy : 
#include<stdio.h>
#include<stdlib.h>
#include<string.h>

YOU KNOW

int main()
{
char tex1[25] , tex2[25];
gets(tex2);
strcpy(tex1,tex2);
puts(tex1);
 system("pause");
return 0;
}
