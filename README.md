# Heroku
Principais comandos CLI do Heroku.

## Logar no heroku

`heroku login`

## Rodando local

```
heroku local
```

## Criar uma aplicação

```
heroku create
heroku apps:create <app_name>
```

## Listar aplicações

```
heroku apps
```

## Logs

```
heroku logs --app=app-with-express
heroku logs --app=app-with-express -t # acompanhar logs
```

## Linkar repositório local

```
git remote add <remote_alias> <remote_url>
```

## Fazer deploy

```
git push <remote_alias> master
git push <remote_alias> <local_branch>:master (sempre a branch remota é a master)
```

## Configurar variável de ambiente

```
heroku config:set <KEY>=<VALUE> (--app <app_name>) (--remote=<alias>)
```
