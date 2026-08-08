# Tramo Destino — archivo de problemas

**Cuando:** 2026-08-08T17:57:27.227Z
**Versión:** 4.0.1
**Nombre:** Tomás Duva
**Señal dueño:** SI — arreglar y publicar
**Ruta:** BUE → FLN
**Salud:** ENFERMA (zero_quotes, scrape_all_fail)
**Quotes:** 0/14 · bait: 0 · scrape 0/8 · API 0/1

## Recomendación

Al poner volver atrás me pide confirmación, si la apruebo detiene, no pausea. Está el boto. De pausa, eso sí! Pero yo vuelvo para atrás sin tocar pausa y se detiene en vez de poner pausa. De ahora en más.. no v a haber confirmación. Directamente va a saltar el mensaje de que seguimos cotizando a menos que vuelva y ponga pausa o detener. (Cómo cuando minimizan la app) Y que así pase. Osea no que avisé y no haga nada. El cartelito de aviso se cierra en 2 segundos a menos que alguien lo cierre antes. Cuando decimos en la parte de "avísame si el viaje cambia" realmente está avisando? Esto tendría que pasar con la app cerrada, entonces? Cómo hacemos? Si podés solucionarlo vas a dejar un informe que se va a abrir por única vez en la próxima versión que hagas. Para yo leer este informe. Debe ser bien resumido simple y facil de entender. Si no lo cierro en 10 segundos se debe cerrar solo.

## Sitios

- fail: `{"google":1,"kayak":1,"kiwi":1,"skyscanner":1,"turismocity":1,"momondo":1,"despegar":1}`
- ok: `{}`

## Log

```
17:49:46 search_start v4.0.1
17:49:55 scrape_fail google:empty n=1
17:49:55 api_empty 2027-10-19
17:49:55 scrape_fail kayak:empty n=1
17:49:57 scrape_fail kiwi:empty n=1
17:49:57 scrape_fail skyscanner:empty n=1
17:50:04 scrape_fail turismocity:empty n=1
17:50:04 scrape_fail momondo:empty n=1
17:50:04 scrape_fail despegar:empty n=1
17:50:04 search_unhealthy zero_quotes,scrape_all_fail
17:50:07 scrape_fail expedia:empty n=1
17:50:09 diag_github_ok owner
```
