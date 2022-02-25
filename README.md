### PCEP Multitest

<a href="https://pythoninstitute.org/certification/pcep-certification-entry-level/pcep-exam-syllabus/">Python Institute</a>
### Asignación de bloques:
* **Bloque 1:** Enrique
* **Bloque 2:** Juan, Arancha
* **Bloque 3:** Dannel
* **Bloque 4:** Vito, Daniel

### Esquema de las preguntas:

```js
"Nombre del Bloque": [ // Los nombres de los bloques ya han sido definidos
    {
        "question": "some q",
        "options": [
            "op1","op2","op3"
        ],
        "answer": 0 // Indice de la opción correcta (En este caso la opción correcta es la primera)
    }
```

### Iniciar repo
```bash
git clone https://github.com/vgenov-py/t603_pcep
cd t603_pcep
git checkout develop
echo "Agregas preguntas... SOY UN COMENTARIO NO HAGO NADA"
git add pcep.json
git commit -m "Agregué muchas preguntas"
git push origin develop
```