# Proyecto: Menú 3D Interactivo para Cafetería

Documento de definición y visión del producto para la aplicación de menú interactivo en 3D para cafeterías y restaurantes modernos.

---

## 1. Qué hace la app
Es una aplicación interactiva de menú digital en 3D que transforma la forma en que los comensales descubren y eligen lo que van a consumir. Al seleccionar cualquier producto o combo del menú, la aplicación renderiza en tiempo real una escena 3D hiperrealista del plato servido (por ejemplo, una porción de pan de banano con chips de chocolate junto a una taza de café latte). 

Además de la visualización visual y espacial del plato, la app funciona como una guía gastronómica y nutricional interactiva: al tocar cualquier componente de la comida o bebida, despliega de forma dinámica sobre una servilleta de papel virtual todos los ingredientes específicos, tipos de harina, alérgenos (huevos, lácteos, frutos secos, gluten) y notas culinarias de preparación.

---

## 2. Quién la usa
* **Usuarios principales:** Los clientes que visitan la cafetería o restaurante de especialidad.
* **Dispositivo y contexto de uso:** Se utiliza directamente en **tablets táctiles proporcionadas por la cafetería en cada mesa**. Los comensales interactúan con el dispositivo nada más sentarse, explorando el menú a su propio ritmo sin la presión de un mesero inmediato y con total claridad sobre lo que van a recibir.
* **Perfil de usuario:** Comensales urbanos, amantes del buen café, comensales visuales, personas con restricciones alimentarias o alergias, y clientes que valoran la transparencia en el origen de los ingredientes y el diseño contemporáneo.

---

## 3. Elementos 3D y Estética (Formas, Colores y Materiales)

### Elementos 3D en escena:
* **Comida y repostería:** Texturas volumétricas detalladas (ej. miga porosa y corteza horneada del pan de banano, chispas de chocolate fundidas con brillo y relieve, textura untuosa de salsas o cremas).
* **Bebidas y café:** Taza de cerámica con líquido realista, microespuma de leche y arte latte detallado con gradientes de café y crema.
* **Vajilla:** Plato principal, taza y platillo esmaltados en el color azul distintivo del branding (`#0400FF`), con acabado brillante/vitrificado de alta gama.
* **Mesa:** Mesa redonda metálica y plateada (acero inoxidable pulido/cepillado o aluminio) con reflejos suaves de la vajilla azul y la iluminación.
*(Nota: La servilleta no forma parte del modelado 3D base; se integrará posteriormente en la interfaz interactiva de la app).*

### Estética y Dirección Visual:
* **Estilo visual:** **Realista / Fotorealista**, enfocado en que los alimentos luzcan frescos, apetitosos, brillantes y tentadores (*food styling* de alta gama).
* **Iluminación:** Iluminación nítida y contemporánea de cafetería de moda, con luces de realce (*specular highlights*) que acentúan el brillo del chocolate, el esmaltado azul de la cerámica y los reflejos en la mesa plateada.
* **Identidad de Marca y Branding:**
  * Personalidad audaz (*super bold*), moderna y vanguardista.
  * **Color insignia de la marca:** **Azul eléctrico puro (`#0400FF`)**, protagonista en la vajilla y elementos de marca, contrastado con la superficie plateada metálica y los tonos dorados y tostados de la comida.
  * **Tipografía:** Títulos gruesos y geométricos (*heavy/bold display*), combinados con fuentes legibles y limpias para los listados de ingredientes.

---

## 4. Qué ve la persona en pantalla

### A. Vista Principal (Catálogo / Menú de la cafetería)
* Un encabezado dinámico con el branding potente de la cafetería (colores azul/naranja intensos).
* Cuadrícula o carrusel visual y fluido con todos los productos del menú categorizados (Repostería, Cafés de Especialidad, Desayunos, Tostadas, Bebidas Frías).
* Tarjetas de producto atractivas con micro-animaciones o vistas previas 3D que invitan a hacer tap.

### B. Vista de Detalle / Escena 3D
* **Área central interactiva:** El plato y la taza en azul `#0400FF` sobre la mesa redonda plateada.
* **Servilleta digital interactiva (UI):** Componente flotante de la app que se despliega sobre la escena al hacer clic o tap en cualquier alimento o bebida, revelando sus ingredientes.
* **Micro-menú flotante (*hud* o barra lateral):** Botones audaces con el nombre del plato, precio, indicador de alérgenos y botón de ordenar o llamar al mesero.
* **Indicadores visuales táctiles:** Puntos focales discretos o halos sutiles sobre los elementos interactivos del plato que invitan a tocarlos.

---

## 5. Qué puede hacer el usuario

1. **Explorar el menú completo:** Navegar entre las distintas categorías y platos de la cafetería.
2. **Manipular la vista 3D:** Rotar el plato en 360°, hacer zoom sobre texturas (como el chocolate derretido) e inclinar la cámara para apreciar el volumen y la presentación desde cualquier ángulo.
3. **Inspección de ingredientes por toque:**
   * Al pulsar sobre el **pan de banano**, la servilleta de papel revela: tipo de harina utilizada (ej. almendra, avena, trigo integral), porcentaje de cacao de las chispas, si contiene huevo o lácteos, y gramos de azúcar.
   * Al pulsar sobre el **latte**, la servilleta detalla: origen del grano de café, notas de cata, perfil de tueste y tipo de leche (entera, avena, almendra, etc.).
4. **Filtrar por preferencias o alérgenos:** Opción de marcar filtros (sin gluten, vegano, sin azúcar añadida) para que la app resalte los ingredientes y platos aptos.
5. **Leer notas de sabor y origen:** Conocer la historia detrás de los proveedores locales y métodos de preparación artesanal.

---

## 6. Qué se comparte entre usuarios

* **Recomendaciones y valoraciones de comensales:** Los clientes pueden leer y dejar opiniones breves, consejos o combinaciones favoritas (ej. *"Pídelo con leche de avena, resalta mucho el cacao"* o *"La textura del pan es súper húmeda y suave"*).
* **Notas y tips sobre ingredientes:** Marcadores dejados por la comunidad de clientes respecto a adaptaciones populares (ej. sustituciones recomendadas para personas celíacas o veganas).
* **Insignias o platos más populares (*Trending in-house*):** La aplicación muestra en tiempo real qué platos e ingredientes están siendo los más explorados y mejor valorados por los demás clientes en el local durante el día.
