# react-typescript-single-and-multiple-option-selection
 
 https://634c24116fb7461274818c1d--bespoke-strudel-4aaf9c.netlify.app/

**Información destacada:**

- "onChange: (value: SelectOption | undefined) => void": Si no se tiene un valor éste puede ser indefinido, y esta es una función vacía que no retorna nada.

- "options: SelectOption[]" significa que se tiene una lista de opciones.

- "value?: SelectOption" es opcional y se refiere a la opción seleccionada actualmente.

- "... = useState<typeof options[0] | undefined>": Una variable de estado puede ser o una opción o el valor de undefined si aún no hemos puesto un valor.

- "className={`${styles.options} ${isOpen ? styles.show : ""}`}>": Si isOpen es verdadero, podemos usar el estilo show, y si es falso, se usa un estilo vacío.

**Highlighted information:**

- "onChange: (value: SelectOption | undefined) => void": If we don't have a value it can be undefined, and this is a void function 
that returns nothing.

- "options: SelectOption[]" means we have a list of options.

- "value?: SelectOption" is optional and refers to the currently selected option.

- "... = useState<typeof options[0] | undefined>": A state variable can be either an option or it can be the value of undefined 
if we haven't set a value yet.

- "className={`${styles.options} ${isOpen ? styles.show : ""}`}>": If isOpen is true, we can use the show style, otherwise just do an empty style.
