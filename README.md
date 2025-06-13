# OneHellOfASorter

> A Python script to flawlessly organize your files into categorized folders. Simply one hell of a sorter.

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)
![Status: Em Desenvolvimento](https://img.shields.io/badge/status-em%20desenvolvimento-orange.svg)
<p aling="center">
<img src="https://github.com/user-attachments/assets/d7b17811-45a9-47fc-8749-fbe0cf21f707" alt="Gif de Sebastian Michaelis" width=1000>
</p>
## Sobre o Projeto

Sua pasta de Downloads é um caos de arquivos desordenados? Problemas dessa natureza exigem uma solução de outro nível.

Assim como um certo mordomo é contratado para resolver os problemas mais complicados da nobreza, o **OneHellOfASorter** é um script Python contratado para trazer ordem impecável aos seus diretórios. Ele analisa uma pasta de sua escolha e, seguindo suas ordens, move cada arquivo para uma subpasta devidamente categorizada (PNGs, JPGs, PDFs, etc.).

É eficiente. É preciso. É, resumidamente, um organizador de arquivos infernalmente bom.

## Principais Features

* **Organização Automática:** Move arquivos para pastas baseadas em sua extensão, de forma rápida e automática.
* **Configuração Centralizada:** Adicione novos tipos de arquivo e pastas de destino facilmente, editando um único dicionário no topo do script.
* **Criação Inteligente de Pastas:** Os diretórios de destino são criados automaticamente se não existirem.
* **Interface Interativa (em desenvolvimento):** Planejado para incluir caixas de diálogo para uma interação mais amigável.

## Começando

Para ter uma cópia local do projeto rodando, siga estes passos.

### Pré-requisitos

* Python 3.7 ou superior instalado. Você pode baixá-lo [aqui](https://www.python.org/downloads/).

### Instalação

1.  Clone o repositório para a sua máquina local:
    ```sh
    git clone [https://github.com/seu-usuario/OneHellOfASorter.git](https://github.com/seu-usuario/OneHellOfASorter.git)
    ```
2.  Navegue até a pasta do projeto:
    ```sh
    cd OneHellOfASorter
    ```
3.  (Opcional, mas recomendado) Crie e ative um ambiente virtual:
    ```sh
    # Para Windows
    python -m venv venv
    .\venv\Scripts\activate

    # Para macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

## Como Usar

Depois de configurar o ambiente, basta executar o script principal:

```sh
python main.py
```

Por padrão, o script irá organizar a sua pasta de **Downloads**. Para alterar o diretório alvo ou customizar as categorias de arquivos, edite o dicionário `MAPEAMENTO_TIPOS_ARQUIVO` no arquivo `main.py`.

## Como Contribuir

Contribuições são o que tornam a comunidade de código aberto um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **muito apreciada**.

1.  Faça um **Fork** do Projeto
2.  Crie uma **Branch** para sua Feature (`git checkout -b feature/AmazingFeature`)
3.  Faça o **Commit** de suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4.  Faça o **Push** para a Branch (`git push origin feature/AmazingFeature`)
5.  Abra um **Pull Request**

## Licença

Distribuído sob a Licença MIT. Veja o arquivo `LICENSE` para mais informações.

## Contato

Carlos Nascimento - [@bakaloneking](https://twitter.com/bakaloneking) - bakaloneking@hotmail.com

Link do Projeto: [https://github.com/seu-usuario/OneHellOfASorter](https://github.com/seu-usuario/OneHellOfASorter)
