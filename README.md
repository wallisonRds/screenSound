# 🎵 ScreenSound

![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

O **ScreenSound** é uma aplicação de console interativa desenvolvida em C# voltada para a gestão, avaliação e análise de médias de bandas musicais. O projeto foi projetado para consolidar conceitos essenciais de **lógica estruturada de programação**, manipulação eficiente de coleções em memória e modularização de código por meio de funções (métodos).

---

## 🎯 Principais Funcionalidades

- **Menu Interativo Dinâmico:** Fluxo de navegação robusto gerenciado por estruturas condicionais estruturadas (`switch-case`).
- **Registro de Bandas:** Sistema de cadastro dinâmico que mapeia nomes de bandas na memória da aplicação.
- **Listagem Completa:** Varredura automática e exibição limpa de todas as chaves e registros armazenados.
- **Sistema de Avaliação:** Permite atribuir notas numéricas para bandas específicas, validando previamente se o registro consultado existe no sistema.
- **Cálculo Estatístico de Médias:** Exibição imediata da média aritmética de avaliações de cada banda utilizando recursos avançados do ecossistema .NET.

---

## 🛠️ Estrutura Técnica & Conceitos Aplicados

Para demonstrar a maturidade no desenvolvimento e alinhamento com os requisitos de um **Analista de Sistemas**, o código adota práticas essenciais de organização de dados:

1. **Manipulação Avançada de Coleções (`Dictionary` + `List`):** Implementação de uma estrutura de dados bidimensional complexa (`Dictionary<string, List<int>>`), associando uma chave do tipo texto (Nome da Banda) a uma lista dinâmica de inteiros (Notas de Avaliação).
2. **Modularização e Clean Code:** Código totalmente segmentado em funções com responsabilidades únicas (`RegistrarBanda`, `MostrarBandasRegistradas`, `AvaliarUmaBanda`, `ExibirMediaDaBanda`), facilitando futuras manutenções ou transições de arquitetura.
3. **Uso de LINQ (.Average):** Utilização de funções nativas de agregação de dados do .NET para realizar cálculos estatísticos em tempo de execução sem a necessidade de loops repetitivos redundantes.
4. **Validação de Fluxos e Defesa de Código:** Implementação de verificações condicionais (`ContainsKey`) para assegurar a integridade do fluxo e evitar exceções de referências nulas no console.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
Antes de iniciar, certifique-se de ter instalado:
- [SDK do .NET Core](https://dotnet.microsoft.com/download) (Versão 6.0 ou superior)
- Um editor de código de sua preferência (como o [VS Code](https://code.visualstudio.com/))

### Passo a Passo

1. **Clonar o repositório:**
   ```bash
   git clone [https://github.com/wallisonRds/screenSound.git](https://github.com/wallisonRds/screenSound.git)
Acessar a pasta do projeto:

Bash
cd screenSound
Compilar e buildar a aplicação:

Bash
dotnet build
Rodar o sistema no terminal:

Bash
dotnet run

👤 Autor
Desenvolvido com foco em engenharia e lógica de software por Wallison Vieira.
