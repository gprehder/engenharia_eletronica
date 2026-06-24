## Programa Completo de Disciplina / Complete Discipline Program

**1. Código:** PSI0124
**Ano:** 2027

---

**2. Nome da Disciplina:**  
Microcontroladores 2
Microcontrollers 2

---

**3. Créditos:** 
[3] Aula (1 crédito = 15 h)
[0] Trabalho (1 crédito = 30 h)
[0] Extensão (em horas)
[ ] É exclusiva para atividade de extensão?

---

**3A. – Oferecimento em língua estrangeira**
[ ] Oferecida em língua estrangeira conforme previsto na Resolução CoG - 8.811, de 28/05/2025.

---

**4. Possui viagem didática?**
[ ] Sim
[X] Não

Em caso afirmativo, informar:
[ ] Viagem estruturante
[ ] Viagem não estruturante

Atividades a serem desenvolvidas:
N/A

---

**5. Oferece 2ª avaliação?**
[X] Sim
[ ] Não

---

**6. Duração:**
[15] semanas

---

**7. Tipo:**
[ ] Anual
[X] Semestral
[ ] Quadrimestral

---

**8. Estágio:**
[0] horas / hours

---

**9. Verifica conflito de horário?**
[ ] Sim
[X] Não

---

**10. Responsável:**
N° USP 5053200 Nome: Gustavo Rehder
Nome: Bruno Sanches
Nome: Laisa Biase

**11 Cursos atendidos:** Engenharia Eletrônica e de Sistemas Computacionais

---

**12. Ementa:**

* [texto em português]: Este curso é um estudo abrangente de design e programação de sistemas embarcados com foco em microcontroladores. Os alunos aprenderão a importância dos sistemas operacionais embarcados e analisarão os componentes de sistemas embarcados, levando em consideração o particionamento de hardware e software. Eles irão compilar e instalar sistemas operacionais em microcontroladores. Habilidades práticas em programação de sistemas embarcados e comunicação.

* [texto em inglês]: This course is a comprehensive study of designing and programming embedded systems with a focus on microcontrollers. Students will learn the significance of embedded operating systems and analyze the components of embedded systems while considering hardware-software partitioning. They will compile and install operating systems on microcontrollers, write and adapt operating system components. Practical skills in embedded systems programming and wireless communication will be acquired.

---

**13. Objetivo:**

* [texto em português]: A disciplina em questão tem como foco o desenvolvimento das competências definidas para o curso de Engenharia Eletrônica e de Sistemas Computacionais nas proporções estabelecidas pelo projeto pedagógico. Para isso, os seguintes Objetivos de Aprendizagem foram estabelecidos:

  1. Justificar a necessidade de um sistema operacional de tempo real (RTOS) em comparação com arquiteturas bare-metal para aplicações de alta complexidade. 

  2. Configurar o ambiente de desenvolvimento, compilar o RTOS e embarcar o firmware resultante no microcontrolador.

  3. Modelar uma aplicação multitarefa, decompondo o sistema em threads com prioridades adequadas para garantir o determinismo temporal.

  4. Implementar primitivas de exclusão mútua e sincronização (Mutexes e Semáforos) para gerenciar recursos compartilhados e evitar condições de corrida.

  5. Desenvolver rotinas de serviço de interrupção (ISRs) integradas ao RTOS, utilizando técnicas de processamento diferido (deferred interrupt processing).

  6. Integrar barramentos de comunicação serial (UART, I2C e SPI) ao ambiente multitarefa, garantindo o acesso seguro e assíncrono aos periféricos.

  7. Instrumentar o código embarcado utilizando técnicas de depuração em hardware, assertions e subsistemas de logging.

  8. Avaliar o desempenho e a confiabilidade do sistema através da análise de métricas como latência, uso de CPU, tempo de troca de contexto e monitoramento de stack.



