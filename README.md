# sublime-django-lookup

![demo.gif](https://raw.github.com/icycandle/sublime-django-lookup/master/demo.gif)

## Trigger Table

These snippet's scope is `meta.function-call.arguments.python`, so they will only trigger in function call's parenthesis `()`, instead of mess up with other python meta method snippets like `__init__`.

| Trigger | Lookup |
|---|---|
| __in  | `field`__isnull=`True`,                        |
| __g   | `field`__gt=`0`,                               |
| __ge  | `field`__gte=`0`,                              |
| __l   | `field`__lt=`0`,                               |
| __le  | `field`__lte=`0`,                              |
| __i   | `field`__in=`[]`,                              |
| __r   | `field`__range=(`start_value`, `end_value`),   |
| __e   | `field`__exact=`None`,                         |
| __ie  | `field`__iexact=`None`,                        |
| __s   | `field`__search=`'string'`,                    |
| __c   | `field`__contains=`'string'`,                  |
| __ic  | `field`__icontains=`'string'`,                 |
| __iew | `field`__iendswith=`'string'`,                 |
| __ew  | `field`__endswith=`'string'`,                  |
| __ss  | `field`__startswith=`'string'`,                |
| __iss | `field`__istartswith=`'string'`,               |
| __re  | `field`__regex=`r'^reg-exp'`,                  |
| __ir  | `field`__iregex=`r'^reg-exp'`,                 |
| __y   | `field`__year=`2020`,                          |
| __mon | `field`__month=`1-12`,                         |
| __d   | `field`__day=`1-31`,                           |
| __h   | `field`__hour=`0-23`,                          |
| __min | `field`__minute=`0-59`,                        |
| __sec | `field`__second=`0-59`,                        |
| __w   | `field`__week_day=`Sun_as_1_Sat_as_7`,         |
| __dt  | `field`__date=`datetime.today()`               |
