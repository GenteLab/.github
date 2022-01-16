# Padrões de Branches e Commits

## Branches
Corpo de uma brach:
`<tipo>: <descrição>`

### Exemplos:
`feature/botao-de-editar-perfil`
`fix/tela-branca-do-login`
`perf/carregamento-de-conteudo`

### Tipos de Branches
- **docs**: apenas mudanças de documentação;
- **feature**: uma nova funcionalidade;
- **bugfix**: a correção de um bug;
- **perf**: mudança de código focada em melhorar performance;
- **refactor**: mudança de código que não adiciona uma funcionalidade e também não corrigi um bug;
- **style**: mudanças no código que não afetam seu significado (espaço em branco, formatação, ponto e vírgula, etc);
- **test**: adicionar ou corrigir testes.

#

## Commits
Corpo de um commit:
`<tipo> <descrição> - jiraCode` 

### Exemplos:
|   **Sintaxe**                                    | **Resultado**                                     |
|:-------------------------------------------------|:--------------------------------------------------|
| `:art: reestruturando codigo - OTT-923`          | :art: reestruturando codigo - OTT-923             |
| `:coffin: codigo zoom antigo - PROD-500`         | :coffin: codigo zoom antigo - PROD-500            |

 
  
### Tipos de Commits

| **Commit type**                                              | **Emoji**                                                 |
| :------------------------------------------------------------| :---------------------------------------------------------|
| Improve structure/format of the code                         | :art: `:art:`                                             |
| Improve performance                                          | :zap: `:zap:`                                             |
| Remove code or files                                         | :fire: `:fire:`                                           |
| Fix a bug                                                    | :bug: `:bug:`                                             |
| Critical hotfix                                              | :ambulance: `:ambulance:`                                 |
| Introduce new features                                       | :sparkles: `:sparkles:`                                   |
| Add or update documentation                                  | :memo: `:memo:`                                           |
| Deploy stuff                                                 | :rocket: `:rocket:`                                       |
| Add or update the UI and style files                         | :lipstick: `:lipstick:`                                   |
| Begin a project                                              | :tada: `:tada:`                                           |
| Add, update, or pass tests                                   | :white_check_mark: `:white_check_mark:`                   |
| Fix security issues                                          | :lock: `:lock:`                                           |
| Release/Version tags                                         | :bookmark: `:bookmark:`                                   |
| Fix compiler/linter warnings                                 | :rotating_light: `:rotating_light:`                       |
| Work in progress                                             | :construction: `:construction:`                           |
| Fix CI Build                                                 | :green_heart: `:green_heart:`                             |
| Downgrade dependencies                                       | :arrow_down: `:arrow_down:`                               |
| Upgrade dependencies                                         | :arrow_up: `:arrow_up:`                                   |
| Pin dependencies to specific versions                        | :pushpin: `:pushpin:`                                     |
| Add or update CI build system                                | :construction_worker: `:construction_worker:`             |
| Add or update analytics or track code                        | :chart_with_upwards_trend: `:chart_with_upwards_trend:`   |
| Refactor code                                                | :recycle: `:recycle:`                                     |
| Add a dependency                                             | :heavy_plus_sign: `:heavy_plus_sign:`                     |
| Remove a dependency                                          | :heavy_minus_sign: `:heavy_minus_sign:`                   |
| Add or update configuration files                            | :wrench: `:wrench:`                                       |
| Add or update development scripts                            | :hammer: `:hammer:`                                       |
| Internationalization and localization                        | :globe_with_meridians: `:globe_with_meridians:`           |
| Fix typos                                                    | :pencil2: `:pencil2:`                                     |
| Write bad code that needs to be improved                     | :poop: `:poop:`                                           |
| Revert changes                                               | :rewind: `:rewind:`                                       |
| Merge branches                                               | :twisted_rightwards_arrows: `:twisted_rightwards_arrows:` |
| Add or update compiled files or packages                     | :package: `:package:`                                     |
| Update code due to external API changes                      | :alien: `:alien:`                                         |
| Move or rename resources (e.g.: files, paths, routes)        | :truck: `:truck:`                                         |
| Add or update license                                        | :page_facing_up: `:page_facing_up:`                       |
| Introduce breaking changes                                   | :boom: `:boom:`                                           |
| Add or update assets                                         | :bento: `:bento:`                                         |
| Improve accessibility                                        | :wheelchair: `:wheelchair:`                               |
| Add or update comments in source code                        | :bulb: `:bulb:`                                           |
| Write code drunkenly                                         | :beers: `:beers:`                                         |
| Add or update text and literals                              | :speech_balloon: `:speech_balloon:`                       |
| Perform database related changes                             | :card_file_box: `:card_file_box:`                         |
| Add or update logs                                           | :loud_sound: `:loud_sound:`                               |
| Remove logs                                                  | :mute: `:mute:`                                           |
| Add or update contributor(s)                                 | :busts_in_silhouette: `:busts_in_silhouette:`             |
| Improve user experience/usability                            | :children_crossing: `:children_crossing:`                 |
| Make architectural changes                                   | :building_construction: `:building_construction:`         |
| Work on responsive design                                    | :iphone: `:iphone:`                                       |
| Mock things                                                  | :clown_face: `:clown_face:`                               |
| Add or update an easter egg                                  | :egg: `:egg:`                                             |
| Add or update a .gitignore file                              | :see_no_evil: `:see_no_evil:`                             |
| Add or update snapshots                                      | :camera_flash: `:camera_flash:`                           |
| Perform experiments                                          | :alembic: `:alembic:`                                     |
| Improve SEO                                                  | :mag: `:mag:`                                             |
| Add or update types                                          | :label: `:label:`                                         |
| Add or update seed files                                     | :seedling: `:seedling:`                                   |
| Add, update, or remove feature flags                         | :triangular_flag_on_post: `:triangular_flag_on_post:`     |
| Catch errors                                                 | :goal_net: `:goal_net:`                                   |
| Add or update animations and transitions                     | :dizzy: `:dizzy:`                                         |
| Deprecate code that needs to be cleaned up                   | :wastebasket: `:wastebasket:`                             |
| Work on code related to authorization, roles and permissions | :passport_control: `:passport_control:`                   |
| Simple fix for a non-critical issue                          | :adhesive_bandage: `:adhesive_bandage:`                   |
| Data exploration/inspection                                  | :monocle_face: `:monocle_face:`                           |
| Remove dead code                                             | :coffin: `:coffin:`                                       |
| Add a failing test                                           | :test_tube: `:test_tube:`                                 |
| Add or update business logic                                 | :necktie: `:necktie:`                                     |
| Add or update healthcheck                                    | :stethoscope: `:stethoscope:`                             |
| Infrastructure related changes                               | :bricks: `:bricks:`                                       |
| Improve developer experience                                 | :technologist: `:technologist:`                           |


## Úteis
- Extensão do vsCode "Gitmoji" criada por "Seaton Jiang", [Baixe aqui](https://marketplace.visualstudio.com/items?itemName=seatonjiang.gitmoji-vscode&ssr=false#overview) 
