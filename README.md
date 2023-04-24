# Ejemplo Documentación Dojos
![Tinkercad](./img/ArduinoTinkercad.jpg)


## Integrantes 
- Lautaro Torres Distefano
- Adrian Barrientos
- Sol Rubinetti
- Trinidad Faccini
- Yamila sueldo


## Proyecto: Semaforo con señalizacion para no videntes.
![Ejercicio 1-1 semafoto](https://user-images.githubusercontent.com/122444609/234120081-8709dec8-8634-48b8-ae7e-1bcf12ffd0c4.png)


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
## 🤖 Link al proyecto
- [Tinkercard-Sol Rubinetti](https://www.tinkercad.com/things/iZNwefUZfGa-dojo-1-grupo-f-clase-5/editel?sharecode=4DJUVY-ezPfkTXRP7us0aNPnXKNrvgEcs_NTCFw-zh4)
- [Tinkercard-Yamila Sueldo](https://www.tinkercad.com/things/ekHG25jeY0k-dojo-numero-uno/editel?sharecode=_ZBsYcqE1y3GENhjB3fzVXFeKbKeGMpGsUccB4qW-Ok)
- [Tinkercard-Adrian Barrientos](https://www.tinkercad.com/things/8mgCsJsUrRK-bodacious-borwo/editel?sharecode=VCCzrcbr8gq2P9JAjRSaL-b77EM1lVzc9hE01hZxCX8)
- [Tinkercard-Lautaro Torres](https://www.tinkercad.com/things/fSOhHiGeVdJ-ejercicio-dojo-1-1/editel?sharecode=9IKDJYqicsguvunn1_dn7oklyXOUMo9TCehS7j1dNF8)
- [Tinkercard-Trini](https://www.tinkercad.com/things/3WUXu8RRyCe-dojo-uno-grupo-f-entrega-uno/editel?sharecode=auH-Hu3eBpDSPj273IRXl5Y4IbzwZkOZd1af6DUXJGE)
---






