# NASA Mission Control Deno Project

Criar arquivo `lock.json` na execução:  
```console
jr@dev:~$ deno run --allow-read --allow-net --lock-write --lock=lock.json mod.ts  
Starting server on port 8000 🚀
```

Executar app  
```console
jr@dev:~$ deno run --allow-read --allow-net --lock=lock.json mod.ts  
Starting server on port 8000 🚀
```