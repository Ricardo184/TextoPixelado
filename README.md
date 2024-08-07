# TextoPixelado

**TextoPixelado** é um script Python que converte imagens em texto utilizando caracteres especiais e cores ANSI. Ideal para criar arte em texto a partir de imagens, o projeto permite personalizar a representação com diferentes caracteres e salvar a saída em arquivos de texto.

## Como Usar

```bash
python TextoPixelado.py [opções] [imagem]
```

### Opções

- `-o CARACTERE`  Define o caractere usado para representar cada pixel da imagem. Exemplo: '■', '▒', '░', '█', '□', '●', '○'. Valor padrão: '■'.
- `-s ARQUIVO`    Define o nome do arquivo onde a saída será salva. Se não fornecido, a saída será exibida no terminal.
- `-h`            Mostra a mensagem de ajuda.

### Exemplo

```bash
python TextoPixelado.py imagem.png -o '▒' -s saída.txt
```

### Notas

- O script redimensiona a imagem para 75x75 pixels se ela for maior que isso.
- A imagem deve estar em um formato suportado pelo Pillow (ex: PNG, JPEG).

## Requisitos

- Python 3
- Pillow

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/ricardo184/TextoPixelado.git
   ```

2. Navegue para o diretório do projeto:

   ```bash
   cd TextoPixelado
   ```

3. Instale as dependências:

   ```bash
   pip install pillow
   ```

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

## Contribuição

Sinta-se à vontade para contribuir com melhorias ou correções. Para mais detalhes, consulte o arquivo CONTRIBUTING.md.
## Exemplos

A pasta [Imagens](./Imagens) contém arquivos de exemplo para demonstração do funcionamento do **TextoPixelado**.

- [imagem1.jpg](https://github.com/Ricardo184/TextoPixelado/blob/main/Imagens/imagem1.jpg): Esta é a imagem original usada como exemplo.
- [imagem1.txt](https://github.com/Ricardo184/TextoPixelado/blob/main/Imagens/imagem1.txt): Este arquivo contém a representação textual da imagem `imagem1.jpg`, gerada pelo script.

Você pode visualizar esses arquivos diretamente na pasta [Imagens](./Imagens) do GitHub para ver como a imagem é convertida em texto e como o resultado é apresentado no terminal.
