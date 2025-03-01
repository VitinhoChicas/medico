# 🏥 **Projeto Médico e Paciente  Java com Spring**

## 📌 Sobre o Projeto
Este projeto é uma revisão de Java com o framework Spring. Criação de duas classe simples.

### 🗄 Banco de Dados Suportados
- **H2** (banco em memória para testes)
- **PostgreSQL** (banco de produção)

>## 🩺 Classes
```plantuml

 
+-----------------------------+
|            Medico           |
+-----------------------------+
| - idMedico: long            |
| - nome: String              |
| - dataContratacao: LocalDate|
| - salario: BigDecimal       |
+-----------------------------+
 
+------------------------------+
|   Paciente                   |
+------------------------------+
| - idPaciente: long           |
| - nomeP: String              |
| - dataNascimento: LocalDate  |
| - internacao: BigDecimal     |
+------------------------------+






