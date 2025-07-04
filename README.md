# Organizador de Declaração de Imposto de Renda - Excel

## Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio prático da **Digital Innovation One (DIO)**, com o objetivo de criar uma ferramenta robusta e amigável no **Microsoft Excel** que auxilie os contribuintes a organizar todas as informações necessárias para a Declaração de Imposto de Renda Pessoa Física (DIRPF).

A planilha permite o registro detalhado de dados do titular, dependentes, rendimentos, despesas dedutíveis, bens, dívidas e documentos complementares. Para otimizar a experiência do usuário, a solução incorpora uma interface de navegação intuitiva por meio de **macros em VBA**, validações automáticas de dados e funcionalidades extras, como links rápidos.

## Funcionalidades da Planilha

* **Registro Detalhado:** Permite o controle preciso de dados do *Titular* e *Dependentes*.
* **Controle Financeiro Abrangente:** Gerenciamento eficiente de *Rendimentos*, *Despesas*, *Bens e Direitos*, e *Dívidas e Ônus*.
* **Organização de Documentos:** Seção dedicada para listar e acompanhar os *Informes Necessários* para a declaração, facilitando a coleta de comprovantes.
* **Validações Automáticas:** Implementação de validações de dados (listas suspensas, formatos numéricos, datas) para garantir o preenchimento correto e padronizado das informações (ex: tipos de rendimentos, estados, bancos).
* **Interface Amigável:**
    * **Dashboard Interativo:** Página inicial intuitiva com botões de navegação para acesso rápido às diferentes seções da planilha.
    * **Navegação por VBA:** Utilização de macros (*VBA*) para facilitar a transição entre as abas e aprimorar a experiência do usuário.
    * **Links Rápidos:** Capacidade de abrir uma pasta local de documentos (caminho configurável via *VBA*), agilizando o acesso a comprovantes e arquivos digitais.
* **Estrutura Otimizada:** Campos e abas estruturados para espelhar os requisitos típicos e a lógica da Receita Federal para a *DIRPF*.

## Estrutura das Abas (Sheets)

A planilha é organizada nas seguintes abas, cada uma com um propósito específico:

* `Dashboard`: Página inicial com o menu de navegação principal.
* `Titular`: Para registro dos dados pessoais do contribuinte principal.
* `Dependentes`: Para informações dos dependentes (se houver).
* `Rendimentos`: Detalhamento das diversas fontes de rendimento.
* `Despesas`: Registro de despesas dedutíveis.
* `Bens e Direitos`: Cadastro de patrimônio (imóveis, veículos, investimentos, etc.).
* `Dívidas e Ônus`: Anotação de dívidas e financiamentos.
* `Informes Necessários`: Lista de documentos e informes a serem coletados.
* `Notas`: Espaço para anotações e observações adicionais.
* `Tabelas de Apoio`: Aba oculta contendo as listas de validação de dados para uso nas outras abas.

## Como Usar

1.  **Baixe o arquivo:** Faça o download do arquivo `IR_Organizer.xlsm` deste repositório.
2.  **Habilite as macros:** Ao abrir o arquivo no Excel, certifique-se de **habilitar o conteúdo/macros** caso seja solicitado, para que a navegação e funcionalidades *VBA* funcionem corretamente.
3.  **Acesse o `Dashboard`:** A planilha será aberta automaticamente na aba `Dashboard`, que serve como sua central de navegação.
4.  **Navegue:** Utilize os botões de navegação para ir até a seção desejada (ex: `Titular`, `Rendimentos`, `Despesas`).
5.  **Preencha os Dados:** Insira suas informações nos campos designados. As validações de dados ajudarão a garantir o preenchimento correto e a integridade das informações.
6.  **Acesse Documentos (Opcional):** Caso tenha configurado o caminho da pasta de documentos no *VBA*, utilize o botão correspondente para abrir sua pasta local de comprovantes.
7.  **Monitore:** As formatações condicionais podem auxiliar na visualização de campos pendentes ou informações que exigem atenção.

## Recursos Técnicos Utilizados

* **Microsoft Excel:** Ambiente principal de desenvolvimento, utilizando seus recursos nativos e avançados.
    * **VBA (Visual Basic for Applications):** Essencial para criação de macros de navegação, automação de tarefas e links dinâmicos.
    * **Validação de Dados:** Para criação de listas suspensas e restrições de entrada de dados, garantindo a qualidade.
    * **Intervalos Nomeados:** Utilizados para facilitar a referência em fórmulas e validações.
    * **Formatação Condicional:** Aplicada para aprimorar a visualização dos dados e indicar status.
    * **Função HIPERLINK:** Para referências a sites externos (ex: site da Receita Federal).
* **Git e GitHub:** Ferramentas essenciais para controle de versionamento do projeto e sua hospedagem pública.
* **Markdown:** Linguagem de marcação utilizada para a criação desta documentação detalhada.

## Aprendizados com o Projeto

Este desafio proporcionou uma valiosa experiência prática e consolidou os seguintes aprendizados:

* **Modelagem de Dados:** Aplicação de conceitos de estruturação de dados relevantes para a declaração de Imposto de Renda.
* **Excel Avançado:** Utilização de recursos avançados do Excel com foco em usabilidade e validação de dados para criar uma ferramenta robusta.
* **Automação com VBA:** Desenvolvimento e implementação de macros para melhorar significativamente a interatividade e a experiência do usuário.
* **Documentação Técnica:** Prática na criação de documentação clara e estruturada utilizando *Markdown* para o *GitHub*.
* **Versionamento de Código:** Experiência prática com *Git* e *GitHub* para controle de versão e publicação de projetos.

## Considerações Finais

Este projeto foi uma excelente oportunidade para consolidar conhecimentos em Excel, VBA e boas práticas de documentação de projetos. A planilha visa tornar o processo de coleta e organização de dados para a Declaração de Imposto de Renda mais organizado, eficiente e menos propenso a erros para o contribuinte.

---

**Autor:** Hellen Araujo
