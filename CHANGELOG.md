# Changelog
## 1.0.1 (2020-06-28)
### Trivial
  - Updated with the latest public django app template. [Wes Kendall, 33f6de1]

## 1.0.0 (2020-06-27)
### Api-Break
  - Initial release of django-pgconnection. [Wes Kendall, f35c15c]

    The initial release of django-pgconnection includes functionality for:
    1. Routing database traffic. ``pgconnection.route`` can route any database
       calls from Django dynamically to a different database.
    2. Hooking into SQL execution. ``pgconnection.pre_execute_hook`` allows one
       to hook into SQL generation and dynamically modify SQL before it is
       executed.

