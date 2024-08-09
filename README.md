# Gerador de PDF

### Contexto
Este repositório contém um projeto desenvolvido para gerar arquivos PDF de maneira simples e eficiente. O gerador de PDF foi criado para atender a necessidades específicas, como a automatização de relatórios, geração de documentos personalizados, entre outros.

### Configuração
1. Clone o repositório:
```git clone https://github.com/leopxz/gerador_de_pdf.git```
<br>```cd gerador_de_pdf```

2. Instale as dependências:
```pip install fpdf```<br>
```pip install -r requirements.txt```
<br>
3. Verifique as configurações adicionais no arquivo config.py (se aplicável). Certifique-se de que todos os parâmetros estejam configurados de acordo com suas necessidades.
<br>
### Execução

1. Após a configuração, o projeto pode ser executado da seguinte forma:
Execute o script principal para gerar o PDF:<br>
```python gerador.py```<br>
OU SE preferir clique com o botão direito do mouse no seu código e clique em: RUN PYTHON > RUN PYTHON FILE IN TERMINAL
<br>
2. Em seguida responda as perguntas que vão aparecer no terminal.
<br>
Os arquivos PDF gerados serão salvos na pasta especificada no arquivo config.py. Verifique o conteúdo do PDF gerado para garantir que tudo esteja conforme o esperado.

### Estrutura
<br>
gerador_de_pdf/<br>
├── .gitgnore            # Arquivo que especifica quais arquivos e diretórios devem ser ignorados pelo Git<br>
├── LICENSE.          # Arquivo que contém a licença do projeto<br>
├── Orçamento.pdf         # PDF gerado como exemplo<br>
├── README.md            # Documentação do projeto<br>
├── gerador.py   # Script principal para gerar o PDF<br>
└── template.png          # modelo do pdf<br>

### Contribuição
Sinta-se à vontade para contribuir com melhorias ou correções neste projeto. Sugestões e pull requests são sempre bem-vindos.

