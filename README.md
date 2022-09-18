# TesteDjango2022
    Com o objetivo da volta do uso do Python no cotidiano 

# 🛠️ O que foi feito:

- `Rotas`: Criação de duas rotas 

        path('hello/', views.hello),
        path('ola/<nome>/', views.ola),

- `Requests`: Criação de uma request para a view

        def ola(request,nome):
        return HttpResponse('Hello {}'.format(nome))


<img scr="https://github.com/MazeDan/Teste_Django_2022/issues/1#issue-1377178483" >
