# Configuración de st-flexipatch

## Parches habilitados

### 1. **ALPHA_PATCH**
   - Agrega transparencia al terminal.
   - [Más información](https://st.suckless.org/patches/alpha/)

### 2. **ANYSIZE_PATCH**
   - Permite redimensionar la ventana a cualquier tamaño
   - [Más información](https://st.suckless.org/patches/anysize/)

### 3. **BLINKING_CURSOR_PATCH**
   - Da la opcion de añadir un cursor parpadeante
   - [Más información](https://st.suckless.org/patches/blinking_cursor/)

### 4. **BOXDRAW_PATCH**
   - Mejora el renderizado de ciertos caracteres especiales
   - [Más información](https://st.suckless.org/patches/boxdraw/)

### 5. **CLIPBOARD_PATCH**
   - Copia el texto seleccionado al portapapeles
   - [Más información](https://st.suckless.org/patches/clipboard/)

### 6. **COLUMNS_PATCH**
   - Permite redimensionar la terminal sin perder el contenido cuando cambia el tamaño de la ventana
   - [Más información](https://github.com/bakkeby/st-flexipatch/issues/34)

### 7. **FONT2_PATCH**
   - Permite agregar fuentes de respaldo para caracteres que no estén en la fuente predeterminada.
   - [Más información](https://st.suckless.org/patches/font2/)

### 8. **LIGATURES_PATCH**
   - Agrega compatibilidad con ligaduras tipográficas
   - [Más información](https://st.suckless.org/patches/ligatures/)

### 9. **SIXEL_PATCH**
   - Agrega soporte para gráficos SIXEL.
   - [Más información](https://gist.github.com/saitoha/70e0fdf22e3e8f63ce937c7f7da71809)

## Instalación
1. Configurar los parches editando `patches.def.h` según las preferencias.
2. Compilar e instalar:
   ```sh
   make clean install
   ```

## Uso
Ejecutar `st` desde la terminal:
```sh
st
```

## Notas adicionales
- Se pueden agregar o modificar los parches en `patches.def.h`.
- Si se cambia la configuración, recompilar con `make clean install`, tuve problemas con eso asi que tambien se deberia eliminar `config.h` y `patches.def`
- Algunos parches requieren bibliotecas adicionales; verificar `config.mk`.

---
Esta configuración ha sido optimizada para mejorar la usabilidad y funcionalidad de `st` sin afectar su eficiencia y simplicidad.

