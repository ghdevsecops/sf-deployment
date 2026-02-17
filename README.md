# alias commands
sf alias set dev=pckging@gmail.com.dev qa=pckging@gmail.com.qa
sf alias unset dev qa
sf alias unset --all
sf alias list

# flags-dir
sf org login web --flags-dir ./flag-values -o dev
flag-values
    username
    instance-url
