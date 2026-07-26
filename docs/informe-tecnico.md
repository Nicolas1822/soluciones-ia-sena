| Dato | Cómo obtenerlo | Valor |
| :--- | :--- | :--- |
| Perfil de hardware | Sección 2 de la guía | 16 RAM |
| RAM total del equipo | `free -h` | 6.9Gi |
| Modelo y etiqueta | `ollama list` | qwen2.5-coder:1.5b |
| Tamaño en disco | `ollama list` | 986 MB |
| Latencia de 5 ejecuciones (ms) | `time curl ...` cinco veces | real 0m0.010s user 0m0.010s sys 0m0.001s |
| Latencia promedio | Promedio de las cinco | 18,2 |
| RAM usada durante la inferencia | `free -h` mientras responde | 622Mi |
| Calidad percibida (1 a 5) | Su criterio, con una frase que lo justifique | responde de manera acertada, pero brindando respuestas limitadas |
