# Verificador com interface gráfica

Nesse projeto eu busco fazer um verificador e criador de CPF  válido.
Futuramente eu pretendo implementar no programa um criador e verificador de CNPJ e RG.

O projeto vai ser desenvolvido totalmente em C.

Para poder compilar o programa tu vai precisar ter instalado GTK no teu computador
Então tu segue esses passos:    

[Acesse esse site e faça a instalação como é descrita lá](https://www.gtk.org/docs/installations/windows/)


Na hora de compilar

```
Acesse o local aonde está o msys
Vá até a pasta home
E depois vá para a pasta onde estiver o seu nome de user
mkdir Verificador
$ git clone https://github.com/Diaszano/Verificador-com-interface-grafica.git Verificador
$ cd Verificador
$ gcc -o Verificador verificador.c `pkg-config --libs --cflags gtk+-3.0`
$ ./Verificador
```