// --- 📜 REPTES DE TEORIA (Dades per al mode Test) ---
const dadesTest = {
  "python": {
    titol: "Python: De zero a Heroi",
    exercicis: [
      { id: "py1", pregunta: "Com s'imprimeix 'Hola'?", opcions: ["print('Hola')", "echo 'Hola'", "console.log('Hola')"], correcta: 0 },
      { id: "py2", pregunta: "Com es fa un comentari?", opcions: ["//", "/*", "#"], correcta: 2 },
      { id: "py3", pregunta: "Quin tipus és 5?", opcions: ["float", "int", "str"], correcta: 1 },
      { id: "py4", pregunta: "Quin tipus és 5.5?", opcions: ["int", "float", "complex"], correcta: 1 },
      { id: "py5", pregunta: "Com declarem una variable?", opcions: ["var x = 5", "int x = 5", "x = 5"], correcta: 2 },
      { id: "py6", pregunta: "Com sumem 1 a la variable 'x'?", opcions: ["x++", "x += 1", "x =+ 1"], correcta: 1 },
      { id: "py7", pregunta: "Resultat de 10 / 2?", opcions: ["5", "5.0", "2"], correcta: 1 },
      { id: "py8", pregunta: "Quin operador és per comparar igualtat?", opcions: ["=", "==", "==="], correcta: 1 },
      { id: "py9", pregunta: "Com comprovem si 'a' NO és igual a 'b'?", opcions: ["a != b", "a <> b", "not a = b"], correcta: 0 },
      { id: "py10", pregunta: "Com es defineix una funció?", opcions: ["function f():", "def f():", "void f():"], correcta: 1 },
      { id: "py11", pregunta: "Què retorna 'len([1,2,3])'?", opcions: ["2", "3", "4"], correcta: 1 },
      { id: "py12", pregunta: "Com s'afegeix un ítem a una llista?", opcions: [".add()", ".push()", ".append()"], correcta: 2 },
      { id: "py13", pregunta: "Quin bucle s'usa per recórrer una llista?", opcions: ["for", "while", "foreach"], correcta: 0 },
      { id: "py14", pregunta: "Com comprovem si una clau és en un diccionari?", opcions: ["key in dict", "dict.has(key)", "exists(key)"], correcta: 0 },
      { id: "py15", pregunta: "Què és una 'tupla'?", opcions: ["Llista que no es pot canviar", "Llista de números", "Un error"], correcta: 0 },
      { id: "py16", pregunta: "Com gestionem errors?", opcions: ["if/else", "try/except", "catch/finally"], correcta: 1 },
      { id: "py17", pregunta: "Què és 'None'?", opcions: ["Un número", "Absència de valor", "Cert"], correcta: 1 },
      { id: "py18", pregunta: "Importar una llibreria?", opcions: ["using maths", "import math", "#include math"], correcta: 1 },
      { id: "py19", pregunta: "Què fa 'range(5)'?", opcions: ["Genera 0,1,2,3,4", "Genera 1 a 5", "Dóna error"], correcta: 0 },
      { id: "py20", pregunta: "Què és '__init__' en una classe?", opcions: ["El destructor", "El constructor", "Una variable"], correcta: 1 }
    ]
  },
  "html": {
    titol: "HTML: Estructura la Web",
    exercicis: [
      { id: "h1", pregunta: "Què vol dir HTML?", opcions: ["Hyper Text Markup Language", "High Tech Modern Language", "Hyper Tabular Mobile Link"], correcta: 0 },
      { id: "h2", pregunta: "Etiqueta per al títol principal?", opcions: ["<title>", "<h1>", "<head>"], correcta: 1 },
      { id: "h3", pregunta: "Etiqueta per a un paràgraf?", opcions: ["<text>", "<p>", "<div>"], correcta: 1 },
      { id: "h4", pregunta: "Com es tanca l'etiqueta <div>?", opcions: ["<div/>", "</div>", "<\div>"], correcta: 1 },
      { id: "h5", pregunta: "Etiqueta per a un salt de línia?", opcions: ["<lb>", "<br>", "<break>"], correcta: 1 },
      { id: "h6", pregunta: "Com es fa un enllaç?", opcions: ["<link>", "<a href='...'>", "<url>"], correcta: 1 },
      { id: "h7", pregunta: "Atribut per posar una imatge?", opcions: ["src", "url", "link"], correcta: 0 },
      { id: "h8", pregunta: "Llista amb punts (desordenada)?", opcions: ["<ol>", "<li>", "<ul>"], correcta: 2 },
      { id: "h9", pregunta: "Element d'una llista?", opcions: ["<item>", "<li>", "<list>"], correcta: 1 },
      { id: "h10", pregunta: "Etiqueta per a negreta?", opcions: ["<bold>", "<strong>", "<neg>"], correcta: 1 },
      { id: "h11", pregunta: "On va la meta-informació?", opcions: ["<body>", "<head>", "<footer>"], correcta: 1 },
      { id: "h12", pregunta: "Atribut per obrir enllaç en pestanya nova?", opcions: ["target='_blank'", "new='true'", "mode='tab'"], correcta: 0 },
      { id: "h13", pregunta: "Com es fa una taula?", opcions: ["<grid>", "<table>", "<board>"], correcta: 1 },
      { id: "h14", pregunta: "Fila d'una taula?", opcions: ["<td>", "<th>", "<tr>"], correcta: 2 },
      { id: "h15", pregunta: "Dada d'una cel·la?", opcions: ["<td>", "<tr>", "<cell>"], correcta: 0 },
      { id: "h16", pregunta: "Comentari en HTML?", opcions: ["//", "", "/* */"], correcta: 1 },
      { id: "h17", pregunta: "Etiqueta per a un formulari?", opcions: ["<input>", "<form>", "<post>"], correcta: 1 },
      { id: "h18", pregunta: "Input per a contrasenyes?", opcions: ["type='secret'", "type='password'", "type='hidden'"], correcta: 1 },
      { id: "h19", pregunta: "Quin atribut identifica un element de forma única?", opcions: ["class", "id", "name"], correcta: 1 },
      { id: "h20", pregunta: "Etiqueta per a contingut secundari/lateral?", opcions: ["<side>", "<aside>", "<section>"], correcta: 1 }
    ]
  },
  "css": {
    titol: "CSS: Estil i Disseny",
    exercicis: [
      { id: "c1", pregunta: "Què vol dir CSS?", opcions: ["Cascading Style Sheets", "Color Style System", "Creative Style Sheet"], correcta: 0 },
      { id: "c2", pregunta: "Canviar color de text?", opcions: ["text-color", "color", "font-color"], correcta: 1 },
      { id: "c3", pregunta: "Canviar color de fons?", opcions: ["background-color", "bg", "color-bg"], correcta: 0 },
      { id: "c4", pregunta: "Com seleccionar un ID en CSS?", opcions: [".id", "#id", "id:"], correcta: 1 },
      { id: "c5", pregunta: "Com seleccionar una CLASSE?", opcions: [".classe", "#classe", "*classe"], correcta: 0 },
      { id: "c6", pregunta: "Mida de la font?", opcions: ["text-size", "font-size", "size"], correcta: 1 },
      { id: "c7", pregunta: "Posar el text en negreta?", opcions: ["font-weight: bold", "text-style: bold", "font: bold"], correcta: 0 },
      { id: "c8", pregunta: "Espai DINS d'un element?", opcions: ["margin", "padding", "border"], correcta: 1 },
      { id: "c9", pregunta: "Espai FORA d'un element?", opcions: ["padding", "margin", "gap"], correcta: 1 },
      { id: "c10", pregunta: "Treure el subratllat d'un enllaç?", opcions: ["text-decoration: none", "link: none", "underline: hidden"], correcta: 0 },
      { id: "c11", pregunta: "Tipus de lletra?", opcions: ["font-type", "font-family", "text-font"], correcta: 1 },
      { id: "c12", pregunta: "Centrar text?", opcions: ["align: center", "text-align: center", "margin: center"], correcta: 1 },
      { id: "c13", pregunta: "Fer invisible però que ocupi espai?", opcions: ["display: none", "visibility: hidden", "opacity: 0"], correcta: 1 },
      { id: "c14", pregunta: "Gruix del vora?", opcions: ["border-width", "border-size", "stroke"], correcta: 0 },
      { id: "c15", pregunta: "Arrodonir cantonades?", opcions: ["border-round", "border-radius", "corner-style"], correcta: 1 },
      { id: "c16", pregunta: "Valor de 'display' per Flexbox?", opcions: ["block", "flex", "grid"], correcta: 1 },
      { id: "c17", pregunta: "Z-index serveix per a...", opcions: ["Zoom", "Capes (profunditat)", "Colors"], correcta: 1 },
      { id: "c18", pregunta: "Posició que segueix l'scroll?", opcions: ["absolute", "fixed", "relative"], correcta: 1 },
      { id: "c19", pregunta: "Canviar el cursor a una mà?", opcions: ["cursor: click", "cursor: pointer", "mouse: hand"], correcta: 1 },
      { id: "c20", pregunta: "Adaptar web a mòbils?", opcions: ["@media", "@mobile", "@responsive"], correcta: 0 }
    ]
  },
  "js": {
    titol: "JS: Programació Web",
    exercicis: [
      { id: "j1", pregunta: "Variable que no canvia?", opcions: ["let", "var", "const"], correcta: 2 },
      { id: "j2", pregunta: "Comentari d'una línia?", opcions: ["#", "//", "/*"], correcta: 1 }
    ]
  },
  "cpp": {
    titol: "C++: Alt Rendiment",
    exercicis: [
      { id: "cp11", pregunta: "Operador de residu (mòdul)?", opcions: ["/", "%", "&"], correcta: 1 },
      { id: "cp12", pregunta: "Estructura de selecció múltiple?", opcions: ["if", "select", "switch"], correcta: 2 },
      { id: "cp13", pregunta: "Com declarar un Array de 5 enters?", opcions: ["int a[5]", "array a(5)", "int a = 5"], correcta: 0 },
      { id: "cp14", pregunta: "Què és un punter?", opcions: ["Un número", "Adreça de memòria", "Una fletxa"], correcta: 1 },
      { id: "cp15", pregunta: "Operador per obtenir l'adreça?", opcions: ["*", "&", "@"], correcta: 1 },
      { id: "cp16", pregunta: "Accedir a la memòria d'un punter?", opcions: ["*", "&", "->"], correcta: 0 },
      { id: "cp17", pregunta: "Què vol dir 'void'?", opcions: ["Retorna 0", "No retorna res", "És buida"], correcta: 1 },
      { id: "cp18", pregunta: "Objecte en memòria dinàmica?", opcions: ["malloc", "new", "create"], correcta: 1 },
      { id: "cp19", pregunta: "Alliberar memòria dinàmica?", opcions: ["free", "delete", "clear"], correcta: 1 },
      { id: "cp20", pregunta: "Què és una classe?", opcions: ["Un grup", "Plantilla per a objectes", "Una funció"], correcta: 1 }
    ]
  },
  "unity": {
    titol: "Unity: Videojocs",
    exercicis: [
      { id: "u1", pregunta: "Quin llenguatge usa Unity?", opcions: ["C++", "C#", "Python"], correcta: 1 },
      { id: "u20", pregunta: "Què és 'Time.deltaTime'?", opcions: ["Hora actual", "Temps entre frames", "Velocitat"], correcta: 1 }
    ]
  }
};

