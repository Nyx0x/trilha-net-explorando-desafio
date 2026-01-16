# 🏨 Sistema de Hospedagem - Desafio DIO

Solução desenvolvida para o desafio de projeto "Construindo um Sistema de Hospedagem de um Hotel no C#", da trilha .NET da Digital Innovation One (DIO).

## 📋 Sobre o Projeto

O objetivo foi implementar a lógica de negócios de um sistema de reservas, focando no uso de **Listas**, **Exceções** e **Encapsulamento**.

### ⚙️ Funcionalidades Implementadas

- **Cadastro de Hóspedes:** Validação lógica que impede o cadastro de mais pessoas do que a capacidade da suíte permite (lançando uma `Exception` caso excedido).
- **Cálculo de Diária:** Método automatizado que multiplica dias reservados pelo valor da suíte.
- **Regra de Desconto:** Aplicação automática de **10% de desconto** para reservas iguais ou superiores a 10 dias.

## 🛠️ Tecnologias

- C# (.NET 8)
- VS Code

## 🚀 Como Rodar

```bash
# Clone este repositório
git clone [https://github.com/Nyx0x/trilha-net-explorando-desafio.git](https://github.com/Nyx0x/trilha-net-explorando-desafio.git)

# Entre na pasta
cd trilha-net-explorando-desafio

# Execute o projeto
dotnet run
