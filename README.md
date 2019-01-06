# Label Groups

Здесь указаны стандартные типы лейблов.

Group | Label |
--- | ---
Priority | ![pr: critical](https://labl.es/svg?text=pr:%20critical&bgcolor=9F0000) ![pr: high](https://labl.es/svg?text=pr:%20high&bgcolor=E30303) ![pr: medium](https://labl.es/svg?text=pr:%20medium&bgcolor=ff6666) ![pr: low](https://labl.es/svg?text=pr:%20low&bgcolor=ffb3b3) 
Part of app | ![app: alarm call](https://labl.es/svg?text=app:%20alarm%20call&bgcolor=ffa64d) ![app: average call](https://labl.es/svg?text=app:%20average%20call&bgcolor=ffa64d) ![app: feed](https://labl.es/svg?text=app:%20feed&bgcolor=ffa64d) ![app: user](https://labl.es/svg?text=app:%20user&bgcolor=ffa64d)
Type | ![tp: service](https://labl.es/svg?text=tp:%20service&bgcolor=a8d49a) ![tp: activity](https://labl.es/svg?text=tp:%20activity&bgcolor=a8d49a) ![tp: controller](https://labl.es/svg?text=tp:%20controller&bgcolor=a8d49a)
Incident | ![inc: bug](https://labl.es/svg?text=inc:%20bug&bgcolor=fba4e4) ![inc: security](https://labl.es/svg?text=inc:%20security&bgcolor=fba4e4)
Documentation | ![to doc](https://labl.es/svg?text=to%20doc&bgcolor=ffdd00)

# Правила присвоения лейблов

1. Priority. Приоритет выставляется в случае наличия срочных задач, которые должны быть исполнены ранее остальных. Если таких задач нет, то лейбл с приоритетом не выставляется.
1. Part of app. Данный лейбл указывает, к какой части приложения относится то или иное issue.
1. Type. Данный лейбл указывает тип элемента системы, над которым велась работа в issue.
1. Incident. Указывает на то, что произошел баг или сбой в системе безопасности.
1. Documentation. Данный лебл выставляется в том случае, если изменения созданного issue требуется зафиксировать в документации.

# Issue с лейблом "to doc"

1. Если issue присваивается лейбл "to doc", то должно быть автоматически создано issue на внесение изменений в документацию.
1. В данное issue также должен быть перенесен лейбл из категории "Part of app".
