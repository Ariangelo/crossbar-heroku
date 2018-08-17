# Crossbar hello:python no Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

This demo application shows it's possible to run the Crossbar router through Heroku.

See http://crossbar.io/docs/Setup-on-Heroku/ for more details.
Be careful, Free apps can only be active up to 18 hours of a 24 hour period.

Find out more: https://devcenter.heroku.com/articles/dyno-sleeping

Este aplicativo de demonstração mostra que é possível executar o roteador Crossbar utilizando o Heroku.

Veja http://crossbar.io/docs/Setup-on-Heroku/ para mais detalhes.
Lembre-se que os aplicativos gratuitos só podem estar ativos 18 horas por dia.

Saiba mais: https://devcenter.heroku.com/articles/dyno-sleeping

```
heroku ps:scale web=0
heroku logs --tail
```
