# HealthPro - Sistema de Gestão de Saúde

Este projeto é uma aplicação desenvolvida em .NET, estruturada com base nos princípios de Clean Architecture. O objetivo principal é fornecer uma plataforma robusta para a gestão de informações relacionadas à saúde, garantindo escalabilidade, manutenibilidade e facilidade de testes.

---

## 📁 Estrutura do Projeto

O projeto está organizado nos seguintes diretórios:

- **HealthPro.Application**: Contém a lógica de negócios e os casos de uso da aplicação.
- **HealthPro.Domain**: Define as entidades do domínio e interfaces dos repositórios.
- **HealthPro.Infrastructure**: Implementa os repositórios e serviços externos, como acesso a dados.
- **HealthPro.IoC**: Responsável pela injeção de dependências e configuração dos serviços.
- **HealthPro.Tests**: Contém os testes automatizados para garantir a qualidade do código.
- **HealthPro**: Projeto principal que integra todas as camadas e executa a aplicação.

---

## ✅ Testes Implementados

A qualidade do código é assegurada por meio de uma suíte abrangente de testes automatizados:

- **Testes Unitários**: Verificam individualmente as funcionalidades dos serviços e repositórios, garantindo que cada componente funcione isoladamente.
- **Testes de Integração**: Avaliam a interação entre diferentes partes do sistema, como a comunicação entre a camada de aplicação e a infraestrutura de dados.

Os testes são escritos utilizando o framework [xUnit](https://xunit.net/) e seguem as melhores práticas para garantir confiabilidade e facilidade de manutenção.

---

## 🧼 Práticas de Clean Code Aplicadas

O projeto adota diversas práticas recomendadas para manter um código limpo e de fácil compreensão:

- **Nomenclatura Clara**: Nomes de classes, métodos e variáveis são descritivos e seguem convenções consistentes.
- **Responsabilidade Única**: Cada classe e método possui uma única responsabilidade, facilitando a manutenção e evolução do código.
- **Injeção de Dependências**: Utiliza-se a injeção de dependências para promover o desacoplamento entre os componentes e facilitar os testes.
- **Separação de Camadas**: A arquitetura em camadas (Application, Domain, Infrastructure) promove uma clara separação de preocupações.

Essas práticas contribuem para um código mais legível, testável e sustentável a longo prazo.

---

## 🤖 Funcionalidades de IA Generativa

O sistema incorpora funcionalidades de Inteligência Artificial Generativa para aprimorar a experiência do usuário e oferecer insights avançados:

- **Geração de Relatórios Personalizados**: Utiliza modelos de linguagem para criar relatórios detalhados com base nos dados do paciente.
- **Assistente Virtual**: Implementa um chatbot inteligente que responde a perguntas frequentes e auxilia na navegação pelo sistema.
- **Análise Preditiva**: Aplica algoritmos de aprendizado de máquina para prever tendências e auxiliar na tomada de decisões clínicas.

Essas funcionalidades são integradas por meio de APIs de IA e serviços de nuvem, garantindo escalabilidade e segurança.

---

## 🚀 Como Executar o Projeto

1. **Pré-requisitos**:
   - [.NET SDK](https://dotnet.microsoft.com/download) instalado na máquina.

2. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/LorenzoVaz/DOTNET-SP4.git
   cd DOTNET-SP4
