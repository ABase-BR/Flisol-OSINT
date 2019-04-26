## Consulta ReverseDNS
Podemos consutar o DNS reverso usando IP ou Dominio.

```sh
https://viewdns.info/reverseip/?host=37.59.174.225&t=1
```

Alem de IPS podemos usar dominios
```sh
https://viewdns.info/reverseip/?host=businesscorp.com.br
```

## Localização do servidor
Podemos ver uma possivel localização do servidor usando
```sh
https://viewdns.info/iplocation/?ip=37.59.174.225
```

Dessa forma podemos ter uma ideia da possivel localização do servidor.

## PortScan
Podemos ver quais portas estão abertas , sem ao menos interagir com o servidor.
```sh
https://viewdns.info/portscan/?host=37.59.174.225
```

> Ele só realiza testes em algumas top ports.

Alem disso de IPS podemos realizar testes em dominios.
```sh
https://viewdns.info/portscan/?host=businesscorp.com.br
```

## Whois 
Diferente do **who.is** o projeto **viewdns** consegue nos retornar o range correto dos servidores.
```sh
https://viewdns.info/whois/?domain=37.59.174.225
```

Alem de consultas Whois usando IP , podemos tambem realizar consultas em URLS.
```sh
https://viewdns.info/whois/?domain=businesscorp.com.br
```

## Traceroute
Podemos realizar o teste de traceroute para ver qual a rota usada até chegar no servidor , dessa forma podemos saber os pulos que ele da até chegar no servidor principal.
```sh
https://viewdns.info/traceroute/?domain=37.59.174.225
```

Alem de IPs podemos usar dominios nos testes
```sh
https://viewdns.info/traceroute/?domain=businesscorp.com.br
```

## IP History
Podemos ver informações sobre quando o dominio foi hospedado e uma possivel localização.

```sh
https://viewdns.info/iphistory/?domain=businesscorp.com.br
```
