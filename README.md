# Gerador de PDF

### Contexto
Este repositório contém um projeto desenvolvido para gerar arquivos PDF de maneira simples e eficiente. O gerador de PDF foi criado para atender a necessidades específicas, como a automatização de relatórios, geração de documentos personalizados, entre outros.

### Configuração
1. Clone o repositório:
```git clone https://github.com/leopxz/gerador_de_pdf.git```
```cd gerador_de_pdf```

2. Instale as dependências:
```pip install fpdf```
```pip install -r requirements.txt```

3. Verifique as configurações adicionais no arquivo config.py (se aplicável). Certifique-se de que todos os parâmetros estejam configurados de acordo com suas necessidades.

### Execução

1. Após a configuração, o projeto pode ser executado da seguinte forma:
Execute o script principal para gerar o PDF:
```python gerador.py```
OU SE preferir clique com o botão direito do mouse no seu código e clique em: RUN PYTHON > RUN PYTHON FILE IN TERMINAL

2. Em seguida responda as perguntas que vão aparecer no terminal.

Os arquivos PDF gerados serão salvos na pasta especificada no arquivo config.py. Verifique o conteúdo do PDF gerado para garantir que tudo esteja conforme o esperado.

### Estrutura

gerador_de_pdf/
├── .gitgnore            # Arquivo que especifica quais arquivos e diretórios devem ser ignorados pelo Git
├── LICENSE.          # Arquivo que contém a licença do projeto
├── Orçamento.pdf         # PDF gerado como exemplo
├── README.md            # Documentação do projeto
├── gerador.py   # Script principal para gerar o PDF
└── template.png          # modelo do pdf

Contribuição
Sinta-se à vontade para contribuir com melhorias ou correções neste projeto. Sugestões e pull requests são sempre bem-vindos.

