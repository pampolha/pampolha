# ***Saudações!*** || ***Greetings!*** #
```c
#include <sorte.h>

struct Info
{
  char[20] Nome;
  int Idade;
  char[50] Estudo_atual;
  char[50] Projeto_atual;
  char[100] Experiencias;
  char[40] Contato;
};

void main()
{
  struct Info Eu;
  
  strcopy(Eu.Nome, "Gabriel Pampolha\n");
  
  Eu.Idade = 19;
  
  strcopy(Eu.Estudo_atual, "Aprendendo Node.js!\n");
  
  strcopy(Eu.Projeto_atual, "Desenvolvendo meu segundo bot de Discord com Node.js!\n");
  
  strcopy(Eu.Experiencias, "- Cursei um semestre de Engenharia da Computação, no qual desenvolvi em C, Python e C#.\n"
                           "- Completei a Quest "Google Cloud Essentials" do Google, e aprendi diversos conceitos em Cloud Engineering e Kubernetes.\n"
                           "- Estou sempre estudando novas tecnologias e conceitos por conta própria. Sou autodidata nas linguagens Rust e Javascript.\n");
                            
  strcopy(Eu.Contato, "contato.gabrielpampolha@gmail.com");
                            
  printf("Olá, mercado de trabalho!");
  
  system("pause");
}
```
