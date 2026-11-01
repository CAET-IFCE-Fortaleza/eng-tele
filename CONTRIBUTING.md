# Como contribuir

Obrigado por querer ajudar! Este repositório só cresce com material de quem está cursando. Este guia explica **o que** pode ser enviado, **como** nomear e **como** enviar.

## O que pode ser enviado

| ✅ Pode | ❌ Não pode |
|---|---|
| Resumos e anotações de aula **feitos por você** | Livros em PDF ou capítulos escaneados (direitos autorais) |
| Listas de exercícios e suas resoluções | Provas antigas **sem autorização do professor** |
| Provas antigas, **se o professor autorizar** | Dados pessoais de colegas (nome + matrícula, notas, fotos) |
| Códigos, simulações, planilhas de laboratório | Trabalhos feitos para entregar como se fossem seus (plágio) |
| Links para vídeos, cursos e sites úteis | Arquivos enormes (vídeos, ISOs): coloque um link |

Na dúvida, pergunte ao CAET antes de enviar.

## Onde colocar

Cada disciplina tem a mesma estrutura:

```
s04/redes-de-computadores-01/
├── README.md          ← informações oficiais (não precisa mexer)
├── resumos/           ← resumos, anotações, mapas mentais
├── listas/            ← listas de exercícios e resoluções
├── provas-antigas/    ← provas de semestres anteriores (com autorização)
└── dicas.md           ← dicas em texto: edite direto aqui
```

Se o material for de uma optativa, ele vai em `optativas/<disciplina>/`. Coisas de TCC, TGI e estágio vão em `tcc-e-estagio/`.

## Como nomear os arquivos

Use o padrão `ano-semestre_tipo_assunto_autor.extensão`, tudo em minúsculas, sem acentos e sem espaços:

```
2026-2_resumo_camada-de-transporte_maria-souza.pdf
2026-1_lista-02_subredes_resolvida.pdf
2025-2_prova-01_prof-autorizou.pdf
```

- **ano-semestre**: quando a disciplina foi cursada (ex.: `2026-2`).
- **tipo**: `resumo`, `lista-01`, `prova-01`, `slides`, `codigo`, `relatorio`…
- **autor**: opcional, se quiser receber o crédito.

Formatos preferidos: **PDF** para documentos, **Markdown** (`.md`) para texto, e o código-fonte original (`.py`, `.c`, `.m`, `.ipynb`…) para programas.

## Como enviar (pelo navegador)

1. Crie uma conta gratuita no [GitHub](https://github.com/signup), se ainda não tiver.
2. Entre na pasta da disciplina e depois na subpasta certa (ex.: `listas/`).
3. Clique em **Add file → Upload files** e arraste os arquivos.
4. Em "Commit changes", escreva uma descrição curta (ex.: *Adiciona lista 2 de Redes I resolvida*).
5. Selecione **Create a new branch … and start a pull request** e confirme.
6. Pronto! Alguém do CAET revisa e aprova. Se faltar algo, comentamos no próprio pull request.

Para **dicas**, abra o `dicas.md` da disciplina, clique no ícone de lápis ✏️, escreva e siga os mesmos passos 4 a 6.

## Corrigir informações

Achou um erro na ementa, na bibliografia ou nos pré-requisitos? [Abra uma issue de correção](https://github.com/CAET-IFCE-Fortaleza/eng-tele/issues/new?template=correcao.yml) ou edite o README da disciplina e mande um pull request.

Quer pedir material de alguma disciplina? [Abra um pedido](https://github.com/CAET-IFCE-Fortaleza/eng-tele/issues/new?template=pedido-material.yml).

## Licença

Ao enviar material de sua autoria, você concorda em disponibilizá-lo sob a licença [CC BY-SA 4.0](LICENSE). Material de terceiros (como provas de professores) continua pertencendo ao autor original e só deve ser enviado com autorização.
