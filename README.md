# TesteDjango2022
    Com o objetivo da volta do uso do Python no cotidiano 

# 🛠️ O que foi feito:

- `Rotas`: Criação de duas rotas 

        path('hello/', views.hello),
        path('ola/<nome>/', views.ola),
        
![gitphoto01](https://user-images.githubusercontent.com/88732777/190928727-6fa5a200-16f7-4155-b8e0-f3c5541ed83f.PNG)

- `Requests`: Criação de uma request para a view

        def ola(request,nome):
        return HttpResponse('Hello {}'.format(nome))


![gitphoto](https://user-images.githubusercontent.com/88732777/190928533-f59cb04e-0970-48ee-b41a-3fe71bcf92b0.PNG)
