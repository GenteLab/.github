# Padrões de Branches e Commits

## Branches
Corpo de uma brach
`<tipo>: <descrição>`

### Tipos de Branches
- **docs**: apenas mudanças de documentação;
- **feature**: uma nova funcionalidade;
- **fix**: a correção de um bug;
- **perf**: mudança de código focada em melhorar performance;
- **refactor**: mudança de código que não adiciona uma funcionalidade e também não corrigi um bug;
- **style**: mudanças no código que não afetam seu significado (espaço em branco, formatação, ponto e vírgula, etc);
- **test**: adicionar ou corrigir testes.

### Exemplos:
`feature/botao-de-editar-perfil`
`fix/tela-branca-do-login`
`perf/carregamento-de-conteudo`

## Commits
Corpo de um commit
`<tipo>(opcional)- <descrição> - jiraCode` 
`! com o exclamação, significa alteração importante`
  
### Tipos de Commits
|   **Commit type**          | **Emoji**                                     |
|:---------------------------|:----------------------------------------------|
| Initial commit             | :tada: `:tada:`                               |
| New feature                | :sparkles: `:sparkles:`                       |
| Bugfix                     | :bug: `:bug:`                                 |
| Metadata                   | :card_index: `:card_index:`                   |
| Documentation              | :books: `:books:`                             |
| Documenting source code    | :bulb: `:bulb:`                               |
| Performance                | :racehorse: `:racehorse:`                     |
| Cosmetic                   | :lipstick: `:lipstick:`                       |
| Tests                      | :rotating_light: `:rotating_light:`           |
| Adding a test              | :white_check_mark: `:white_check_mark:`       |
| Make a test pass           | :heavy_check_mark: `:heavy_check_mark:`       |
| General update             | :zap: `:zap:`                                 |
| Improve format/structure   | :art: `:art:`                                 |
| Refactor code              | :hammer: `:hammer:`                           |
| Removing code/files        | :fire: `:fire:`                               |
| Continuous Integration     | :green_heart: `:green_heart:`                 |
| Security                   | :lock: `:lock:`                               |
| Upgrading dependencies     | :arrow_up: `:arrow_up:`                       |
| Downgrading dependencies   | :arrow_down: `:arrow_down:`                   |
| Translation                | :alien: `:alien:`                             |
| Text                       | :pencil: `:pencil:`                           |
| Critical hotfix            | :ambulance: `:ambulance:`                     |
| Deploying stuff            | :rocket: `:rocket:`                           |
| Work in progress           | :construction:  `:construction:`              |
| Adding CI build system     | :construction_worker: `:construction_worker:` |
| Analytics or tracking code | :chart_with_upwards_trend: `:chart_with_upwards_trend:` |
| Removing a dependency      | :heavy_minus_sign: `:heavy_minus_sign:`       |
| Adding a dependency        | :heavy_plus_sign: `:heavy_plus_sign:`         |
| Configuration files        | :wrench: `:wrench:`                           |
| Package.json in JS         | :package: `:package:`                         |
| Merging branches           | :twisted_rightwards_arrows: `:twisted_rightwards_arrows:` |
| Bad code / need improv.    | :hankey: `:hankey:`                           |
| Reverting changes          | :rewind: `:rewind:`                           |
| Breaking changes           | :boom: `:boom:`                               |
| Code review changes        | :ok_hand: `:ok_hand:`                         |
| Accessibility              | :wheelchair: `:wheelchair:`                   |
| Move/rename repository     | :truck: `:truck:`                             |


### Exemplos:
`:tada: - iniciando projeto - OTT-923`
`:bug:(api!) - correcao de tela em loop - PROD-500` 
