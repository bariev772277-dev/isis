# ISIS# Лабораторная работа № 1. Работа с Git и GitHub

# 

# \## Как клонировать репозиторий по SSH

# 

# 1\. Создайте SSH-ключ и добавьте его публичную часть в настройки аккаунта GitHub.

# 2\. На странице репозитория нажмите \*\*Code → SSH\*\* и скопируйте адрес.

# 3\. Откройте Git Bash в папке, где хотите сохранить локальную копию, и выполните:

# 

# git clone git@github.com:bariev772277-dev/ISIS.git

# &#x20;  

# 

# &#x20;  Если используется отдельный учебный ключ `ISIS`, укажите его при клонировании:

# 

# &#x20;  git clone -c core.sshCommand='ssh -F /dev/null -o IdentitiesOnly=yes -i \~/.ssh/github-labs/ISIS/ISIS' git@github.com:bariev772277-dev/ISIS.git

# &#x20;  

# 

# 4\. Перейдите в папку репозитория и проверьте адрес `origin`:

# 

# &#x20;  cd ISIS

# &#x20;  git remote -v

# &#x20;  

