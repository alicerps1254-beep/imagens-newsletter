# imagens-newsletter

Arquivos da newsletter **DETRAN.RJ Notícias**: o modelo das edições e as imagens usadas no e-mail.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `modelo-base.html` | Matriz de todas as edições. Não edite: faça uma cópia. |
| `newsletter.html` | Edição 1 (24 de agosto de 2026), já preenchida. Serve de exemplo. |
| `logogovrj.png`, `detrannoticias.png` | Logos do cabeçalho. O e-mail carrega estas imagens direto da branch `main`. |
| Demais `.png` | Material de referência da identidade visual. |

## Como montar uma edição nova

1. Copie `modelo-base.html` e renomeie (ex.: `edicao-02.html`).
2. Abra a cópia num editor de texto e procure por `[[`. Cada `[[...]]` é um campo a preencher. O texto entre os colchetes diz o que vai ali; apague os colchetes junto.
3. O modelo traz duas matérias: a **completa** (com faixa de números em destaque) e a **simples** (sem faixa, com dois parágrafos). Para mais matérias, copie o bloco entre `INÍCIO MATÉRIA` e `FIM MATÉRIA` e siga o passo a passo do comentário no topo do arquivo.
4. Blocos marcados `[OPCIONAL]` podem ser apagados inteiros.
5. Antes de enviar, confira o checklist no topo do arquivo e mande um e-mail de teste para você (celular e Outlook).

O comentário no início do `modelo-base.html` também traz a paleta de cores, os tamanhos de letra e os espaçamentos da identidade visual.
