---
description: >-
  Cómo se produce un KO, qué ocurre con los Stocks, cómo se gana la partida y
  cómo se resuelven los empates por KO simultáneo.
---

# Knockouts and Winning the Game

Un **Knockout** (KO) es el evento que hace avanzar la partida hacia su final: cada KO consume una reserva (**Stock**) del equipo afectado y, cuando un equipo se queda sin Stocks, la partida termina de inmediato.

Este capítulo define **cuándo** se produce un KO, **qué consecuencias** tiene, **cómo se gana** la partida y **cómo se resuelve** el caso excepcional de varios KO simultáneos.

> **Requisito previo:** este capítulo asume que ya conoces la resolución de fichas de Empuje descrita en [Push](push.md) y la estructura de rondas y secuencias explicada en [Gameplay](gameplay.md).

***

## 1. Qué es un Knockout

Una Leyenda es **noqueada** cuando termina **una o más casillas más allá de un borde** de la Arena.

Los bordes son las dos cartas de los extremos de la Arena. Quedar **sobre** el borde no es un KO; el KO exige **rebasarlo**.

### Formas de provocar un KO

| Origen                | Cuándo se comprueba                          | Descripción                                                                                    |
| --------------------- | -------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| **Empuje (Push)**     | Al final de cada ronda, en la fase de Empuje | Las fichas de Empuje acumuladas desplazan a la Leyenda más allá del borde. Es la vía habitual. |
| **Movimiento (Move)** | Al resolver el efecto de la carta            | Una Leyenda puede rebasar el borde por su propio movimiento y **auto-noquearse**.               |
| **Efectos de carta**  | Al resolver el efecto de la carta            | Cualquier efecto que mueva o empuje a una Leyenda puede sacarla de la Arena.                    |

> **Atención:** el Empuje se resuelve **al final de cada ronda**, no al final de la secuencia. Una Leyenda puede ser noqueada en la ronda 1 de una secuencia sin llegar a jugar sus cartas 2 y 3.

***

## 2. Resolución del Empuje y comprobación del KO

La fase de Empuje sigue siempre estos tres pasos, **en este orden**:

| Paso | Nombre                                   | Efecto                                                                                                                      |
| ---- | ---------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| 1    | **Empujar** (*Push*)                     | Por cada ficha de Empuje, mueve a la Leyenda una casilla en la dirección de la ficha. Después retira todas las fichas.        |
| 2    | **Agarrarse al borde** (*Grab the edge*) | Si la Leyenda ha quedado **exactamente sobre** un borde, gira hacia el centro de la Arena y avanza 1 casilla. **No hay KO.** |
| 3    | **¡Knockout!**                           | Si la Leyenda ha quedado **1 o más casillas más allá** del borde, es noqueada.                                               |

> **Fichas opuestas:** las fichas de Empuje en direcciones contrarias se cancelan. Si una Leyenda acumula fichas en ambos sentidos, retira una de cada dirección hasta que todas apunten al mismo lado.

***

## 3. Consecuencias de un Knockout

Cuando tu Leyenda es noqueada ocurre **una** de estas dos cosas:

### 3.1. Tu equipo conserva al menos 1 Stock

1. Retira **un Stock** de la reserva de tu equipo.
2. Coloca tu peana (*standee*) en la casilla donde está el **Portal** de tu equipo.
3. Elige **libremente** la dirección hacia la que mira tu Leyenda.

> La Leyenda **conserva su Fatiga acumulada**: volver a la Arena no reinicia el marcador de Fatiga.

### 3.2. Tu equipo no tiene Stocks

El equipo contrario **gana la partida inmediatamente**. No se resuelve el resto de la ronda ni de la secuencia.

***

## 4. Stocks y condición de victoria

Los Stocks son las «vidas» compartidas del equipo. Su cantidad inicial depende del formato de la partida:

| Formato | Stocks por equipo | KO necesarios para ganar |
| ------- | ----------------- | ------------------------ |
| **1v1** | 1                 | 2                        |
| **2v2** | 2                 | 3                        |
| **3v3** | 3                 | 4                        |

> **Cómo leer la tabla:** los Stocks absorben los primeros KO. El KO que gana la partida es el que se produce cuando el rival ya está a 0 Stocks; de ahí que hagan falta *Stocks + 1* KO.

**Condición de victoria:** gana el equipo que provoque un KO a un rival que ya no tenga Stocks en su reserva.

***

## 5. KO simultáneos y desempates

Leyendas de **ambos** equipos pueden ser noqueadas en la misma fase de Empuje. Si eso provocase que los dos equipos ganasen a la vez, aplica los siguientes criterios **en orden**, deteniéndote en el primero que resuelva el empate:

