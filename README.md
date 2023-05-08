# DOJO NUMERO UNO - GRUPO F

![Tinkercard](https://github.com/trinifaccini/dojo-uno/blob/main/img/DOJO-UNO-GRUPO-F-ENTREGA-UNO.png)

## Integrantes 
- Sol Rubinetti
- Yamila Sueldo
- Adrian Barrientos
- Lautaro Torres
- Trinidad Faccini

## Consigna
El gobierno de la ciudad quiere actualizar los semáforos que tiene instalados. La empresa  “UTNFRA Robotics” ganó la licitación y ahora les toca a los desarrolladores de la empresa generar  un proyecto low cost que cumpla con las especificaciones que el gobierno de la ciudad nos  impone, a saber las especificaciones son las siguientes. 

### Segunda entrega: 
8. Durante el amarillo: Tiene que sonar 1 vez por segundo en un tono SUAVE. 
9. Al cambiar de verde a amarillo debe titilar 3 veces el verde antes de pasar al amarillo
10. Al cambiar de amarillo a rojo se debe titilar 3 veces el amarillo
11. Al cambiar de rojo a Amarillo se debe titilar 3 veces el rojo
12. Al cambiar de amarillo a verde se debe titilar 3 veces el amarillo.

## Descripción

Creamos un semáforo con señalización para no videntes. 

## Finalidad del proyecto
Demostrar los conocimientos aprendidos en la materia Sistema de Procesamiento de Datos.

## Función principal

Esta función se encarga de hacer sonar al buzzer la cantidad de veces recibida por parametro, por un tiempo y con una intensidad que tambien
son recibidos por parametro. 

~~~ C++ 
// ESTA FUNCION VA A DURAR LO QUE duren las funciones: 
// sonarBuzzer() + silenciarBuzzer() * veces
void sonarSilenciarBuzzer(int buzzer, int tiempo, int intensidad, int veces)
{
  int contador = 0;
  
  while (contador < veces)
  {
    sonarBuzzer(buzzer, tiempo, intensidad);
    silenciarBuzzer(buzzer, tiempo);
    contador = contador + 1;
  }
}
~~~

## :robot: Link al proyecto
- [Tinkercard-Sol Rubinetti](https://www.tinkercad.com/things/kvxo3hxow4a-copy-of-dojo-1-grupo-f-clase-5-rubinetti-sol-1d/editel?sharecode=WGMzLdPwy3q_oZEOTwYz3Y0MRbV6R5n879nWy0bPDZo)
- [Tinkercard-Yamila Sueldo](https://www.tinkercad.com/things/gyURhZ5qcD9-copy-of-dojo-numero-uno/editel?sharecode=jcljAZWur_vRAy5BWvCNVAHIg4dVq48kvHV_FXRgf9k)
- [Tinkercard-Adrian Barrientos](https://www.tinkercad.com/things/8mgCsJsUrRK-bodacious-borwo/editel?sharecode=VCCzrcbr8gq2P9JAjRSaL-b77EM1lVzc9hE01hZxCX8)
- [Tinkercard-Lautaro Torres](https://www.tinkercad.com/things/fSOhHiGeVdJ-lautaro-torresejercicio-dojo-1-2/editel?sharecode=9IKDJYqicsguvunn1_dn7oklyXOUMo9TCehS7j1dNF8)
- [Tinkercard-Trinidad Faccini](https://www.tinkercad.com/things/4z3mhxVozQW-dojo-uno-grupo-f-entrega-dos/editel?sharecode=w1-w-rqWAS2D5xQI_Y1ASwRkBqFLPSaJrfb6A1xqPrc)
