# Репликация поисков из систематических обзоров

## Пример систематического обзора с реплицирующимися поисками

```
[1.10., 10:35] Anonymous: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6343333/
😍😍😍 Воспроизводящиеся поиски! Они существуют!!!
[1.10., 10:38] Anonymous: haemorrhage [Title/Abstract] not hemorrhage [Title/Abstract]
32,302 items
Никогда не забывайте про вариации написания, милые мои.
[1.10., 10:40] Anonymous: То же:
multitrauma [Title/Abstract] not polytrauma [Title/Abstract]
262 items
[1.10., 16:32] Anonymous: Кстати, еще по поводу этого. Смотрите, как это работает. У меня возникли обоснованные сомнения в том, что поисковый запрос был всеобъемлющим, поскольку он не включал пресловутые вариации написания `haemorrhage` и `multitrauma`. Но авторы привели свой запрос, а значит нет необходимости сомневаться — можно взять и проверить! И тогда я написал запрос:
https://www.ncbi.nlm.nih.gov/m/pubmed/?term=(informed%20consent%20[Title/Abstract]%20AND%20(haemorrhage*[tiab]%20or%20multitrauma[tiab]))%20not%20(((((((((((((((((informed%20consent%20[Title/Abstract])%20AND%20trauma%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20traumatic%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20polytrauma%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20injury%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20injuries%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20wound%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20wounds%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20laceration%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20lacerations%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20fracture%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20fractures%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20rupture%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20ruptures%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20hemorrhage%20[Title/Abstract]))%20OR%20((informed%20consent%20[Title/Abstract])%20AND%20hemorrhages%20[Title/Abstract]))
Он выдает все те записи, которые содержат `haemorrhage` и `multitrauma`, но не выдаются по авторскому запросу. Таких оказалось всего 48. Ну и что, я бегло просмотрел их все за пару минут, выяснил, что релевантных записей среди них не содержится — вот и все, сомнения мои проверены. Запросы авторские воспроизводятся, претензий к их содержанию у меня не осталось, значит поисковая стратегия прошла испытание, и я стану ей доверять.
```
