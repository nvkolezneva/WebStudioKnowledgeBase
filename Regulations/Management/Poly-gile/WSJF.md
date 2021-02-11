# Приоритизации бэклога
Необходимо прибегать к математическим методам при расстановке приоритетов. Конечно, всегда есть параметры, упрощающие этот процесс — такие как дедлайны или зависимости между элементами бэклога. Но все предположения о ценности или сложности того или иного элемента достаточно приблизительны.

Специальные инструменты как раз помогают внести в процесс приоритизации конкретику и объяснить иерархию элементов в понятных числах. В студии применяется вот такой инструмент — система оценки **Weighted Shortest Job First**. Как видно из названия, чем выше коэффициент WSJF, тем приоритетнее задача.
1. ![](https://onagile.ru/resources/post-images/6eb832bc-8f0b-4964-85d4-b85bbc470574.jpg)

Где:

***Ценность для клиента/бизнеса*** (User-Business Value) — показывает, насколько выполнение конкретной задачи будет полезно клиентам и бизнесу.

***Фактор времени*** (Time Criticality) — насколько критично выполнить задачу прямо сейчас? Чтобы опередить конкурентов, успеть к установленному сроку или открыть возможность для работы над связанными задачами. 

***Снижение рисков или реализация возможностей*** (Risk Reduction or Opportunity Enablement) — фактор, отражающий, как выполнение конкретной задачи снизит риски или какие возможности откроет.

***Продолжительность, размер работы*** (Job Duration, Job Size) — в условиях ограниченности ресурсов, и особенно на этапе формирования команды и начала работы, удобно оценивать размер задачи в относительных пунктах (Story points).

Это условные баллы, показывающие соотношение масштабов задач. Так, если реализацию инициативы А мы оценим в 1 пункт, а Б — в 3 пункта, то, независимо от реальной системы единиц, первая задача потребует в 3 раза меньше ресурсов, чем вторая. В качестве шкалы баллов используется последовательность Фибоначчи, т.е. каждая следующая величина равна сумме двух предыдущих: 1, 2, 3, 5, 8...

 2. Далее создаем сводную таблицу и оцениваем каждый параметр для всех задач, присваивая значения в пунктах.
 ![](https://onagile.ru/resources/post-images/cf4c18d4-930b-4796-8eb8-6c0912a06fe8.jpg)
