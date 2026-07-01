## Programa Completo de Disciplina / Complete Discipline Program

**1. Código:** PSI0322
**Ano:** 2027

---

**2. Nome da Disciplina:**  
Processamento de Áudio e Imagem  
Audio and Image Processing

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
[ ]  Sim  
[X] Não  

Em caso afirmativo, informar:  
[ ]  Viagem estruturante  
[ ]  Viagem não estruturante   

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
[0] horas  

---

**9. Verifica conflito de horário?**
[ ] Sim
[x] Não

---

**10. Responsável:**  
N° USP 1488469 Nome: Magno Teófilo Madeira da Silva  
N° USP 63599 Nome: Vítor Heloiz 

---

**11 Cursos atendidos:** Engenharia Eletrônica e de Sistemas Computacionais

---

**12. Ementa:**
* [texto em português]: O curso visa proporcionar aos alunos uma base sólida em processamento de sinais de tempo discreto, particularmente amostragem, transformadas de Fourier e projeto de filtros digitais, habilitando-os aplicar os conceitos em problemas de estimação espectral, mudança de taxa de amostragem e filtragem linear de imagens.



* [texto em inglês]: The course intends to give students a solid foundation in discrete-time signal processing, particularly sampling, Fourier transform and digital filter design.  The students should be able to apply the techniques in spectrum estimation, change of sampling rates, and linear filtering of images.

---

**13 Objetivo:** 
* [texto em português]: 
O estudante deve ser capaz de: 

1.	Compreender como amostrar sinais de tempo contínuo sem perda de informação.
2.	Calcular e interpretar a transformada de Fourier de tempo discreto (TFTD), compreender a relação entre a TFTD, a série de Fourier, e a transformada de Fourier (TF) de sinais de tempo contínuo.
3.	Calcular e interpretar os resultados da transformada de discreta de Fourier (TDF), e sua relação com a TFTD e a TF.
4.	Aplicar a TDF para análise espectral de sinais determinísticos periódicos e não periódicos.
5.	Compreender o princípio de funcionamento da transformada rápida de Fourier (FFT) e sua utilização a partir de bibliotecas prontas.
6.	A transformada z de sinais de tempo discreto.  Função de transferência de sistemas lineares e invariantes no tempo.
7.	Identificar os diferentes tipos de filtros digitais – resposta ao impulso finita (FIR), fase linear, resposta ao impulso infinita (IIR).  Projetar filtros digitais para aplicações simples.  Escolher a técnica de projeto mais adequada (mínimos quadrados, janelamento, min-max).
8.	Projetar e implementar sistemas para mudança de taxa de amostragem de sinais digitais.
9.	Compreender e aplicar a transformada de Fourier para sinais multidimensionais (como imagens). 
10.	Compreender e projetar filtros multidimensionais em aplicações simples.



* [texto em inglês]: The student must be able to: 

1.	Understand how to sample continuous-time signals without information loss.
2.	Compute and interpret the discrete-time Fourier transform (DTFT), and understand its relation to the Fourier series and the Fourier transform (FT).
3.	Compute and interpret the discrete Fourier transform (DFT), and its relation to the DTFT and FT.
4.	Apply the DFT to spectral analysis of deterministic periodic and non-periodic signals.
5.	Understand the basis of the FFT algorithm, and its use through computer libraries.
6.	The z transform of discrete-time signals. Transfer fuction of linear time-invariant systems.
7.	Identify the different kinds of digital filters – finite and infinite impulse response, linear phase.  Design a digital filter for simple applications, choosing the most adequate approximation (least-squares, windowing, min-max).
8.	Design and implement systems for change of sampling rate.
9.	Understand and apply the Fourier transform for multidimensional signals.
10.	Understand and design multidimensional linear filters in simple applications.

---

