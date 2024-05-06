# fiap-checkpoint2

# Instruções Docker - Perfis
## Executando imagem
```
docker run -p 8080:8080 fiap-checkpoint3
```

## Como executar no modo DEV
```
docker run -p 8080:8080 -e PROFILE=dev fiap-checkpoint3
ou
docker run -p 8080:8080 fiap-checkpoint3
```

## Como executar no modo stg
```
docker run -p 8080:8080 -e PROFILE=stg fiap-checkpoint3
```

## Como executar no modo prd
```
docker run -p 8080:8080 -e PROFILE=prd fiap-checkpoint3
```

# Integrantes

| Integrante | Github |
| --- | --- |
| Pedro Lamark | https://github.com/PedroLamark/fiap-checkpoint3 |
