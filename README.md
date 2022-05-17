# Revisão Python

Olá, aqui estão algumas das minhas revisões sobre POO, listas, tuplas, dicionários e sets em Python. Sempre é bom relembrar!

# Classes

As classes oferecem uma forma de organizar dados e funcionalidades do seu programa. Criar uma nova classe cria um novo tipo de objeto, permitindo que novas instâncias sejam criadas. Cada instância de classe pode ter atributos anexados a ela. Instâncias da classe também podem ter métodos para modificar seu estado.

Veja um simples exemplo de classe:

```python
class MyClass:
    """A simple class example"""

    i = 1234 # atributo de classe
    # o atributo "i" com seu valor estará presente
    # em todos as instâncias da classe

    def message(): # método da classe
        print('Hello world')
```