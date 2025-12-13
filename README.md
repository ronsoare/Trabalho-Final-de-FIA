# Trabalho Final de FIA  
## Raciocínio Espacial Neuro-Simbólico com LTNtorch

**Professor:** Edjard de Souza Mota  

**Integrantes:**  
- Ronaldo Rodrigues Soares: ronaldo.soares@icomp.ufam.edu.br  
- Yan Silva: 
- José Dercy    

---

## Visão Geral do Projeto

Este projeto consiste no desenvolvimento de um **agente neuro-simbólico capaz de entender relações espaciais**.  
Diferente do Deep Learning tradicional, que se baseia apenas no mapeamento direto de **Input → Output**, este trabalho utiliza **Logic Tensor Networks (LTN)** para ensinar à rede **regras lógicas explícitas** sobre como objetos se relacionam entre si em um espaço bidimensional (2D).

O uso de LTN permite combinar aprendizado neural com conhecimento simbólico, tornando o modelo mais interpretável e alinhado a restrições lógicas previamente definidas.

---

# **Summary**

> - [**1 — Imports & Utils**](#scrollTo=nvxZZ2ZmDSDP)
>   - [**1.1 — Imports**](#scrollTo=hTRSbfppZDcU)
>   - [**1.2 — Utils**](#scrollTo=jl7v461pZJAI)
> - [**2 — The Data Structure**](#scrollTo=MRCo9bCJDlJ2)
>   - [**2.1 — Dataset Generator**](#scrollTo=E_goZXvvJdkS)
>   - [**2.2 — Dataset Plotting**](#scrollTo=F9NelndJMWI5)
> - [**3 — Main Tasks**](#scrollTo=W7skzjqGM2gI)
>	  - [**3.1 — Task 1: Taxonomy & Shapes**](#scrollTo=IhQRYeN-Nqao)
>	    - [**3.1.1 — Data generation**](#scrollTo=zF9bMx_2OCnA)
>	    - [**3.1.2 — Predicates**](#scrollTo=ejp6diiuPCaD)
>	    - [**3.1.3 — Axioms**](#scrollTo=jhhDr132PSeu)
>	  - [**3.2 — Task 2: Spatial Reasoning**](#scrollTo=E9jHpp4eQXt0)
>	    - [**3.2.1 — Predicates**](#scrollTo=RNIiIs_gQaT7)
>	    - [**3.2.2 — Axioms**](#scrollTo=oumv9hS5QjQz)
>	  - [**3.3 — Task 3: Horizontal Reasoning**](#scrollTo=f6Z9tyb3Qqkb)
>	  - [**3.4 — Task 4: Vertical Reasoning**](#scrollTo=pnYo2hdRQ75t)
>	    - [**3.4.1 — Predicates**](#scrollTo=48TukLZ3XjG-)
>	    - [**3.4.2 — Axioms**](#scrollTo=DA05tJOjXskz)
>	  - [**3.5 — Task 5: Compound Reasoning**](#scrollTo=1lb921QbSxzv)
> - [**4 — Training & Evaluate**](#scrollTo=2utzeQmfRgsJ)
>	  - [**4.1 — Training**](#scrollTo=IkMEX9SJbGVv)
>	  - [**4.2 — Evaluate**](#scrollTo=kTAxLL_fbLi-)
> - [**5 — Results**](#scrollTo=YP8_IeURbXm8)
>	  - [**5.1 — Loop Function**](#scrollTo=VBuozQnxb-32)
>	  - [**5.2 — Demo Mode**](#scrollTo=nkDlqtMdcL52)
>	  - [**5.3 — Results Finals**](#scrollTo=1G7RDAMhcQ-1)


---

# ** Arquivos do projeto
- 📓 [Notebook do Projeto](./Trabalho%203.ipynb)
- 🖼️ [Arquivo para ser usado nos experimentos](./imagem.jpg)
