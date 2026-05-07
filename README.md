Se explica la practica como la información solicitada (En DiarioPractica3.md se puede observar como se ha realizado todo)

TAREA 1 CI
1. Eventos que lanza workflow. Lo lanzas cuando se hagan push y pull-request sobre la rama master (no main) pero sólo cuando se cambie algo del directorio hangman-fron, no de otro.
2. Los pasos que se dan. Yo tengo  3 jobs encandenados que se ejecutan todos sobre ubuntu-latest, para build, test y bye (este se ejecutará aunque no falle alguno de los otros), como ocurre con el test.
3. Las actions usadas. Hay actions externas (actions/checkout@v4, actions/setup-node@v4, y una manual por mi).
4. Comentario adicional
     En las capturas puede observar primero un git push sobre la rama master (no main), por eso el ci.yml ejecutado primero no es de push-requests.
     Posteriormente se puede ver un push-requests cuando he cambio un fichero del directorio hangman-front y un merge del pull-requests una vez ejecutado el workflow en la rama workflow-ci.
     En el fichero DiarioPractica3.md se observa capturas de la ejecución de todo.,
   
TAREA 2 CI

1. Eventos que lanza workflow. En este caso lo vamos a realizar manualmente.
2. Los pasos que se dan. Yo tengo  3 jobs encandenados que se ejecutan todos sobre ubuntu-latest, para build, test y bye (este se ejecutará aunque no falle alguno de los otros), como ocurre con el test.
3. Las actions usadas. Hay actions externas (actions/checkout@v4, actions/setup-node@v4, y una manual por mi).
4. Comentario adicional
     Hay primeros Run realizado sobre mi propio docker hub, y después lo hago sobre docker registry.
     En el fichero DiarioPractica3.md se observa capturas de la ejecución de todo.,
