# DocL-

# DocLê

> Leitura automática de documentos com OCR e Inteligência Artificial.

**Equipe:** DocLê
**Responsável:** Ângelo Rafael Oliveira Cunha Santos

---

## 👥 Integrantes e responsabilidades iniciais

| Integrante | Matrícula | Responsabilidade inicial |
|---|---|---|
| Ângelo Rafael Oliveira Cunha Santos | 01589358 | Coordenação da equipe, gestão do quadro no Trello, integração dos módulos e interface do sistema |
| Thaís Helena Ramos de Melo | 01068175 | Levantamento do problema, documentação do projeto (README) e preparação da apresentação |
| Túlio Angelus Torres de Melo Mendes | 01633581 | Módulo de leitura de texto (OCR) e tratamento das imagens |
| Julio Cesar Braga Maciel de Souza | 01528725 | Módulo de identificação de dados e nomes (PLN) e testes com documentos de exemplo |

---

## 🧩 Descrição do problema

Em muitos órgãos públicos e empresas, os dados de documentos como notas fiscais, formulários, comprovantes e contratos ainda são **digitados manualmente** nos sistemas. Esse processo é:

- **Lento:** o servidor ou funcionário precisa ler cada documento e copiar campo por campo;
- **Sujeito a erros:** números de CPF, CNPJ, datas e valores digitados errado geram retrabalho, cadastros inconsistentes e até prejuízo financeiro;
- **Pouco produtivo:** profissionais qualificados gastam tempo em uma tarefa repetitiva que poderia ser automatizada.

## 🔗 Desafio escolhido na plataforma CORETO

**Ineficiência e erros na extração manual de dados de documentos**
https://coreto.app.emprel.gov.br/banco-de-bo/ineficiencia-e-erros-na-extracao-manual-de-dados-de-documentos

---

## 🎯 Objetivo da solução

Desenvolver uma aplicação web simples que **lê a imagem de um documento e extrai automaticamente o texto e os dados importantes**, reduzindo o tempo gasto com digitação e a quantidade de erros.

A solução combina duas tecnologias:

- **OCR (Reconhecimento Óptico de Caracteres):** transforma a imagem do documento em texto digital;
- **PLN (Processamento de Linguagem Natural):** interpreta esse texto e identifica as informações relevantes.

## 🙋 Público beneficiado

- **Servidores públicos e equipes administrativas** que hoje fazem a digitação manual de documentos;
- **Órgãos públicos e empresas**, que ganham agilidade e dados mais confiáveis;
- **Cidadãos**, que passam a ter solicitações e atendimentos processados com mais rapidez.

---

## ✅ Funcionalidades previstas para a primeira versão

1. **Envio de imagens de documentos:** o usuário envia a foto ou o scan de um documento nos formatos PNG ou JPG.
2. **Leitura automática do texto (OCR):** o sistema transforma a imagem do documento em texto digital.
3. **Identificação de dados importantes:** o sistema encontra automaticamente CPF, CNPJ, datas, valores, e-mails e telefones presentes no documento.
4. **Reconhecimento de nomes com IA:** o sistema identifica nomes de pessoas, empresas e locais citados no documento.
5. **Visualização e download do resultado:** o usuário vê o texto extraído e os dados encontrados na tela e pode baixar o texto em arquivo.

---

## 🛠️ Tecnologias previstas

| Tecnologia | Uso no projeto |
|---|---|
| Python | Linguagem principal |
| Tesseract OCR (pytesseract) | Leitura do texto das imagens |
| Pillow | Tratamento das imagens antes da leitura |
| Expressões regulares (regex) | Identificação de CPF, CNPJ, datas, valores, e-mails e telefones |
| spaCy (modelo em português) | Reconhecimento de nomes de pessoas, empresas e locais |
| Streamlit | Interface web da aplicação |
| GitHub | Versionamento do código |
| Trello | Gestão das tarefas do projeto |

---

## 📋 Gestão do projeto

Quadro de tarefas no Trello:
https://trello.com/invite/b/6abc576970f3f63460da84c9/ATTI44d171027429449215fe3bb4d8873b7f75B01F80/projeto-docle

---

## 🚀 Próximas versões (planejado)

- Suporte a arquivos PDF (digitais e escaneados);
- Validação dos dígitos verificadores de CPF e CNPJ;
- Exportação dos dados encontrados para planilha.
