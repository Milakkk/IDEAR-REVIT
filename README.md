# IDEAR-REVIT

Descrição curta
--------------
IDEAR-REVIT é um projeto para integração/automatização com Autodesk Revit (ou ferramenta relacionada). Este repositório contém código, scripts e recursos para [criação de cotas automaticas].

Badges
------
- Status: WIP / Concluído / Em desenvolvimento
- Licença: MIT / GPL / Proprietária
- Versão: 0.1.0


Requisitos
----------
- Autodesk Revit — versão(s): (preencher, ex.: 2021, 2022, 2023)
- .NET Framework / .NET Core (se for add-in) — versão: (preencher)
- Python / Dynamo / outro (se aplicável) — versão: (preencher)
- Dependências adicionais: listar pacotes ou bibliotecas necessárias

Instalação
----------
Escolha a seção que corresponde ao tipo de artefato do repositório (ex.: add-in, script, pacote).

Instalação genérica
1. Clone o repositório:
   ```
   git clone https://github.com/Milakkk/IDEAR-REVIT.git
   ```
2. Entre na pasta do projeto:
   ```
   cd IDEAR-REVIT
   ```
3. Instale dependências (exemplo com pip, se houver scripts Python):
   ```
   pip install -r requirements.txt
   ```

Instalação como Add-in do Revit (exemplo)
1. Compile o projeto (Visual Studio / dotnet build).
2. Copie o(s) arquivo(s) gerado(s) (.addin e .dll) para a pasta de Add-ins do Revit:
   - Windows: `%AppData%\Autodesk\Revit\Addins\<AnoRevit>\`
3. Reinicie o Revit e verifique se a aba/ comando aparece.

Uso
---
- Como executar (exemplos):
  - Executar script:
    ```
    python scripts/runner.py --modelo caminho/para/modelo.rvt
    ```
  - Executar add-in: abrir Revit → acessar a aba do add-in → executar ferramenta desejada.
- Parâmetros comuns e opções (descrever flags, inputs e outputs).

Estrutura do repositório
------------------------
- /src — código-fonte do add-in / scripts
- /docs — documentação adicional e especificações
- /examples — arquivos de exemplo e modelos de teste
- /tests — testes automatizados
- README.md — este arquivo

Como contribuir
---------------
1. Abra uma issue descrevendo a proposta ou bug.
2. Faça um fork do repositório e crie uma branch:
   ```
   git checkout -b feat/nova-funcionalidade
   ```
3. Faça commits claros e envie um pull request.
4. Siga as diretrizes de codificação e escreva/atualize testes quando aplicável.

Boas práticas para PR
- Descreva o objetivo do PR.
- Relacione a issue (ex.: `Closes #12`).
- Inclua instruções para teste manual.
- Garanta que os testes automatizados (se existirem) passam.

Testes
-----
- Como rodar os testes locais:
  ```
  pytest
  ```
  ou
  ```
  dotnet test
  ```
- Cobertura e requisitos de CI (preencher conforme configuração do repositório).


Contato
-------
- Autor: Milakkk

Notas finais / TODO
-------------------
- Documentar versões suportadas do Revit.
- Incluir exemplos reais de uso (screenshots, GIFs).
- Adicionar CI (GitHub Actions) para build e testes automáticos.
