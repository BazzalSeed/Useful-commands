# Useful Commands

### [Review Board](https://reviewboard.locately.com/)

1. SVN change list
    ```
     svn changelist admin-dashboard
    ```

2. RBT commands
    ```
    rbt diff > brandgeek_maintenance_mode.diff

    rbt post --diff-filename=my-named-mod.diff --open

    rbt post --diff-filename=brandgeek_admin_monitoring_sel.diff --review-request-id=1328
    https://reviewboard.locately.com/
    ```

### Tunneling/DataBase

1. check process running regarding ssh
    ```
     ps -ef | grep s
    ```
2.  connect to remote postgre database
    ```
    psql -U postgres -h localhost -p 5439 siphon
    ```
    *  -U as user
    *  -h as host name
    * -p as port
    * last word as database name
    * [complete list of flags](https://www.postgresql.org/docs/devel/static/app-psql.html)

3. under ~/.ssh/config for all configured hosts names