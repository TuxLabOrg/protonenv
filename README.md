# protonenv
Executa programas dentro do ambiente do proton, inspirado no [protonhax](https://github.com/jcnils/protonhax)

Apenas uma reformulação no codigo.

### Uso:
```
protonenv <parametro>
  init			Deve ser usado nas opções de inicialização do jogo. Cria o ambiente de execuçaõ.
    Ex: protonenv init %command%

  run <APPID> <EXE>	Usado para executar programas dentro do ambiente criado pelo "init".
		Ex: protonenv run 730 prog.exe

  list			Lista os programas em execução iniciados com o "init".

  help			Mostra esta ajuda.
```

## Ex:
```
No jogo na Steam:
protonenv init %command%

No terminal:
$ protonenv run <AppID> cmd

```
