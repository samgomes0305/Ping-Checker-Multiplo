# Ping Checker Múltiplo

Este script Python realiza verificações de ping em vários endereços IP listados no arquivo `hosts.txt`. Ele utiliza o comando `ping` para enviar pacotes ICMP e medir a latência da resposta de cada host. O intervalo entre as verificações é configurado para 2 segundos.

## Pré-requisitos

Certifique-se de ter o Python instalado em seu sistema. Além disso, o arquivo `hosts.txt` deve estar presente no mesmo diretório que o script.

## Uso

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/ping-checker-multiplo.git
   ```

2. Navegue até o diretório do script:

   ```bash
   cd ping-checker-multiplo
   ```

3. Execute o script:

   ```bash
   python ping_checker.py
   ```

   O script iniciará a verificação de ping para cada endereço IP listado em `hosts.txt`.

## Conteúdo do Arquivo hosts.txt

O arquivo `hosts.txt` deve conter os endereços IP que você deseja verificar, cada um em uma linha separada. Certifique-se de que este arquivo esteja no mesmo diretório que o script.

Exemplo:

```plaintext
192.168.0.1
8.8.8.8
github.com
```

## Notas

- Este script utiliza o comando `ping` disponível no sistema operacional. Certifique-se de que o comando está acessível no seu ambiente.

- O intervalo de 2 segundos entre as verificações pode ser ajustado conforme necessário, alterando o valor passado para `time.sleep()`.

- Certifique-se de ter permissões suficientes para executar o comando `ping` no seu sistema.

- Este script foi desenvolvido para fins educacionais e de demonstração. Use-o com responsabilidade e respeite os termos de serviço dos hosts que você está verificando.
