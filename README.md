# pi-ralelo

uma implentação básica do cálculo de Pi paralelo usando o método de Monte Carlo

# Dependências do projeto:

```sh
sudo apt install openmpi-bin libopenmpi-dev
```

# Como rodar:

```sh
mpicc main.c -o main && mpiexec -n 4 ./main
```

```sh
mpicc example1.c -o main && mpiexec --use-hwthread-cpus ./main
```
