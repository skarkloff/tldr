# pytest

> Ejecuta Python tests.
> Mas informacion en: <https://docs.pytest.org/>.


- Ejecuta tests desde archivos en especifico:

`pytest {{ruta/al/archivo_test.py ruta/al/archivo_test2.py ...}}`

- Ejecuta tests por nombre dando una expresion como palabra clave:

`pytest -k {{expresion}}`

- Salga tan pronto como una prueba falle o encuentre un error:

`pytest --exitfirst`

- Ejecutar pruebas que coincidan o excluyan marcadores:

`pytest -m {{marcador1 and not marcador2}}`

- Ejecutar hasta que falle una prueba, continuando desde la última prueba fallida:

`pytest --stepwise`

- Ejecutar prueba sin mostrar una salida:

`pytest --capture=no`
