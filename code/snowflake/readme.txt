Coding standards and naming convention.

1.Versioned Script Naming

Prefix: The letter 'V' for versioned change
Version: A unique version number with dots or underscores separating as many number parts as you like
Separator: __ (two underscores)
Description: An arbitrary description with words separated by underscores or spaces (can not include two underscores)
Suffix: .sql or .sql.jinja


2.Repeatable Script Naming
e.g:

R__sp_add_sales.sql
R__fn_get_timezone.sql
R__fn_sort_ascii.sql


3.Always Script Naming
e.g.

A__add_user.sql
A__assign_roles.sql
