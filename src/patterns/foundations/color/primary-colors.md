---
title: Primary Colors
styles: base/variables.scss
maturity: ready
control: exclude
colors: 
  - name: Kampmann Blau
    hex: '#0e2249'
    rgb: rgb(14,34,73)
	cmyk: rgb(100,70,10,50)
  - name: Fr&uuml;hlingsgr&uuml;n
    hex: '#95c11f'
    rgb: rgb(149,193,31)
	cmyk: cmyk(50.0.100.0)
  - name: Aloe Vera
    hex: '#79c08b'
    rgb: rgb(121,192,139)
	cmyk: cmyk(57,0,57,0)
  - name: Petrol
    hex: '#008f8c'
    rgb: rgb(0,143,140)
	cmyk: cmyk(81,21,47,5)
  - name: Cyan
    hex: '#58c7da'
    rgb: rgb(88,199,218)
	cmyk: cmyk(61,0,61,0)
  - name: Beige
    hex: '#d7d5cd'
    rgb: rgb(215,213,205)
	cmyk: cmyk(18,13,20,0)
  - name: Beige als 35%
    hex: '#f0efec'
  - name: Beige hell
    hex: '#f1f0ee'
    rgb: rgb(241,240,238)
	cmyk: cmyk(7,5,7,0)	
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
  flex: 1 0 20%;
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
	{% if item.cmyk %}<p>{{ item.cmyk }}</p>{% endif %}
  </li>
{% endfor %}
</ul>