| Orden | Criterio de desempate                                                           | Gana...                                    |
| ----- | ------------------------------------------------------------------------------- | ------------------------------------------ |
| 1.º   | Número de KO sufridos **en esa ronda**                                          | El equipo que haya sufrido **menos** KO.   |
| 2.º   | Distancia a la que se ha empujado a un rival **más allá** del borde en esa ronda | El equipo que haya empujado **más lejos**. |
| —     | Ambos criterios empatados                                                       | La partida termina en **empate**.          |

***

## 6. Ejemplo de resolución

**Situación (partida 2v2).** El equipo Azul tiene 1 Stock; el equipo Rojo, 2. Al terminar la ronda, Alysia (Azul) tiene 2 fichas de Empuje hacia el borde izquierdo y está a 1 casilla de ese borde. Fitz (Rojo) tiene 1 ficha de Empuje hacia el borde derecho y está justo a 1 casilla del borde.

| Paso | Acción                                                     | Resultado                                                                       |
| ---- | ---------------------------------------------------------- | ------------------------------------------------------------------------------- |
| 1    | **Empujar:** Alysia se desplaza 2 casillas; Fitz, 1.       | Alysia queda 1 casilla **pasado** el borde; Fitz, **sobre** el borde.           |
| 2    | **Agarrarse al borde:** solo aplica a Fitz.                | Fitz gira hacia el centro y avanza 1. **Sobrevive.**                            |
| 3    | **Knockout:** Alysia ha rebasado el borde.                 | Alysia es **noqueada**.                                                          |
| 4    | **Consecuencia:** el equipo Azul tiene 1 Stock.            | Retira 1 Stock (queda a 0). Alysia vuelve al Portal azul con su Fatiga intacta. |

El siguiente KO que sufra el equipo Azul dará la victoria al equipo Rojo, porque Azul ya está a 0 Stocks.

***

## 7. La variante Free-for-all

En [Free-for-all variant](free-for-all-variant.md) cada jugador es su propio equipo y el objetivo cambia: **el primero en anotar 2 KO gana**. Estas son las diferencias que afectan a este capítulo:

| Regla estándar                                     | Regla en Free-for-all                                                                                                    |
| -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Los Stocks protegen al equipo.                     | **No se reparten Stocks.** Las fichas de Stock se usan para **contar los KO anotados** por cada jugador.                  |
| Al ser noqueado gastas un Stock.                   | Vuelves siempre al Portal central **con 2 de Fatiga**. Nunca eres eliminado.                                              |
| El KO no se atribuye a nadie en concreto.          | El KO lo anota **la última Leyenda que colocó una ficha de Empuje** en la dirección del empuje.                           |
| Gana quien agote los Stocks rivales.               | Gana quien anote **2 KO**.                                                                                                |
| Desempates: menos KO sufridos → empuje más lejano. | Se comprueba **antes** un criterio nuevo: gana quien haya anotado **más KO en esa ronda**.                                |
| —                                                  | Una Leyenda **sin fichas de Empuje** que fuese a ser noqueada vuelve al Portal (elige encaramiento y conserva su Fatiga). |

***

## 8. Errores frecuentes

| Error                                                      | Regla correcta                                                                      |
| ---------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Creer que quedar **sobre** el borde es un KO.              | Estar sobre el borde activa «Agarrarse al borde»: giras hacia el centro y avanzas 1. |
| Resolver el Empuje al final de la **secuencia**.           | El Empuje se resuelve al final de **cada ronda**.                                    |
| Reiniciar la Fatiga al volver por el Portal.               | La Fatiga **se conserva**; solo cambian la posición y el encaramiento.               |
| Sumar fichas de Empuje opuestas.                           | Se **cancelan** una a una antes de mover.                                            |
| Terminar la ronda tras un KO que deja al rival a 0 Stocks. | Perder el último Stock no es la derrota: la derrota llega con el **siguiente** KO.   |
| Olvidar comprobar los KO simultáneos.                      | Si ambos equipos ganarían a la vez, aplica los desempates de la sección 5.           |

***

## 9. Referencias cruzadas

* [Push](push.md) — mecánica completa de las fichas de Empuje.
* [Gameplay](gameplay.md) — estructura de secuencias y rondas.
* [Actions](actions.md) — cómo el *Strike*, la Fuerza y el Bloqueo generan fichas de Empuje.
* [Free-for-all variant](free-for-all-variant.md) — reglas completas de la variante.
* [FAQs](faqs.md) — aclaraciones sobre Fatiga, bordes y resolución de empujes.