**14. Conteúdo Programático:**
* [texto em português]: Esta disciplina visa proporcionar uma compreensão dos conceitos básicos de processamento de sinais amostrados e sinais determinísticos de tempo discreto de modo geral, usando como base as diferentes versões da Transformada de Fourier (TF) e suas interrelações.  Também se espera que os alunos ao final do curso sejam capazes de aplicar as técnicas aprendidas em aplicações simples, que serão vistas ao longo do curso.  Para tanto são inicialmente descritas condições para reconstrução de sinais amostrados, e é enunciado o teorema da amostragem.  Em seguida é apresentada a Transformada de Fourier de Tempo Discreto (TFTD), suas propriedades, e sua relação com a Transformada de Fourier, e enunciado e demonstrado graficamente o Teorema da Amostragem.  
A Transformada Discreta de Fourier (TDF) é apresentada como uma aproximação da TF, e também como um truncamento da TFTD. São apresentadas as propriedades da TDF e sua relação com a TF e a TFTD, e técnicas para estimação espectral (de sinais determinísticos) usando a TDF.  O princípio de funcionamento da FFT (versão rápida da TDF) é apresentado.
A transformada z é apresentada, e seu uso para descrever sistemas lineares e invariantes no tempo.
Finalmente, são descritas aproximações para filtros digitais, e descritas diferentes técnicas de projetos de filtros digitais, aplicadas a um exemplo de mudança de taxa de amostragem.  Os conceitos vistos anteriormente são estendidos para sinais multidimensionais (particularmente imagens), em exemplos de aplicação como filtros de imagens e tomografia.

* [texto em inglês]: This course aims to provide the students with an understanding of the basic concepts of signal processing of sampled signals, or of discrete-time deterministic systems in general.  The course has a focus on the different versions of the Fourier Transform (FT) and their interrelations.  It is also expected that the students be able to use the techniques presented during the course in simple applications.  The course begins discussing conditions for perfect reconstruction of sampled signals, and the Sampling Theorem.  The Discrete-Time Fourier Transform (DTFT) and its relation to the TF are discussed, and the Sampling Theorem is proven graphically.  
The Discrete Fourier Transform (DFT) is then presented both as an approximation to the FT and as a truncation of the DTFT.  The properties of the DFT are discussed, along with its relations to the FT and DTFT and techniques for spectrum estimation for deterministic signals.  The fast Fourier transform (FFT) is presented.
The z transform is presented, as well as its use to describe linear time-invariant systems.
Different approximations and techniques for digital filter design are described, and the students are invited to apply filters in sampling-rate transformation applications. The concepts of transforms and filters are extended to multi-dimensional signals, with applications to image filtering and tomography.

---

**15. Métodos de ensino:**
* [texto em português]: Abordagem integrada que combina aulas expositivas teóricas com metodologias ativas de aprendizagem e atividades práticas.
* [texto em inglês]: An integrated approach combining theoretical lectures with active learning methodologies and practical activities.

---

**16. Método de avaliação :**
* [texto em português]: A avaliação dos estudantes será processual e integrada, estruturada para mensurar tanto o domínio dos fundamentos matemáticos quanto a capacidade de implementação prática em processamento digital de sinais (PDS). A nota final será composta por avaliações teóricas individuais, focadas na dedução e interpretação de transformadas (TFTD, TDF, FFT e Transformada Z), teoremas de amostragem e formulação matemática de filtros lineares e invariantes no tempo (LTI). Complementarmente, serão realizadas atividades práticas de laboratório e programação, onde os alunos utilizarão bibliotecas computacionais para realizar análise espectral de sinais, implementar algoritmos de mudança de taxa de amostragem e processar sinais multidimensionais (imagens). Estas atividades culminarão no desenvolvimento de um projeto técnico, voltado ao projeto, escolha de técnicas de otimização (janelamento, mínimos quadrados ou min-max) e implementação de filtros digitais (FIR e IIR) para uma aplicação real.
* [texto em inglês]: Student assessment will be formative and integrated, structured to measure both the mastery of mathematical foundations and the capacity for practical implementation in digital signal processing (DSP). The final grade will be based on individual theoretical exams, focusing on the derivation and interpretation of transforms (DTFT, DFT, FFT, and Z-Transform), sampling theorems, and the mathematical formulation of linear time-invariant (LTI) systems. Complementarily, practical laboratory and programming assignments will be conducted, where students will use computational libraries to perform spectral analysis, implement sampling rate conversion algorithms, and process multidimensional signals (images). These activities will culminate in the development of a technical project, aimed at the design, selection of optimization techniques (windowing, least squares, or min-max), and implementation of digital filters (FIR and IIR) for a real-world application.

---

**17. Critério de avaliação:**
* [texto em português]: Os critérios de avaliação fundamentam-se no rigor matemático e na habilidade de implementação computacional de algoritmos de processamento de sinais. Será avaliada a exatidão conceitual na aplicação de teoremas de amostragem e na interpretação espectral via transformadas (TFTD, TDF, FFT e Z), além da precisão técnica no projeto e escolha metodológica (janelamento, mínimos quadrados ou min-max) para filtros digitais FIR, IIR e multidimensionais. Consideram-se também a eficiência e a correção do código desenvolvido nas atividades práticas para mudança de taxa de amostragem e processamento de imagens, bem como a capacidade analítica de justificar as decisões de engenharia tomadas no projeto final.
  
