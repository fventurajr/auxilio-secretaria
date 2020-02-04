# auxilio-secretaria
# Controlar as viagens de trabalho

# Classes de negócios:
## Viajante
* nome
* empresa
## Órgão
* empresa
* sigla
* nome
* centro de custo
## Viagem
* tipo [ ida | volta ]
* cia aérea [ Azul | Gol | Latam | outra ]
* número do vôo
* cidade origem
* aeroporto de partida [ GIG | SDU | outro ]
* data / hora do voo
* aeroporto de chegada [ outro | GIG | SDU ]
* cidade destino
* status de viagem
* secretária responsável
* nome do hotel
* dias de hospedagem

# Métodos
* Cadastrar Viajante
* Cadastrar Órgão
* Cadastrar Viagem
* Atualizar Status de Viagem

# Planejamento

## Atividades
- [ ] Modelar as entidades              ( model   )
- [ ] Definir as regras de negócio      ( control )
- [ ] Desenhar as entradas de dados     ( view    )
- [ ] Desenvolver validação de entrada  ( view    )
- [ ] Escolha do modelo de persistência ( entity  )

# Background

## Desenvolvimento

| campo           | valor                |
|-----------------|----------------------|
| abordagem       | orientação a objeto  |
| front-end       | indefinido           |
| back-end        | Java 8.0             |
| banco de dados  | indefinido           |
| cliente         | Grace Souza          |
| desenvolvedores | Fernando Ventura Jr. |
|                 | Aline Afonso Silva   |

Diagrama de classes:
![]https://www.draw.io/#G17XyxVXx1-WDD54NWSkH3JS_-IfrYE4sI



