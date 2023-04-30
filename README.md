# Projeto para testar o consul como ferramenta de service discovery

## Commandos do consul

Subir um agente 
```bash
consul agent -dev
```

Listar os membros do cluster
```bash
consul members
```

install dig
```bash
apk -U add bind-tools
```

consulta de DNS (Só batendo no DNS)
```bash
dig @localhost -p 8600
```

consulta de DNS expecífica do DOMINIO/IP
```bash
dig @localhost -p 8600 consul01.node.consul
```

consula de DNS trazendo somente o IP
```bash
dig @localhost -p 8600 consul01.node.consul +short
```


### Tipos de processos consul
- server ou client
- em produção pelo menos 3 máquinas e sempre números ímpares

