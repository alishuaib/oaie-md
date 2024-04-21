```python
player_hp_placeholder = widgets.HTML(value="💖").add_class('ui_label')
enemy_hp_placeholder = widgets.HTML(value="🖤").add_class('ui_label')
hp_bar_layout = widgets.HBox([player_hp_placeholder, enemy_hp_placeholder]).add_class('ui_box')
display(hp_bar_layout)
```
