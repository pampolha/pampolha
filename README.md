### *Saudações!* || *Greetings!*
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
  char[] Habilidades;
};

void main()
{
  struct Info Eu;
  
  strcopy(Eu.Nome, "Gabriel Pampolha\n");
  
  Eu.Idade = 19;
  
  strcopy(Eu.Estudo_atual, "Aprendendo Node.js e javascript!\n");
  
  strcopy(Eu.Projeto_atual, "Desenvolvendo um bot de Discord em Node.js!\n");
  
  strcopy(Eu.Experiencias, "Cursei o primeiro semestre de Eng. da Computação, e lá eu descobri o meu talento em programação.\n"
                            "Enquanto estive lá, aprendi e desenvolvi a linguagem C além do currículo acadêmico,\n"
                            "e enquanto estava adiantado participei de um grupo de desenvolvimento de jogos,\n"
                            "no qual aprendi a linguagem C#, programação orientada a objetos e Unity.\n"
                            "Também participei de um grupo de pesquisas sobre programação, que me levou a aprender o meu\n"
                            "primeiro algoritmo, o selection sort, totalmente em C, ainda no primeiro semestre da faculdade.\n"
                            "Além disso, aprendi o básico da linguagem Python e a plotagem de vetores 2D e 3D nele.\n"
                            "Após isso, saí da faculdade e foquei em projetos pessoais, aprendi a linguagem Rust sozinho\n"
                            "e desenvolvi um bot do discord com ela.\n");
                            
  strcopy(Eu.Contato, "contato.gabrielpampolha@gmail.com");
  
  strcopy(Eu.Habilidades, "Linguagens de programção: C, C#, e Rust\n"
                          "Soft skills: Flexibilidade, liderança, capacidade de enxergar diferentes pontos de vista, visão analítica\n");
                          
  printf("Olá, mercado de trabalho!");
  system("pause");
}
```