// --- 🔍 ANALITZA EL CODI (Dades per al mode Anàlisi) ---
const dadesAnalisi = {
  "python": {
    titol: "🔍 Detectiu de Python",
    exercicis: [
      { id: "py_a1", pregunta: "x = 5\ny = 3\nprint(x + y)", opcions: ["53", "8", "x+y"], correcta: 1 },
      { id: "py_a2", pregunta: "a = '10'\nb = '20'\nprint(a + b)", opcions: ["30", "1020", "Error"], correcta: 1 },
      { id: "py_a3", pregunta: "if 5 > 10:\n  print('A')\nelse:\n  print('B')", opcions: ["A", "B", "Res"], correcta: 1 },
      { id: "py_a4", pregunta: "for i in range(3):\n  print(i)", opcions: ["1, 2, 3", "0, 1, 2", "0, 1, 2, 3"], correcta: 1 },
      { id: "py_a5", pregunta: "x = [10, 20, 30]\nprint(x[1])", opcions: ["10", "20", "30"], correcta: 1 },
      { id: "py_a6", pregunta: "def f(a, b=2):\n  return a * b\nprint(f(5))", opcions: ["5", "10", "2"], correcta: 1 },
      { id: "py_a7", pregunta: "x = 10\nx *= 2\nprint(x)", opcions: ["10", "12", "20"], correcta: 2 },
      { id: "py_a8", pregunta: "print(len('Hola'))", opcions: ["4", "5", "3"], correcta: 0 },
      { id: "py_a9", pregunta: "x = True\nprint(not x)", opcions: ["True", "False", "None"], correcta: 1 }
    ]
  },
  "html": { titol: "Inspector HTML", exercicis: [] },
  "css": { titol: "Inspector CSS", exercicis: [] },
  "js": { titol: "Inspector JS", exercicis: [] },
  "cpp": { titol: "Inspector C++", exercicis: [] },
  "unity": { titol: "Inspector Unity", exercicis: [] }
};

