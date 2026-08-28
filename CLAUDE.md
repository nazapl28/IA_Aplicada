# Diretriz do projeto IA Aplicada

Vale para todos os livros, cursos e palestras desta pasta. Cada obra tem seu próprio `REGRAS.md` com o que for específico dela.

---

## Regra 1. Pense antes de escrever

**Não faça suposições. Não oculte dúvidas. Exponha os *trade-offs*.**

- Declare suas suposições explicitamente. Se estiver incerto, pergunte.
- Se houver múltiplas interpretações, apresente-as. Não escolha silenciosamente.
- Se existir uma abordagem mais simples, mencione-a.
- Se algo não estiver claro, pare. Identifique o que causa confusão. Pergunte.

## Regra 2. Simplicidade em primeiro lugar

**O mínimo de texto necessário para desenvolver o tema. Nada de especulações.**

- Sem informação além do que foi pedido. Sem abstração, sem divagação.
- Se você escreveu 200 linhas e cabiam 50, reescreva.

## Regra 3. Alterações cirúrgicas

**Mexa apenas no necessário. Limpe apenas a sua própria bagunça.**

- Não tente melhorar texto adjacente que não precisa de correção.
- Siga o estilo existente, mesmo que você fizesse diferente.
- Se notar texto obsoleto não relacionado, mencione. Não exclua.
- Removeu algo? Remova também o que ficou órfão por causa disso.

Teste: cada linha alterada precisa estar ligada ao que foi pedido.

## Regra 4. Execução orientada a objetivos

Transforme a tarefa em objetivo verificável e apresente o plano antes de tarefas longas. Ao final, verifique e reporte o que sobrou.

## Regra 5. O núcleo é somente leitura

**Nenhum arquivo de `nucleo/` pode ser criado, alterado, renomeado, movido ou excluído durante o trabalho em uma obra.**

Vale para qualquer edição, inclusive a que parecer trivial: corrigir uma vírgula, atualizar uma data, ajustar um termo. O núcleo alimenta todos os livros. Uma alteração feita de passagem enquanto se escreve um capítulo repercute em obras que nem foram abertas.

O caminho correto é o inverso. A obra **lê** o núcleo e escreve a versão adaptada dentro da própria pasta, com o vocabulário do seu setor. A fonte permanece intacta.

Encontrou erro, defasagem ou lacuna no núcleo? **Reporte e pare.** Descreva o que está errado e em qual arquivo, depois siga com a tarefa em curso. Não corrija por iniciativa própria.

A única exceção é a autorização expressa: o usuário dizer, naquela conversa, que a tarefa é trabalhar no núcleo. Aí o núcleo deixa de ser fonte e passa a ser o objeto do trabalho, sob as regras 1 a 4.

---

## Estilo de escrita

Estas regras foram construídas ao longo do primeiro livro, corrigindo defeito por defeito. Elas valem para tudo o que for escrito aqui.

Antes de qualquer entrega — capítulo novo, revisão de capítulo, texto avulso — rode a skill `human` para tirar a cara de texto gerado por IA. Só depois confira o texto contra as regras abaixo.

**Proibido em prosa corrida:**

- **Travessão em aposto.** É a marca mais visível de texto gerado por IA em português. Permitido apenas em entrada de referência ABNT (`ANPD — AGÊNCIA NACIONAL...`), em cabeçalho de artigo de minuta normativa e em enumeração dentro de apêndice.
- **A construção `, e`.** Correta em inglês, ruim em português corrido. A única exceção é aposto com par de vírgulas: `o texto que sobrou, e que está em vigor, é este`.
- **Aspas retas.** Só aspas curvas: `“ ”`.
- **Dois-pontos como conectivo.** Usar dois-pontos para ligar duas orações completas, no lugar de `porque`, `pois` ou um ponto final, é hábito do inglês. Em excesso, é uma das marcas mais claras de texto gerado por IA em português. Reserve dois-pontos para enumeração, citação direta e aposto curto de um substantivo — nunca para explicar ou justificar a frase anterior.
- **Muletas de ênfase:** `vale dizer`, `convém notar`, `é importante ressaltar`, `cabe destacar`.
- **Vocabulário inflado:** crucial, fundamental, essencial, primordial, marco, ponto de virada, cenário em constante evolução.
- **Fuga do verbo ser:** `atua como`, `configura-se como`, `funciona como`, `apresenta-se como`. Escreva `é`.
- **Gerúndio de análise no fim da frase:** `, reforçando sua importância`, `, consolidando a posição`.
- **Atribuição vaga:** `especialistas apontam`, `segundo analistas`.
- **Fechamento formulaico:** `em suma`, `em conclusão`, `apesar dos desafios`.

**Cuidados que só aparecem na releitura:**

- Ao retirar um conectivo, a frase que sobra costuma ficar manca. O erro típico é o gerúndio de ligação entrando no lugar: `com os capítulos seguintes mostrando`, `com a tentação sendo limitá-la`. Prefira frase nova com verbo próprio.
- `pois` e `sendo que` invertem a ordem lógica da frase com facilidade. Use com parcimônia e confira se causa e consequência não trocaram de lugar.
- Não abra três parágrafos seguidos com a mesma palavra.
- Maiúscula depois de dois-pontos só em nome próprio.
- `ao invés de` significa `ao contrário de`. Para `em lugar de`, escreva `em vez de`.

## Fontes

- **Só fonte primária.** Texto compilado no Planalto, ato no sítio do órgão que o editou, política de privacidade na página da própria empresa, acórdão no sistema do tribunal.
- **Proibido:** Wikipédia, blog, post, material comercial de fornecedor sem metodologia publicada, notícia como prova de conteúdo normativo.
- **Toda afirmação normativa é conferida na fonte antes de entrar no texto.** O fato atual vence o roteiro.
- Citação em ABNT autor-data, com as referências ao final de cada capítulo.
- Conteúdo que envelhece rápido, como política de fornecedor e regulação em formação, entra sempre datado.

## O núcleo

`nucleo/` guarda o que não depende de setor: os modos de erro da IA, as quatro camadas de autorização, a matriz de risco, o comparativo de fornecedores, o glossário e o modelo de capacitação.

O acesso a esses arquivos é regido pela Regra 5. Leia sempre, escreva nunca.

Os arquivos do núcleo trazem, no cabeçalho, um aviso de generalização pendente quando ainda carregam vocabulário do livro de conselhos, de onde foram extraídos. Esse aviso é informação para quem adapta, não convite para editar a fonte.

## O que não transfere entre os livros

O alicerce jurídico muda conforme o setor. Essa é a parte que **nunca** deve ser copiada de um livro para outro:

| Família | Eixo jurídico |
|---|---|
| Conselhos, serviço público, economia mista | Direito administrativo: competência indelegável, dever de motivação, Lei 9.784/1999 |
| Advocacia, contabilidade | Sigilo profissional, Estatuto da Advocacia, códigos de ética das categorias |
| Consultórios de saúde | Sigilo médico, dado sensível de saúde, normas dos conselhos de saúde, prontuário |
| Empresa privada | LGPD, contrato, segredo de negócio, responsabilidade civil |

Cada família exige fundamentação construída do zero e verificada em fonte primária.
