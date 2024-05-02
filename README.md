El operador and evalúa si el valor a la izquierda y el de la derecha son True, y en el caso de ser cierto, devuelve True. Si uno de los dos valores es False, el resultado será False. Es realmente un operador muy lógico e intuitivo que incluso usamos en la vida real. Si hace sol y es fin de semana, iré a la playa. Si ambas condiciones se cumplen, es decir que la variable haceSol=True y la variable finDeSemana=True, iré a la playa, o visto de otra forma irALaPlaya=(haceSol and finDeSemana).
```python
print(True and True)   # True
print(True and False)  # False
print(False and True)  # False
print(False and False) # False
```