# Fluxograma de pré-requisitos

Disciplinas obrigatórias da matriz 2018.2, por semestre. Uma seta **A → B** quer dizer que **A é pré-requisito de B**. Os pré-requisitos das optativas estão na [pasta de optativas](../optativas/).

```mermaid
flowchart TB
  subgraph S1["1º semestre"]
    N1["Química Geral"]
    N2["Cálculo I"]
    N3["Eletrônica Digital"]
    N4["Ética e Filosofia"]
    N5["Introdução à Engenharia de Telecomunicações"]
  end
  subgraph S2["2º semestre"]
    N6["Álgebra Linear"]
    N7["Cálculo II"]
    N8["Mecânica Geral"]
    N9["Introdução à Programação"]
  end
  subgraph S3["3º semestre"]
    N10["Ondulatória e Óptica"]
    N11["Cálculo III"]
    N12["Equações Diferenciais Ordinárias"]
    N13["Circuitos CC"]
    N14["Laboratório de Circuitos CC"]
  end
  subgraph S4["4º semestre"]
    N15["Eletromagnetismo Básico"]
    N16["Cálculo Numérico"]
    N17["Redes de Computadores I"]
    N18["Circuitos CA"]
    N19["Laboratório de Circuitos CA"]
  end
  subgraph S5["5º semestre"]
    N20["Eletromagnetismo Aplicado"]
    N21["Redes de Computadores II"]
    N22["Probabilidade e Estatística"]
    N23["Eletrônica Analógica I"]
    N24["Laboratório de Eletrônica Analógica"]
  end
  subgraph S6["6º semestre"]
    N25["Guias e Ondas"]
    N26["Gerência de Redes de Computadores"]
    N27["Sinais e Sistemas de Comunicação"]
    N28["Eletrônica Analógica II"]
    N29["Microcontroladores e Microprocessadores"]
  end
  subgraph S7["7º semestre"]
    N30["Antenas"]
    N31["Comunicação Óptica"]
    N32["Processamento Digital de Sinais"]
    N33["Laboratório de Sistemas de Comunicação"]
    N34["Economia para Engenharia"]
  end
  subgraph S8["8º semestre"]
    N35["Projeto de Sistemas de Rádio Enlace"]
    N36["Comunicação por Satélite"]
    N37["Princípios de Comunicação Digital"]
    N38["Higiene e Segurança do Trabalho"]
  end
  subgraph S9["9º semestre"]
    N39["Metodologia Científica e Tecnológica"]
    N40["Redes Móveis"]
    N41["Segurança de Redes de Computadores"]
    N42["Introdução à Automação Industrial e Controle"]
  end
  subgraph S10["10º semestre"]
    N43["Inovação Tecnológica"]
    N44["Projeto Social"]
    N45["Trabalho de Graduação Interdisciplinar"]
  end
  N2 --> N7
  N8 --> N10
  N7 --> N11
  N7 --> N12
  N10 --> N15
  N11 --> N15
  N2 --> N16
  N9 --> N16
  N3 --> N17
  N13 --> N18
  N13 --> N19
  N14 --> N19
  N15 --> N20
  N16 --> N20
  N17 --> N21
  N18 --> N23
  N18 --> N24
  N19 --> N24
  N20 --> N25
  N17 --> N26
  N18 --> N27
  N23 --> N28
  N3 --> N29
  N9 --> N29
  N25 --> N30
  N25 --> N31
  N27 --> N32
  N27 --> N33
  N30 --> N35
  N30 --> N36
  N27 --> N37
  N17 --> N40
  N17 --> N41
  N27 --> N42
  N20 --> N45
  N21 --> N45
  N32 --> N45
  N39 --> N45
```

## Lista por disciplina

| Disciplina | Semestre | Pré-requisitos |
|---|---|---|
| Química Geral | 1º | — |
| Cálculo I | 1º | — |
| Eletrônica Digital | 1º | — |
| Ética e Filosofia | 1º | — |
| Introdução à Engenharia de Telecomunicações | 1º | — |
| Álgebra Linear | 2º | — |
| Cálculo II | 2º | Cálculo I |
| Mecânica Geral | 2º | — |
| Introdução à Programação | 2º | — |
| Ondulatória e Óptica | 3º | Mecânica Geral |
| Cálculo III | 3º | Cálculo II |
| Equações Diferenciais Ordinárias | 3º | Cálculo II |
| Circuitos CC | 3º | — |
| Laboratório de Circuitos CC | 3º | — |
| Eletromagnetismo Básico | 4º | Ondulatória e Óptica, Cálculo III |
| Cálculo Numérico | 4º | Cálculo I, Introdução à Programação |
| Redes de Computadores I | 4º | Eletrônica Digital |
| Circuitos CA | 4º | Circuitos CC |
| Laboratório de Circuitos CA | 4º | Circuitos CC, Laboratório de Circuitos CC |
| Eletromagnetismo Aplicado | 5º | Eletromagnetismo Básico, Cálculo Numérico |
| Redes de Computadores II | 5º | Redes de Computadores I |
| Probabilidade e Estatística | 5º | — |
| Eletrônica Analógica I | 5º | Circuitos CA |
| Laboratório de Eletrônica Analógica | 5º | Circuitos CA, Laboratório de Circuitos CA |
| Guias e Ondas | 6º | Eletromagnetismo Aplicado |
| Gerência de Redes de Computadores | 6º | Redes de Computadores I |
| Sinais e Sistemas de Comunicação | 6º | Circuitos CA |
| Eletrônica Analógica II | 6º | Eletrônica Analógica I |
| Microcontroladores e Microprocessadores | 6º | Eletrônica Digital, Introdução à Programação |
| Antenas | 7º | Guias e Ondas |
| Comunicação Óptica | 7º | Guias e Ondas |
| Processamento Digital de Sinais | 7º | Sinais e Sistemas de Comunicação |
| Laboratório de Sistemas de Comunicação | 7º | Sinais e Sistemas de Comunicação |
| Economia para Engenharia | 7º | — |
| Projeto de Sistemas de Rádio Enlace | 8º | Antenas |
| Comunicação por Satélite | 8º | Antenas |
| Princípios de Comunicação Digital | 8º | Sinais e Sistemas de Comunicação |
| Higiene e Segurança do Trabalho (HST) | 8º | — |
| Metodologia Científica e Tecnológica | 9º | — |
| Redes Móveis | 9º | Redes de Computadores I |
| Segurança de Redes de Computadores | 9º | Redes de Computadores I |
| Introdução à Automação Industrial e Controle | 9º | Sinais e Sistemas de Comunicação |
| Inovação Tecnológica | 10º | — |
| Projeto Social | 10º | — |
| Trabalho de Graduação Interdisciplinar (TGI) | 10º | Eletromagnetismo Aplicado, Redes de Computadores II, Processamento Digital de Sinais, Metodologia Científica e Tecnológica |

> Fonte: matriz curricular 11892 (2018.2). Se os pré-requisitos mudarem, atualize este arquivo e os READMEs das disciplinas.
