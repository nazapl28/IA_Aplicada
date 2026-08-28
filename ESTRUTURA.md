# Estrutura do projeto

Uma coleção de livros sobre uso de inteligência artificial, cada um dirigido a um setor, com curso e palestra derivados.

## Pastas

```
IA_Aplicada\
├── CLAUDE.md              diretriz e estilo, comuns a tudo
├── ESTRUTURA.md           este arquivo
├── nucleo\                o que não depende de setor
└── NN-Setor\              uma pasta por obra
    ├── REGRAS.md          o que é específico daquela obra
    ├── livro\
    ├── curso\
    ├── palestra\
    └── divulgacao\
```

Cada pasta `NN-Setor` é um repositório git próprio, para que cada obra publique no seu ritmo, sem misturar histórico.

## O núcleo

| Arquivo | Conteúdo | Envelhece |
|---|---|---|
| `modos-de-erro.md` | Os seis modos de erro da IA generativa | pouco |
| `camadas-autorizacao.md` | Ferramenta, pessoa, dado, tarefa | pouco |
| `matriz-risco.md` | Impacto sobre direitos × autonomia da ferramenta | pouco |
| `glossario.md` | Termos de direito e de tecnologia | pouco |
| `modelo-capacitacao.md` | Programa de capacitação em dois eixos | pouco |
| `fornecedores.md` | Condições de OpenAI, Anthropic, Google, Microsoft | **rápido** |
| `VERIFICACAO-comum.md` | Registro do que foi conferido em fonte primária | médio |

`fornecedores.md` é o único arquivo que precisa de revisão de calendário. Ele existe em um lugar só justamente para não haver cinco cópias desatualizando em paralelo.

## Estado das obras

| Obra | Livro | Curso | Palestra |
|---|---|---|---|
| 01-Conselhos | **publicado**, ISBN 978-65-02-30710-6 | a fazer | a fazer |
| 02-Serviço público | a fazer | | |
| 03-Economia mista | a fazer | | |
| 04-Advocacia e contabilidade | a fazer | | |
| 05-Consultórios de saúde | a fazer | | |
| 06-Empresa privada | a fazer | | |

A numeração indica ordem de produção sugerida, não prioridade comercial. Serviço público e economia mista vêm cedo porque compartilham o alicerce jurídico do primeiro livro, o que reduz muito a pesquisa nova.

## Como um livro novo usa o núcleo

1. Lê `nucleo/` inteiro antes de começar.
2. Define o eixo jurídico do setor e o verifica em fonte primária. Esta é a parte que não se copia.
3. Adapta as peças do núcleo ao vocabulário e às situações daquele setor.
4. Escreve o que é próprio do setor: as etapas de trabalho, os personagens, os casos.
5. Se descobrir algo que vale para todos os setores, reporta antes de alterar o núcleo.

## O livro publicado

`01-Conselhos/livro/` contém a obra já publicada. O texto está fechado. Correções encontradas depois entram numa lista para segunda edição, não no arquivo.

Os artefatos saem de script: `gerar_capa.py`, `gerar_epub.sh`, `gerar_pdf.sh`, `preparar_pdf.py` e `divulgacao/gerar_carrossel.py`.
