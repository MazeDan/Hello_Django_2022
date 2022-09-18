# TesteDjango2022
    Com o objetivo da volta do uso do Python no cotidiano 

# 🛠️ O que foi feito:

- `Rotas`: Criação de duas rotas 

        path('hello/', views.hello),
        path('ola/<nome>/', views.ola),

- `Requests`: Criação de uma request para a view

        def ola(request,nome):
        return HttpResponse('Hello {}'.format(nome))


<img scr="https://user-images.githubusercontent.com/88732777/190928117-a0f98f5f-a066-49d6-9404-cc3e5dac9a47.PNG" >
