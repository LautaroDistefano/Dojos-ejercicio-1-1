# Ejemplo Documentación Dojos
![Tinkercad](./img/ArduinoTinkercad.jpg)


## Integrantes 
- Lautaro Torres Distefano
- Adrian Barrientos
- Sol Rubinetti
- Trinidad Faccini
- Yamila sueldo


## Proyecto: Semaforo con señalizacion para no videntes.
![Tinkercad](./img/Ejercicio 1-1 semafoto.png)


## Descripción
Semaforo con señalizacion para no videntes que a travez de un Piezo(Buzzer) genera ruido.

## Función principal
Esta funcion se encarga de encender y apagar el buzzer 10 veces.
~~~ C (lenguaje en el que esta escrito)
int contador = 0;
void avisarLedRojo(int BUZZER, int tiempo)
{
  int contador = 0;
  while (contador < 10)
  {
    sonarBuzzer(250,250);
    Serial.println("Suena buzzer");
    delay(tiempo);
    noTone(BUZZ);
    Serial.println("Se apaga el buzzer");
    delay(tiempo);
    contador += 1;
  }
}
~~~

## :robot: Link al proyecto
- [proyecto](https://www.tinkercad.com/things/aOYiibnDjWu)
## :tv: Link al video del proceso
- [video](https://www.youtube.com/watch?v=VyGjE8kx-O0)

---
### Fuentes
- [Consejos para documentar](https://www.sohamkamani.com/how-to-write-good-documentation/#architecture-documentation).

- [Lenguaje Markdown](https://markdown.es/sintaxis-markdown/#linkauto).

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

- [Tutorial](https://www.youtube.com/watch?v=oxaH9CFpeEE).

- [Emojis](https://gist.github.com/rxaviers/7360908).

---






