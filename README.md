# test-task-form
ZADANIE. 

Zbudowanie formularza, z wykorzystaniem Angulara Reactive Forms oraz Angular Material (Angular minimum w wersji 12). Formularz ma się składać z 3 pól podstawowych, oraz umożliwiać dodanie pól dodatkowych. 

 

Formularz ma składać się z następujących pól podstawowych: 

-imię (walidator na min 3 znaki, pole wymagane) 
-nazwisko (walidator na min 3 znaki, pole wymagane) 
-hasło (walidator – duża litera, znak specjalny, min. 7 znaków, pole wymagane) 

Przycisk ”Dodaj” w którego wbudowane jest menu z opcjami: 
telefon 
e-mail 
twoje zainteresowania 

Po kliknięciu w poszczególną opcje menu, do formularza ma zostać dodane odpowiednie pole, z odpowiednimi walidatorami: 

telefon – przyjmuje tylko liczby z przedziału 0-9 oraz znak „+” (plus), pole nie wymagane 

e-mail - walidator poprawności adresu e-mail, pole nie wymagane 

twoje zainteresowania – pole nie wymagane, max 100znaków 

Dodatkowo przy polach telefon oraz e-mail mają się znajdować przełączniki, przy użyciu których można włączać lub wyłączać walidator wymagane/niewymagane dla tych pól. 

Przy polu hasło należy umieścić przycisk, który umożliwi zmianę typu tego pola z password na text i odwrotnie. 