// --- 🛠️ CREA EL CODI (2 reptes per llenguatge) ---
const dadesCreacio = {
  "python": {
    titol: "Python: Repte d'Escriptura",
    exercicis: [
      { id: "pyc1", pregunta: "Escriu una instrucció per imprimir 'Hola Mon':", solucio: "print('Hola Mon')" },
      { id: "pyc2", pregunta: "Defineix una variable anomenada 'punts' amb el valor 100:", solucio: "punts = 100" }
    ]
  },
  "html": {
    titol: "HTML: Estructura real",
    exercicis: [
      { id: "hc1", pregunta: "Escriu l'etiqueta per a un títol de nivell 1 que digui 'Benvinguts':", solucio: "<h1>Benvinguts</h1>" },
      { id: "hc2", pregunta: "Crea un botó que digui 'Enviar' (només l'etiqueta):", solucio: "<button>Enviar</button>" }
    ]
  },
  "css": {
    titol: "CSS: Estils bàsics",
    exercicis: [
      { id: "cc1", pregunta: "Escriu la propietat per posar el color de text en vermell (red):", solucio: "color: red;" },
      { id: "cc2", pregunta: "Escriu la propietat per posar un marge superior de 20 píxels:", solucio: "margin-top: 20px;" }
    ]
  },
  "js": {
    titol: "JS: Lògica interactiva",
    exercicis: [
      { id: "jsc1", pregunta: "Fes un console.log que mostri exactament el número 5:", esperat: "5" },
      { id: "jsc2", pregunta: "Escriu el codi per mostrar una alerta que digui 'Hola':", solucio: "alert('Hola')" }
    ]
  },
  "cpp": {
    titol: "C++: Sintaxi de sistema",
    exercicis: [
      { id: "cpc1", pregunta: "Escriu la instrucció per imprimir 'Hola' usant cout (sense std::):", solucio: "cout << \"Hola\"" },
      { id: "cpc2", pregunta: "Declara una variable entera 'x' i assigna-li el valor 5:", solucio: "int x = 5;" }
    ]
  },
  "unity": {
    titol: "Unity: Scripting de motor",
    exercicis: [
      { id: "uc1", pregunta: "Escriu la instrucció per mostrar 'Xoc' a la consola d'Unity:", solucio: "Debug.Log(\"Xoc\")" },
      { id: "uc2", pregunta: "Com es diu el mètode per moure un objecte (Translate)?", solucio: "transform.Translate" }
    ]
  }
};