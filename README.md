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

### Tipos de processos consul
- server ou client
- em produção pelo menos 3 máquinas e sempre números ímpares

