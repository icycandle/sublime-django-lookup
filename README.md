# sublime-django-lookup

## Trigger Table

These snippet's scope is `meta.function-call.arguments.python`, so they will only trigger in function call's parenthesis `()`, instead of mess up with other python meta method snippets like `__init__`.

| Trigger | Lookup |
|---|---|
| __c   | `field`__contains=`'string'`,                  |
| __d   | `field`__day=`1-31`,                           |
| __dt  | `field`__date=`datetime.today()`               |
| __e   | `field`__exact=`None`,                         |
| __ew  | `field`__endswith=`'string'`,                  |
| __g   | `field`__gt=`0`,                               |
| __ge  | `field`__gte=`0`,                              |
| __h   | `field`__hour=`0-23`,                          |
| __i   | `field`__in=`[]`,                              |
| __ic  | `field`__icontains=`'string'`,                 |
| __ie  | `field`__iexact=`None`,                        |
| __iew | `field`__iendswith=`'string'`,                 |
| __in  | `field`__isnull=`True`,                        |
| __ir  | `field`__iregex=`r'^reg-exp'`,                 |
| __iss | `field`__istartswith=`'string'`,               |
| __l   | `field`__lt=`0`,                               |
| __le  | `field`__lte=`0`,                              |
| __min | `field`__minute=`0-59`,                        |
| __mon | `field`__month=`1-12`,                         |
| __r   | `field`__range=(`start_value`, `end_value`),   |
| __re  | `field`__regex=`r'^reg-exp'`,                  |
| __s   | `field`__search=`'string'`,                    |
| __sec | `field`__second=`0-59`,                        |
| __ss  | `field`__startswith=`'string'`,                |
| __w   | `field`__week_day=`Sun_as_1_Sat_as_7`,         |
| __y   | `field`__year=`2020`,                          |
