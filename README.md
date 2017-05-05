# nfv_clickOS
Scripts utilizados para agilizar meu ambiente de testes (mestrado)


# Instalando o `pktgen`

Para instalar o `pktgen`, segui o conteúdo apresentado em [github - danieltt/pktgen](https://github.com/danieltt/pktgen).

Reproduzindo:

```
git clone https://github.com/danieltt/pktgen.git
cd pktgen
make
insmod pktgen
```
Obs.: utilizei o Debian 8.7.1 com Kernel 3.16.0-4-amd64. Erro ao tentar usar o Kernel compilado `vmlinuz-4.9.9-clickos`.

Quando instalado, basta executar os scripts presentes em `pktgen/example`
