<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

```
Este prompt coleta informações específicas de um indivíduo para gerar um plano de treino personalizado, levando em consideração suas características físicas, disponibilidade, preferências de treino, e outras variáveis importantes.

## Variáveis a serem Coletadas

1. **{{biotipo}}**
2. **{{disponibilidade_treino}}**
3. **{{tipo_de_treino}}**
4. **{{faixa_etaria}}**
5. **{{nível_de_experiência}}**
6. **{{objetivo}}**
7. **{{restrições_físicas}}**

## Regras

### **{{biotipo}}**

- **Ectomorfo:** Corpo naturalmente magro, metabolismo acelerado, dificuldade em ganhar peso e massa muscular.
- **Mesomorfo:** Corpo atlético, facilidade em ganhar massa muscular e perder gordura, boa resposta ao treinamento.
- **Endomorfo:** Corpo com tendência a acumular gordura, metabolismo mais lento, maior dificuldade em perder peso.

### **{{disponibilidade_treino}}**

- **1 dia:** Treino Full Body
- **3 dias:** Treino ABC
- **5 dias:** Treino ABCDE

### **{{tipo_de_treino}}**

- **Funcional:** Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais e múltiplos grupos musculares.
- **Maquinário:** Exercícios realizados em equipamentos, focados em isolar grupos musculares específicos.
- **Peso Livre:** Exercícios com pesos livres (halteres, barras, kettlebells) para trabalhar múltiplos grupos musculares simultaneamente.
- **Cardio:** Exercícios aeróbicos para melhorar a resistência cardiovascular (corrida, natação, ciclismo).
- **HIIT:** Treinos intervalados de alta intensidade, eficientes para queima de gordura e condicionamento.

### **{{faixa_etaria}}**

- **18-25 anos:** Enfoque em treinos intensos com maior capacidade de recuperação.
- **26-35 anos:** Equilíbrio entre intensidade e recuperação, com atenção ao fortalecimento muscular.
- **36-45 anos:** Maior foco em exercícios de mobilidade e prevenção de lesões.
- **46-60 anos:** Priorizar exercícios que preservem a massa muscular e articulações, com menor impacto.
- **60+ anos:** Exercícios de baixo impacto, foco em mobilidade, força funcional e equilíbrio.

### **{{nível_de_experiência}}**

- **Iniciante:** Treinos com foco em técnica, baixa intensidade e progressão gradual.
- **Intermediário:** Treinos que desafiem a força e a resistência, com progressões moderadas.
- **Avançado:** Treinos intensos com maior volume e técnicas avançadas, como dropsets e superséries.

### **{{objetivo}}**

- **Ganho de Massa:** Foco em exercícios de hipertrofia com séries moderadas a pesadas e menor ênfase em cardio.
- **Perda de Gordura:** Combinação de exercícios de força com cardio e HIIT para maximizar a queima calórica.
- **Condicionamento:** Equilíbrio entre força, resistência e cardio para melhorar o desempenho geral.
- **Manutenção:** Treinos equilibrados para manter o condicionamento atual sem grandes variações de peso.

### **{{restrições_físicas}}**

1. **Nenhuma restrição:** Treino pode ser elaborado sem limitações específicas, utilizando todas as opções de exercícios disponíveis.
2. **Lesões articulares:** Se há problemas nas articulações (joelhos, ombros, tornozelos, etc.), priorizar exercícios de baixo impacto e evitar sobrecarga nas áreas afetadas. Incluir fortalecimento específico para articulações.
3. **Problemas de coluna:** Em casos de hérnia, escoliose ou outros problemas na coluna, evitar exercícios que envolvam grande compressão da coluna ou movimentos de torção. Priorizar exercícios de fortalecimento do core e postura.
4. **Condições cardíacas ou respiratórias:** Adaptar a intensidade do treino, focando em exercícios que não elevem exageradamente a frequência cardíaca. Incluir pausas maiores entre séries e exercícios aeróbicos de intensidade moderada.

## Resultado Esperado

Com base nas informações fornecidas, crie um plano de treino personalizado que atenda às necessidades específicas da pessoa, levando em consideração o biotipo, disponibilidade de treino, tipo de treino preferido, faixa etária, nível de experiência, objetivo e quaisquer restrições físicas.

```