* [texto em inglês]: The discipline in question focuses on developing the competencies defined for the Electronic and Computational Systems Engineering in the proportions established by the pedagogical project. For this purpose, the following Learning Objectives have been established:

  1. Justify the need for a real-time operating system (RTOS) compared to bare-metal architectures for high-complexity applications.

  2. Configure the development environment, compile the RTOS, and flash the resulting firmware onto the microcontroller.

  3. Model a multitasking application, decomposing the system into threads with appropriate priorities to guarantee temporal determinism.

  4. Implement mutual exclusion and synchronization primitives (Mutexes and Semaphores) to manage shared resources and prevent race conditions.

  5. Develop interrupt service routines (ISRs) integrated with the RTOS, utilizing deferred interrupt processing techniques.

  6. Integrate serial communication buses (UART, I2C, and SPI) into the multitasking environment, ensuring secure and asynchronous access to peripherals.

  7. Instrument the embedded code using hardware debugging techniques, assertions, and logging subsystems.

  8. Evaluate system performance and reliability by analyzing metrics such as latency, CPU utilization, context switch time, and stack monitoring.

---

**14. Conteúdo Programático:**

* [texto em português]: Este curso oferece um estudo aprofundado sobre o projeto e a programação de sistemas embarcados complexos, com foco central na utilização de Sistemas Operacionais de Tempo Real (RTOS). Os alunos analisarão as diferenças fundamentais entre arquiteturas bare-metal e RTOS, aprendendo a justificar sua adoção com base nos requisitos do sistema. Ao longo da disciplina, serão desenvolvidas habilidades práticas para configurar, compilar e embarcar o ecossistema do RTOS no hardware. O curso aborda a modelagem de aplicações multitarefa através da divisão do sistema em threads, gerenciamento de prioridades e o uso de primitivas de exclusão mútua e sincronização (Mutexes e Semáforos) para evitar condições de corrida e travamentos. Adicionalmente, os alunos aprenderão a integrar rotinas de interrupção (ISRs) eficientes e barramentos de comunicação serial (UART, I2C e SPI) de forma assíncrona e segura ao ambiente multitarefa. Por fim, serão exploradas técnicas avançadas de instrumentação, como sistemas de logging e depuração em hardware, capacitando os estudantes a avaliar o desempenho e a confiabilidade do sistema por meio de métricas de tempo real e monitoramento de falhas.

* [texto em inglês]: This course offers an in-depth study of the design and programming of complex embedded systems, with a central focus on the utilization of Real-Time Operating Systems (RTOS). Students will analyze the fundamental differences between bare-metal architectures and RTOS, learning to justify their adoption based on system requirements. Throughout the discipline, practical skills will be developed to configure, compile, and flash the RTOS ecosystem onto the hardware. The course covers multitasking application modeling by decomposing the system into threads, managing priorities, and using mutual exclusion and synchronization primitives (Mutexes and Semaphores) to prevent race conditions and deadlocks. Additionally, students will learn to integrate efficient interrupt service routines (ISRs) and serial communication buses (UART, I2C, and SPI) in a secure, asynchronous manner within the multitasking environment. Finally, advanced instrumentation techniques—such as logging systems and hardware debugging—will be explored, enabling students to evaluate system performance and reliability through real-time metrics and fault monitoring.

---

**15. Métodos de ensino:**

* [texto em português]: Abordagem integrada combinando aulas expositivas, atividades práticas em laboratório, exercícios de programação em baixo nível, desenvolvimento de projetos embarcados e metodologias ativas de aprendizagem.

* [texto em inglês]: Integrated approach combining theoretical lectures, laboratory activities, low-level programming exercises, embedded systems project development, and active learning methodologies.

---

**16. Método de avaliação :**

* [texto em português]: A avaliação será realizada de forma contínua e diversificada, incluindo exercícios de programação, atividades práticas em laboratório, projetos de sistemas embarcados, avaliações formativas de curto prazo e provas somativas.

* [texto em inglês]: Assessment will be conducted in a continuous and diversified manner, including programming exercises, laboratory activities, embedded systems projects, short-term formative assessments, and summative exams.

---

**17. Critério de avaliação:**

