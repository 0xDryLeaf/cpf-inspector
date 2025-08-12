# CPF Inspector

O CPF Inspector é uma ferramenta de linha de comando para validar CPFs (*Cadastro de Pessoas Físicas*) em arquivos CSV ou TXT. Este script oferece a capacidade de verificar a validade de CPFs em um único arquivo ou em vários arquivos em um diretório, tendo também a capacidade de filtrar a saída para exibir apenas CPFs válidos e exibindo estatísticas de validação e permitindo a saída dos resultados em um arquivo.

## Requisitos

- Python 3.x

## Dependências

Antes de executar o CPF Inspector, certifique-se de ter instalado todas as dependências listadas no arquivo requirements.txt.

Para instalar as dependências, execute o seguinte comando no terminal:

```bash
pip install -r requirements.txt
```

## Como usar

1. Baixe ou clone este repositório para o seu sistema local.

2. Certifique-se de ter o Python instalado em seu sistema.

3. Abra o terminal (*ou prompt de comando*) e navegue até o diretório onde você baixou/clonou este repositório.

4. Instale as dependências necessárias.

5. Execute o script com os argumentos desejados. Veja abaixo os exemplos de uso:

### Exemplos de uso:

- Para validar CPFs em um único arquivo:

```bash
python cpf_inspector.py <arquivo_com_cpfs>
```

- Para validar CPFs em um único arquivo e salvar os resultados em um novo arquivo:

```bash
python cpf_inspector.py <arquivo_com_cpfs> -o <nome_do_arquivo_de_saída>
```

- Para validar CPFs em um único arquivo e exibir apenas os CPFs válidos:

```bash
python cpf_inspector.py -t <arquivo_com_cpfs>
```

- Para validar CPFs em vários arquivos em um diretório (*pode ser combinado com **-t** e **-o***):

```bash
python cpf_inspector.py -d <diretorio_com_arquivos>
```

- Para ver o manual da ferramenta:

```bash
python cpf_inspector.py -h
```

## Contribuindo

Sinta-se à vontade para contribuir com melhorias, sugestões ou relatar problemas. Basta abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo LICENSE para obter detalhes.


