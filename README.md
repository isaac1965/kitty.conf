# kitty.conf
My setup kitty terminal
```sh
enabled_layouts splits
map ctrl+shift+enter launch --location=vsplit
map ctrl+shift+\ launch --location=vsplit
map ctrl+shift+- launch --location=hsplit


# Redimensionar el panel horizontalmente
map ctrl+] resize_window narrower 1
map ctrl+[ resize_window wider 1
# Restablecer el tamaño de los paneles
map alt+r resize_window reset

#tabs
map ctrl+, next_tab
map ctrl+. previous_tab
map ctrl+t set_tab_title

# Cambiar al panel anterior
map ctrl+h previous_window
# Cambiar al siguiente panel
map ctrl+l next_window

```