* [texto em inglês]: The assessment criteria are based on mathematical rigor and the ability to computationally implement signal processing algorithms. Evaluation will focus on conceptual accuracy in applying sampling theorems and interpreting spectral data via transforms (DTFT, DFT, FFT, and Z-transform), alongside technical precision in the design and methodological choice (windowing, least squares, or min-max) for FIR, IIR, and multidimensional digital filters. Additionally, the criteria include the efficiency and correctness of the code developed in practical assignments for sampling rate conversion and image processing, as well as the analytical capacity to justify the engineering decisions made in the final project.

---

**18. Normas de recuperação:**
* [texto em português]: A recuperação será focada nos tópicos de maior dificuldade identificados durante o semestre. O aluno deverá realizar estudos dirigidos e exercícios complementares sobre os conteúdos específicos não atingidos, seguidos de uma nova avaliação para verificar a superação das deficiências.
* [texto em inglês]: Remedial work will focus on the topics of greatest difficulty identified during the semester. Students must complete guided studies and complementary exercises on the specific contents that were not mastered, followed by a new assessment to verify the resolution of learning gaps.

---

**19. Bibliografia básica:**
* [texto em português]:  
A base teórica que será utilizada no curso terá origem variada, podendo ser composta de livros de referência, apostilas, vídeos, entre outros, e poderá ser atualizada constantemente.  Os docentes deverão apresentar a bibliografia referente ao tema em questão quando necessário. Algumas das bibliografias que serão utilizadas são:

1.	Nascimento, V.H.: Processamento de Áudio e Imagem (notas de aula, e-disciplinas), 2025.
2.	Prandoni, P. e Vetterli, M.. Signal Processing for Communications. EPFL Press, 2008. Os autores disponibilizam uma versão on-line em http://www.sp4comm.org/getit.html.
3.	Diniz, P.S.R.;Barros da Silva, E.A.; Lima Netto, S.: Processamento Digital de Sinais: Projeto e análise de sistemas, 2ª edição, Porto Alegre, Bookman, 2014.
4.	Oppenheim A.V.; Schafer, R.W.; Buck, J.R. - Discrete-Time Signal Processing. Prentice-Hall, 2a ed., 1999.




* [texto em inglês]: 
The theoretical foundation used in the course will have diverse origins, including reference books, handouts, videos, among others, and may be constantly updated. The instructors will provide the bibliography related to the topic in question when needed. Some of the bibliography that will be used are: 

1.	Nascimento, V.H.: Processamento de Áudio e Imagem (notas de aula, e-disciplinas), 2025.
2.	Prandoni, P. e Vetterli, M.. Signal Processing for Communications. EPFL Press, 2008. Os autores disponibilizam uma versão on-line em http://www.sp4comm.org/getit.html.
3.	Diniz, P.S.R.;Barros da Silva, E.A.; Lima Netto, S.: Digital Signal Processing: System Analysis and Design, 2nd edition, Cambridge University Press, 2010.
4.	Oppenheim A.V.; Schafer, R.W.; Buck, J.R. - Discrete-Time Signal Processing. Prentice-Hall, 2a ed., 1999.


---

**20. Bibliográfica complementar:**
* [texto em português]: N/A
* [texto em inglês]: N/A


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
- [ ] 1. Erradicação da Pobreza
- [ ] 2. Fome Zero e Agricultura Sustentável
- [ ] 3. Saúde e Bem-Estar
- [ ] 4. Educação de Qualidade
- [ ] 5. Igualdade de Gênero
- [ ] 6. Água Potável e Saneamento
- [ ] 7. Energia Limpa e Acessível
- [ ] 8. Trabalho Decente e Crescimento Econômico
- [X] 9. Indústria, Inovação e Infraestrutura
- [ ] 10. Redução das Desigualdades
- [X] 11. Cidades e Comunidades Sustentáveis
- [ ] 12. Consumo e Produção Responsáveis
- [ ] 13. Ação Contra a Mudança Global do Clima
- [ ] 14. Vida na Água
- [ ] 15. Vida Terrestre
- [ ] 16. Paz, Justiça e Instituições Eficazes
- [ ] 17. Parcerias e Meios de Implementação