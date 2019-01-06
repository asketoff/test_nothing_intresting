# Label Groups

Здесь указаны стандартные типы лейблов.

Group | Label |
--- | ---
Priority | ![prt: critical](https://labl.es/svg?text=prt:%20critical&bgcolor=9F0000) ![prt: high](https://labl.es/svg?text=prt:%20high&bgcolor=E30303) ![prt: medium](https://labl.es/svg?text=prt:%20medium&bgcolor=ff6666) ![prt: low](https://labl.es/svg?text=prt:%20low&bgcolor=ffb3b3) 
Part of app | ![app: AlarmCall](https://labl.es/svg?text=app:%20AlarmCall&bgcolor=ffa64d) ![app: AverageCall](https://labl.es/svg?text=app:%20AverageCall&bgcolor=ffa64d) ![app: Feed](https://labl.es/svg?text=app:%20Feed&bgcolor=ffa64d) ![app: User](https://labl.es/svg?text=app:%20User&bgcolor=ffa64d)
Architecture | ![arc: Application](https://labl.es/svg?text=arc:%20Application&bgcolor=a8d49a) ![arc: Dependency](https://labl.es/svg?text=arc:%20Dependency&bgcolor=a8d49a) ![arc: Service/BroadcastReceiver](https://labl.es/svg?text=arc:%20Service/BroadcastReceiver&bgcolor=a8d49a) ![arc: Activity](https://labl.es/svg?text=arc:%20Activity&bgcolor=a8d49a) ![arc: ActivityController](https://labl.es/svg?text=arc:%20ActivityController&bgcolor=a8d49a) ![arc: Controller](https://labl.es/svg?text=arc:%20Controller&bgcolor=a8d49a) ![arc: AnotherController](https://labl.es/svg?text=arc:%20AnotherController&bgcolor=a8d49a) ![arc: Fragment](https://labl.es/svg?text=arc:%20Fragment&bgcolor=a8d49a) ![arc: FragmentController](https://labl.es/svg?text=arc:%20FragmentController&bgcolor=a8d49a) ![arc: FunctionalController](https://labl.es/svg?text=arc:%20FunctionalController&bgcolor=a8d49a)
Incident | ![inc: Bug](https://labl.es/svg?text=inc:%20Bug&bgcolor=fba4e4) ![inc: Security](https://labl.es/svg?text=inc:%20Security&bgcolor=fba4e4)
Documentation | ![to doc](https://labl.es/svg?text=to%20doc&bgcolor=ffdd00)

# Правила присвоения лейблов

1. Priority. Приоритет выставляется в случае наличия срочных задач, которые должны быть исполнены ранее остальных. Если таких задач нет, то лейбл с приоритетом не выставляется.
1. Part of app. Данный лейбл указывает, к какой части приложения относится то или иное issue.
1. Architecture. Данный лейбл указывает элемент архитектуры приложения, над которым велась работа в issue.
1. Incident. Указывает на то, что произошел баг или сбой в системе безопасности.
1. Documentation. Данный лебл выставляется в том случае, если изменения созданного issue требуется зафиксировать в документации.

# Issue с лейблом "to doc"

1. Если issue присваивается лейбл "to doc", то должно быть автоматически создано issue на внесение изменений в документацию.
1. В данное issue также должен быть перенесен лейбл из категории "Part of app".
