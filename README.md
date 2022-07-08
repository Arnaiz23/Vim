# Comandos vim

- w -> al final de la palabra derecha
- b -> al inicio de la palabra izquierda
- e -> al final de la palabra actual -1 letra
- j -> abajo
- k -> arriba
- l -> derecha
- h -> izquierda
- i -> insertar antes del cursor
- a -> insertar despues del cursor
- A -> insertar al final de la linea
- x -> eliminar el caracter
- gd -> ir a la definicion en el mismo archivo
- gf -> ir a la definicion de otro archivo
- dw -> eliminar la palabra (delete word)
- u -> rehacer (undo)
- ctrl r -> deshacer (redo)
- d shift4 -> elimina desde el cursor hasta el final de la linea
- d w -> elimina la palabra actual desde el cursor
- d b -> elimina la palabra anterior desde el cursor
- 6db -> elimina desde el cursor 6 caracteres hacia atras
- 6dw -> elimina desde el cursor 6 caracteres hacia delante
- dd -> corta
- p -> pegar despues de la linea del cursor (abajo de la linea)
- P -> pegar antes de la linea del cursor (arriba de la linea)
- r -> remplazar un caracter
- R -> remplazar y lo mantiene
- ciw -> cambiar palabra
- gg -> ir al inicio del archivo
- G -> ir al final del archivo
- ctrl g -> saber la linea en la que estas
- 12G -> ir a la linea 12
- normal /word enter -> busca
- buscar n -> siguiente coincidencia
- buscar N -> anterior coincidencia
- shift 5 -> saltar de {([ a })]
- c shift 5 -> cortar de {([ a })]
- 0 -> lleva al inicio de la linea
- $ -> lleva al final de la linea
- :s/th/de -> sustituye la primera ocurrencia th por de (en la linea del cursor)
- :s/th/de/g -> sustituye todas las ocurrencias th por de (en la linea del cursor)
- :%s/th/de/g -> sustituye todas las ocurrencias th por de (en todo el archivo)
- :%s/th/de/gc -> sustituye todas las ocurrencias th por de (en todo el archivo y pregunta palabra por palabra)
- o -> crea una nueva linea debajo del cursor
- O -> crea una nueva linea arriba del cursor
- v -> entra en el modo visual que te permite seleccionar
- v seleccion x -> elimina
- v seleccion y -> copia y luego p -> pegar


## IMPORTANTESSS !!!!!

- w -> al final de la palabra derecha
- b -> al inicio de la palabra izquierda
- j -> abajo
- k -> arriba
- l -> derecha
- h -> izquierda
- i -> insertar antes del cursor
- a -> insertar despues del cursor
- A -> insertar al final de la linea
- x -> eliminar el caracter
- u -> rehacer (undo)
- ctrl r -> deshacer (redo)
- d shift4 -> elimina desde el cursor hasta el final de la linea
- d w -> elimina la palabra actual desde el cursor
- d b -> elimina la palabra anterior desde el cursor
- dd -> corta
- p -> pegar despues de la linea del cursor (abajo de la linea)
- P -> pegar antes de la linea del cursor (arriba de la linea)
- R -> remplazar y lo mantiene
- ciw -> cambiar palabra
- gg -> ir al inicio del archivo
- G -> ir al final del archivo
- 12G -> ir a la linea 12
- normal /word enter -> busca
- buscar n -> siguiente coincidencia
- buscar N -> anterior coincidencia
- 0 -> lleva al inicio de la linea
- $ -> lleva al final de la linea
- o -> crea una nueva linea debajo del cursor
- O -> crea una nueva linea arriba del cursor
- v -> entra en el modo visual que te permite seleccionar
- v seleccion x -> elimina
- v seleccion y -> copia y luego p -> pegar



--------------------------------------------------------------------
## Configuracion de vim / neovim

Clone del repositorio / .vimrc en ~/.vimrc
Si uso neovim (asi comparto el mismo archivo de configuracion de tanto vim / neovim
  - nvim ~/.config/nvim/init.vim
    - source ~/.vimrc

