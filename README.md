# demps

## Instrucciones

Clonar este repositorio e ingresar al directorio creado:

```

git clone https://github.com/demps-project/production.git \
cd production
```


Iniciar el simulador
```
docker compose up -d
```

Una vez iniciado, se puede ingresar al sitio web del simulador

```
http://localhost:8000
```

Ejemplo de ejecución de una simulación

```
docker compose exec  --user=demps-user simulator demps --config /sim/valdivia00.config --outdir /sim/output/test01
```
