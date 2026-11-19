# Hospital DB — Consultas SQL

## Sobre o Projeto

O projeto consiste na realização de consultas SQL no banco de dados `hospital_db`, com o objetivo de analisar informações sobre pacientes, médicos, consultas, internações e convênios. As consultas permitem organizar os dados, calcular valores e gerar resultados que auxiliam na análise e no gerenciamento das atividades hospitalares.

## Resultados das Consultas

### 1. Faturamento Total de Consultas por Convênio

| Convênio | Faturamento Total |
|---|---:|
| Bradesco Saúde | R$ 400,00 |

### 2. Média do Valor de Consulta por Especialidade

| Especialidade | Média |
|---|---:|
| Cardiologia | R$ 350,00 |
| Cardiologia Pediátrica | R$ 400,00 |

### 3. Valor Médio das Diárias por Tipo de Quarto

| Tipo de Quarto | Média da Diária |
|---|---:|
| UTI | R$ 466,67 |
| Apartamento | R$ 323,33 |

### 4. Total de Consultas por Médico

| Médico | Total |
|---|---:|
| Dr. Marcos Andrade | R$ 700,00 |
| Dra. Camila Rocha | R$ 1.000,00 |
| Dr. Roberto Silva | R$ 400,00 |
| Dra. Patricia Lima | R$ 280,00 |
| Dra. Vanessa Martins | R$ 550,00 |
| Dr. Gustavo Santos | R$ 320,00 |
| Dra. Claudia Castro | R$ 600,00 |
| Dra. Renata Mello | R$ 300,00 |

### 5. Soma de Diárias por Paciente Silva

| Paciente | Total |
|---|---:|
| Ana Silva | R$ 450,00 |
| João Pedro Silva | R$ 200,00 |

### 6. Contagem de Prescrições por Status

| Status | Total de Medicamentos |
|---|---:|
| Realizada | 70 |

### 7. Média de Consultas por Convênio e Especialidade

| Convênio | Especialidade | Média |
|---|---|---:|
| Unimed | Cardiologia | R$ 350,00 |
| Unimed | Cirurgia Geral | R$ 500,00 |
| Unimed | Pediatria | R$ 280,00 |
| Unimed Pleno | Cirurgia Plástica | R$ 600,00 |

### 8. Média de Diárias em Quartos de UTI

| Convênio | Média da Diária |
|---|---:|
| Unimed | R$ 475,00 |
| Bradesco Saúde | R$ 450,00 |

### 9. Medicamentos Prescritos por Médico

| Médico | Total de Medicamentos |
|---|---:|
| Dr. Marcos Andrade | 142 |
| Dra. Camila Rocha | 40 |
| Dr. Roberto Silva | 30 |
| Dra. Patricia Lima | 60 |
| Dra. Vanessa Martins | 10 |
| Dr. Gustavo Santos | 24 |
| Dra. Claudia Castro | 56 |

### 10. Valor Total e Média de Consultas por Paciente

| Paciente | Valor Total | Média |
|---|---:|---:|
| Maria Santos | R$ 280,00 | R$ 280,00 |

---

**Ferramenta utilizada:** MySQL Workbench  
**Banco de dados:** hospital_db  
**Linguagem:** SQL

**Autora:** Gabrielli