* [texto em português]: O desempenho do estudante será avaliado com base na capacidade de compreender e aplicar conceitos de sistemas embarcados, programar periféricos utilizando registradores, desenvolver máquinas de estados finitos, integrar hardware e software em aplicações práticas e validar experimentalmente o funcionamento de sistemas microcontrolados.

* [texto em inglês]: Student performance will be evaluated based on the ability to understand and apply embedded systems concepts, program peripherals using registers, develop finite state machines, integrate hardware and software in practical applications, and experimentally validate microcontroller-based systems.

---

**18. Normas de recuperação:**

* [texto em português]: A recuperação será focada nos tópicos de maior dificuldade identificados ao longo do semestre. O aluno deverá realizar estudos dirigidos, atividades práticas complementares e exercícios adicionais envolvendo programação e integração de sistemas embarcados, seguidos de nova avaliação para verificação da superação das deficiências identificadas.

* [texto em inglês]: Remedial work will focus on the topics of greatest difficulty identified throughout the semester. Students must complete guided studies, complementary practical activities, and additional exercises involving programming and embedded systems integration, followed by a new assessment to verify the resolution of the identified deficiencies.

---

**19. Bibliografia básica:**

* [texto em português]:
  [1] Floyd, Thomas. Sistemas digitais. 9ª edição. Grupo A, 2011.
  [2] Vahid, Frank. Sistemas digitais: projeto, otimização e HDLs. Grupo A, 2008.
  [3] Jonathan W. Valvano. Embedded Systems: Introduction to ARM Cortex-M Microcontrollers. 5th Edition, 2017.

* [texto em inglês]:
  [1] Floyd, Thomas. Digital Systems. 9th edition. Grupo A, 2011.
  [2] Vahid, Frank. Digital Systems: Design, Optimization and HDLs. Grupo A, 2008.
  [3] Jonathan W. Valvano. Embedded Systems: Introduction to ARM Cortex-M Microcontrollers. 5th Edition, 2017.

---

**20. Bibliográfica complementar:**

* [texto em português]:
  [4] Patterson, David; Hennessy, John. Organização e Projeto de Computadores. Elsevier.
  [5] Yiu, Joseph. The Definitive Guide to ARM Cortex-M3 and Cortex-M4 Processors. Newnes.

* [texto em inglês]:
  [4] Patterson, David; Hennessy, John. Computer Organization and Design. Elsevier.
  [5] Yiu, Joseph. The Definitive Guide to ARM Cortex-M3 and Cortex-M4 Processors. Newnes.

---

**21. Atividade de extensão - Grupo social alvo da atividade:**

* [texto em português]: N/A

* [texto em inglês]: N/A

---

**22. Atividade de extensão - Objetivos da atividade:**

* [texto em português]: N/A

* [texto em inglês]: N/A

---

**23 Atividade de extensão - Descrição da atividade:**

* [texto em português]: N/A

* [texto em inglês]: N/A

---

**24 Atividade de extensão - Indicadores de avaliação da atividade:**

* [texto em português]: N/A

* [texto em inglês]: N/A

---

**25. Objetivos de Desenvolvimento Sustentável (ODS):**

* [ ] 1. Erradicação da Pobreza
* [ ] 2. Fome Zero e Agricultura Sustentável
* [ ] 3. Saúde e Bem-Estar
* [x] 4. Educação de Qualidade
* [ ] 5. Igualdade de Gênero
* [ ] 6. Água Potável e Saneamento
* [ ] 7. Energia Limpa e Acessível
* [ ] 8. Trabalho Decente e Crescimento Econômico
* [x] 9. Indústria, Inovação e Infraestrutura
* [ ] 10. Redução das Desigualdades
* [x] 11. Cidades e Comunidades Sustentáveis
* [ ] 12. Consumo e Produção Responsáveis
* [ ] 13. Ação Contra a Mudança Global do Clima
* [ ] 14. Vida na Água
* [ ] 15. Vida Terrestre
* [ ] 16. Paz, Justiça e Instituições Eficazes
* [ ] 17. Parcerias e Meios de Implementação
