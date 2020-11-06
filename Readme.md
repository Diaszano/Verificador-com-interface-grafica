# Verificador com interface gráfica

Nesse projeto eu busco fazer um verificador e criador de CPF  válido.
Futuramente eu pretendo implementar no programa um criador e verificador de CNPJ e RG.

O projeto vai ser desenvolvido totalmente em C.

Para poder compilar o programa tu vai precisar ter instalado GTK no teu computador
    
```  
$ sudo apt-get install libgtk-3-dev 
```

Na hora de compilar

```
$ gcc -o Verificador verificador.c `pkg-config --libs --cflags gtk+-3.0`
$ ./Verificador
```