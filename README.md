# Corona Vírus Charts CG
https://coronaviruschartscg.web.app/

Eu estava procurando alguma informação sobre o corona vírus em forma de gráficos aqui na minha cidade,  mas, não encontrei pelo menos de forma fácil. Então, em uma madrugada, resolvi criar uma plataforma pra gerar esse tipo de conteúdo com bases nas informações prestadas pela Prefeitura e Secretaria de Saúde de Campina Grande.  O intuito é informar a população da nossa cidade como está a curva de contágio. Acredito que fica mais claro sendo em  gráficos.

![gráficos](https://scontent.fjdo1-1.fna.fbcdn.net/v/t1.0-9/101059470_3644069102276784_1690408658514477056_o.jpg?_nc_cat=108&_nc_sid=730e14&_nc_eui2=AeFNnZb-QiocZwD4ti6H_5yKuH5dbFYXZEu4fl1sVhdkS7NDe-R8BrD_Msz1Py1S5GT4jNfiZVC80OjxqmwZw62N&_nc_ohc=re8BbZRMvqgAX9aLnpK&_nc_ht=scontent.fjdo1-1.fna&oh=24d702d33dea2dd136209d2a5b545cb1&oe=5EF6DBB5)

> Existe uma API que pode ser consultada e integrada a outros sistemas
> de campina grande:

https://coronaviruschartscg.firebaseio.com/covid19cg.json

Retorno GET:

    {
    "confirmados":1288,
    "data_atualizacao":"29/05/2020",
    "leitos_enfermaria":49,
    "leitos_uti":79,"obitos":29,
    "recuperados":627,
    "suspeitos":885
    }
