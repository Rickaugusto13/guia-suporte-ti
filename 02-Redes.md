# 🌐 Redes de Computadores para Suporte Técnico

## Objetivo

Este documento reúne os principais conceitos, comandos e procedimentos
utilizados no diagnóstico de problemas de rede em ambientes
corporativos.

## Conceitos essenciais

-   Endereço IP
-   Máscara de rede
-   Gateway
-   DNS
-   DHCP

## Comandos úteis

### Verificar configuração de rede

``` cmd
ipconfig /all
```

Exibe IP, gateway, DNS e outras configurações.

### Testar conectividade

``` cmd
ping 8.8.8.8
```

Verifica se há comunicação com outro equipamento.

### Descobrir o caminho até um destino

``` cmd
tracert google.com
```

Mostra por quais roteadores a conexão passa.

### Consultar DNS

``` cmd
nslookup google.com
```

Verifica se o DNS está resolvendo nomes corretamente.

## Checklist de diagnóstico

1.  O cabo de rede está conectado?
2.  O Wi-Fi está ativo?
3.  O computador recebeu um IP?
4.  O gateway responde ao ping?
5.  O DNS está funcionando?
6.  O problema afeta apenas um usuário ou toda a empresa?

## Problemas comuns

-   Sem acesso à internet
-   Conexão lenta
-   DNS indisponível
-   IP duplicado
-   Perda de comunicação com servidores

## Minha experiência

Durante minha atuação em suporte técnico utilizei comandos como
**ipconfig**, **ping**, **tracert** e **nslookup** para identificar
problemas de conectividade, validar configurações de rede e agilizar o
diagnóstico de incidentes.

## Perguntas comuns em entrevistas

-   Qual a diferença entre IP público e IP privado?
-   Para que serve um servidor DNS?
-   O que faz o DHCP?
-   Quando utilizar o comando `ping`?
-   Para que serve o `tracert`?
