---
title: Akzentfarben
styles: base/variables.scss
maturity: ready
control: exclude
colors: 
  - name: Aloe Vera
    hex: '#79c08b'
    rgb: rgb(121,192,139)
  - name: Petrol
    hex: '#008f8c'
    rgb: rgb(0,143,140)
  - name: Cyan
    hex: '#58c7da'
    rgb: rgb(88,199,218)
  - name: Beige
    hex: '#d7d5cd'
    rgb: rgb(215,213,205)
  - name: Beige als 35%
    hex: '#f0efec'
  - name: Beige hell
    hex: '#f1f0ee'
    rgb: rgb(241,240,238)
---
<style>
.set {
  display: flex;
  flex-wrap: wrap;
  margin: 0 -1rem;
  margin-top: 0;
  padding: 0;
  list-style: none;
}
li {
  flex: 1 0 25%;
  margin: 1rem;
}
.color {
  width: 100%;
  min-width: 160px;
  height: 80px;
  color: white;
  border: 1px solid whitesmoke;
  margin-bottom: 1rem;
}
p {
  margin: 0;
}
</style>
<ul class="set">
{% for item in page.colors %} 
  <li>
    <div class="color" style="background:{{ item.hex }}"></div> 
    <p>{{ item.name }}</p>
    {% if item.hex %}<p>{{ item.hex }}</p>{% endif %}
    {% if item.rgb %}<p>{{ item.rgb }}</p>{% endif %}
  </li>
{% endfor %}
</ul>