/* Curriculum VITAE*/

#include <stdio.h>
#include<string.h>
#include<locale.h>

int main() 
{
  
setlocale(LC_ALL,"Portuguese");
  
char nome[50],endereco[50],bairro[50], cidade[50],estado[50];
char mail[50], obj[300], habc[300];
char formAc[300],formTec[300],experProf[300];
char cursQual[300],trabVol[300], interes[300];  
char tel1[15],tel2[15],App[15], cep[15], num[10];
  
printf("Digite o Nome Completo:");/* O usuário digita o nome completo*/
fgets(nome,50,stdin);
fflush(stdin);
  
/* Contatos felefônicos */
  
printf("Informe o telefone do Titular:");
fgets(tel1,15,stdin);
fflush(stdin);
  
printf("Informe o telefone Para Recado:");
fgets(tel2,15,stdin);
fflush(stdin);

printf("Informe o WhatsApp:");
fgets(App,15,stdin);
fflush(stdin);

printf("Informe o Endereço:");/* O usuário digita o endereço onde mora em seguida do número*/
fgets(endereco,50,stdin);
fflush(stdin);
  
printf("Informe o número da residencia:");
fgets(num,10,stdin);
fflush(stdin);
  
printf("Informe o Bairro:");/* O usuário digita o nome do bairro onde mora*/
fgets(bairro,50,stdin);
fflush(stdin);

printf("Informe a Cidade:");/* O usuário digita o nome da cidade onde reside em seguida do cep*/
fgets(cidade,50,stdin);
fflush(stdin);
  
printf("Informe o cep:");
fgets(cep,10,stdin);
fflush(stdin);
  
printf("Informe o Estado:");/* O usuário digita o estado onde mora*/
fgets(estado,50,stdin);
fflush(stdin);

printf("Informe o seu E-mail:");/*O usuário digita o e-mailde contato*/
fgets(mail,50,stdin);
fflush(stdin);

printf("Informe os seus Objetivos:");/* O usuário digita seus objetivos*/
fgets(obj,300,stdin);
fflush(stdin);

printf("Informe suas Habilidades e Competências:");/* O usuário digita suas habilidades e competências*/
fgets(habc,300,stdin);
fflush(stdin);

printf("Informe a sua Formação Acadêmica:");/* O usuário digita sua formação de ensino superior*/
fgets(formAc,300,stdin);
fflush(stdin);

printf("Informe a sua Formação Técnica:");/* O usuário digita sua formação técnica*/
fgets(formTec,300,stdin);
fflush(stdin);

printf("Informe a sua Experiência Profissional:");/* O usuário descreve sobre a sua experiência profissional*/
fgets(experProf,300,stdin);
fflush(stdin);

printf("Informe Sobre os Cursos de Qualificação:");/* O usuário descreve suas qualificações*/
fgets(cursQual,300,stdin);
fflush(stdin);

printf("Informe sobre Trabalhos Voluntarios:");/* Descreve sobre trabalhos voluntarios*/
fgets(trabVol,300,stdin);
fflush(stdin);

printf("Informe seus Interesses:");/* Descreve os interesses*/
fgets(interes,300,stdin);
fflush(stdin);
  
puts("resultado:");
  
puts(nome);
puts(tel1);
puts(tel2);
puts(App);
puts(endereco);
puts(num);
puts(bairro);
puts(cidade);
puts(cep);
puts(estado);
puts(mail);
puts(obj);
puts(habc);
puts(formAc);
puts(formTec);
puts(experProf);
puts(cursQual);
puts(trabVol);
puts(interes);
  return (0);
}
