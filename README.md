A funcionalidade converterVoz usa a biblioteca pyttsx3 do Python 3.

import pyttsx3

def converterVoz(texto):
    engine = pyttsx3.init()
    engine.say(texto)
    engine.runAndWait()

converterVoz("""
Informe o texto aqui e execute a aplicação.
""")
