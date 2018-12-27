
---

* Taskta debug etmek istediğiniz bölüme  breakpointinizi `import ipdb; ipdb.set_trace()`  komutu ile ekleyin.
* `python manage.py shell` komutu ile Django shell penceresini açın ve çağırmak istediğiniz metodun parametrelerini {} içinde girin.
 
```python
>>> from task.metodu.konumu import task_metodu
>>> task_metodu({arg1, arg2, arg3})
```

afiyet olsun.
