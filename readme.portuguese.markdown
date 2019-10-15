# Coleção de filmes em JSON

Uma coleção detalhada de filmes e atores fácil de usar no formato JSON e separado por ano de lançamento.

Forkado de https://github.com/jsonmc/jsonmc que agora está arquivado e é de somente leitura. Estou lentamente migrando as issues para este repositório, então seja paciente, por favor. Se desejar, dê uma estrela e ative as notificações!

## Contribuindo

Todo Outubro esse repositório recebe muita atenção. Se você deseja trabalhar em qualquer _issue_ com a tag Hacktoberfest, avise na _issue_ e garanto que irei mesclar os PRs de aqueles enviados primeiro.

Se você está procurando por _issues_ para contribuir, verifique aquelas que não contém a label "dibs". Confira os comentários e, se ninguém a reinvidicou, tenha certeza de deixar seu comentário para que seu PR seja o primeiro a ser mesclado.

Tenha certeza de sempre referenciar seus _pull requests_ com a respectiva _issue_ adicionando `Fixes #100` em sua mensagem de _commit_, título ou descrição do PR. Um template foi fornecido para te ajudar.

### Um filme possui as seguintes informações


| Atributo do filme       | Detalhes                                                                 |
| ----------------------- | --------------------------------------------------------------------     |
| Data de lançamento      | Data no formato YYYY-MM-DD                                               |
| Categorias              | Ação, aventura, comédia, animação, família, fantasia, sci-fi, esporte    |
| Diretor                 | Diretores do filme                                                       |
| Escritores              | Escritores da história e roteiro                                         |
| Atores                  | Elenco principal                                                         |
| Ano                     | Ano de lançamento                                                        |
| Duração                 | Duração em minutos                                                       |
| Roteiro                 | Breve descrição do filme                                                 |


#### Exemplo de arquivo de filme

```json
{
  "name": "Jurassic Park",
  "year": 1993,
  "runtime": 127,
  "categories": [
    "adventure",
    "thriller",
    "sci-fi"
  ],
  "release-date": "1993-06-11",
  "director": "Steven Spielberg",
  "writer": [
    "Michael Crichton",
    "David Koepp"
  ],
  "actors": [
    "Sam Neill",
    "Laura Dern",
    "Jeff Goldblum"
  ],
  "storyline": "Huge advancements in scientific technology have enabled a mogul ... critical security systems are shut down and it now becomes a race for survival with dinosaurs roaming freely over the island."
}
```
## Contribuindo

Confira o [Guia de contribuição](contributing.markdown) para maiores instruções.
