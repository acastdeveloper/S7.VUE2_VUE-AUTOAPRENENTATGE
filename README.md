# Sprint 7. Vue II

##### Sumari

- Descripció i Objectius

- Part teòrica
  
  - Curs Vue. Part 2.
  
  - Vue debugging.
  
  - A practicar!

- Part pràctica. S7. Pressupost.

# Descripció i Objectius

En aquest sprint acabaràs de conèixer els conceptes fonamentals de Vue que no ha donat temps a veure en l'anterior apartat.

##### **Durada de l'sprint**

15 dies lectius.

##### **Objectiu general**

- Aprendre conceptes bàsics i intermedis de Vue.

##### **Objectius específics**

- Entendre què són els mètodes de cicle de vida aprendre a utilitzar-los.
- Saber implementar watchers.
- Implementar el routing de Vue.
- Crear formularis amb Vue.
- Aprendre les directives de Vue.
- Debugar una aplicació Vue per detectar errors.
- Agregar i fer servir Bootstrap i Tailwind CSS.
- Aprendre a fer servir els slots de Vue.
- Consumir dades d'una API amb Axios.
- Aprofundir en la reactivitat de Vue.

---

# PART TEÒRICA

## Curs Vue, part 2

  

En el següent apartat treballaràs els conceptes més avançats de Vue.

És molt important que sàpigues comprendre correctament (en l'àmbit tècnic) les documentacions d'aquelles tecnologies amb les quals et familiaritzes habitualment.

En cada sprint estàs aprenent elements i aspectes nous, per aquest motiu et recomanem acudir a la **->[**documentació oficial de Vue**](https://v3.vuejs.org/guide/introduction.html#what-is-vue-js)** regularment perquè puguis repassar els conceptes i no t'oblidis de les seves característiques rellevants.

A més, la documentació oficial de Vue està molt ben estructurada, amb explicacions molt clares i concises!



### Cicle de vida dels components

En **Vue**, cada component té un cicle de vida, una quantitat d'etapes diferents que travessa.

Podem utilitzar aquests esdeveniments en diferents fases de la nostra aplicació per obtenir el control dels components:

[#06 Ciclo de vida de Vue (Lifecycle) | Curso de Vue.js 😍 Desde Cero - YouTube](https://www.youtube.com/watch?v=2VZBZuHOtIA)



### Watchers

Els **watchers** de Vue.js ens permeten executar una funció cada vegada que una propietat del nostre component modifiqui el seu valor:  

Si les propietats computades són més apropiades en la majoria dels casos, els **watchers** són més poderosos i ens permeten fer operacions complexes, com per exemple: les anomenades **http** o executar alguna lògica asíncrona (que no seria possible amb una propietat computada).

[watchers vue //🎓Curso de vuejs GRATIS// (17) Propiedades observadas (Watchers) - YouTube](https://www.youtube.com/watch?v=qD0pcT0xWb0)



### Formularis en Vue

Els formularis són una part molt important de qualsevol web, ja que normalment hem de demanar dades a l'usuari, com per exemple pot passar amb el **login i el registre.**

A continuació, et presentem un recurs molt complet perquè aprenguis a crear qualsevol mena de formulari en Vue.

[Vue JS 3 Tutorial for Beginners #7 - Forms &amp; Inputs - YouTube](https://www.youtube.com/watch?v=ixOcve5PX-Q)



### Routing

Totes les vistes (components) de la nostra app es mostren sobre l'índex, intercanviant el component que es visualitza en cada acció, però sense recarregar la pàgina **SPA (Single Page Action).** 

Per tant, en Vue existeix el **Sistema de Routing**, l'objectiu del qual és permetre que en la nostra app hi hagi rutes internes i la navegació.

El Routing és el responsable de reconèixer la ruta que l'usuari vol visualitzar a cada moment:

[#18 Rutas con Vue (router-view) | Curso de Vue.js 😍 Desde Cero - YouTube](https://www.youtube.com/watch?v=vHC5ByLBi0k)

[#19 Router Link y Rutas con Parámetros | Curso de Vue.js 😍 Desde Cero - YouTube](https://www.youtube.com/watch?v=ImKHslGDJhQ)

[#20 Parámetros dinámicos y rutas a través de eventos | Curso de Vue.js 😍 Desde Cero - YouTube](https://www.youtube.com/watch?v=YY219kmA54A)





### Query Params en Router-Link

A vegades, volem afegir paràmetres de consulta als URL de ruta i que els components siguin capaços d'obtenir els paràmetres d'aquesta ruta:

[VUE JS | Cómo configurar Query Params en Router-Link - YouTube](https://www.youtube.com/watch?v=6fUl-AnVxx0)



### Bootstrap & Vue

Bootstrap et permetrà crear llocs web **responsive** fàcilment. 

A continuació, et presentem una sèrie de vídeos que expliquen diversos temes fonamentals sobre Bootstrap implementat en Vue:

[#21 Bootstrap 4 + Vue [Instalación] | Curso de Vue.js 😍 Desde Cero - YouTube](https://www.youtube.com/watch?v=sMZZuM4tavo)

[#22 Navbar [Class Active] Bootstrap 4 + Vue | Curso de Vue.js 😍 Desde Cero - YouTube](https://www.youtube.com/watch?v=qoE6pTHv5eg)

[#23 Columnas responsives [Row/Col] Bootstrap 4 + Vue | Curso de Vue.js 😍 Desde Cero - YouTube](https://www.youtube.com/watch?v=WPlOlF3lWK0)

[#24 Botones y Cards con Bootstrap 4 + Vue | Curso de Vue.js 😍 Desde Cero - YouTube](https://www.youtube.com/watch?v=U_tHCLMTiFI)

[#25 Formulario INPUT con Bootstrap 4 + Vue | Curso de Vue.js 😍 Desde Cero - YouTube](https://www.youtube.com/watch?v=Z1LxWfjjdfU)

[#26 Formulario Select y Radio Buttons con Bootstrap 4 + Vue | Curso de Vue.js 😍 Desde Cero - YouTube](https://www.youtube.com/watch?v=iGGm_piFwoY)





### Tailwind & Vue

És un framework CSS que s'ha posat de moda recentment.

**VIGILA!** Ja que, en les ofertes d'ocupació apareix més sovint el Bootstrap que Tailwind!

Bé, en el cas que Bootstrap no t'hagi convençut del tot o simplement t'interessa aprofundir en la maquetació web, a continuació, et presentem un vídeo que ensenya a utilitzar Tailwind amb Vue:

[Tailwind CSS with Vue - YouTube](https://www.youtube.com/watch?v=ZAjUGkhqUP4)





### Consumir dades d'una API amb Axios

Aquesta part és fonamental, ja que, la majoria de les aplicacions web que hauràs de desenvolupar han de carregar dades a través d'un o diversos servidors externs.

A continuació, et presentem el següent vídeo que explica com utilitzar **Axios** per obtenir dades d'una **API.**

[| Vue desde 0 | Usando Axios para traer datos de una API #7 - YouTube](https://www.youtube.com/watch?v=0Ti9d524lNQ)

Estigues atent/a a aquesta part, perquè saber com consumir dades en una aplicació de Vue és essencial.  

El següent vídeo detalla com fer servir el concepte **fetch** en lloc d**'Axios**. Principalment, la diferència és que s'usen promeses i fa ús d'un paquet anomenat **Json-server**, que permet simular una API en el nostre ordinador.   

Json-server et pot ser útil a l'hora de resoldre una prova tècnica en una empresa, ja que queda molt millor que posar les variables hardcodeadas en un component o carregar un Json en local:

[Vue JS 3 Tutorial for Beginners #9 - Fetching Data - YouTube](https://www.youtube.com/watch?v=7iDGJolHFmU)





### Reactivitat en Vue

Una de les característiques que diferencien a Vue és el seu sistema de reactivitat. És important entendre com funciona per poder prevenir alguns errors comuns. 

En aquesta secció, indagarem en alguns detalls de baix nivell del sistema de reactivitat de Vue.

A més,  escoltar una xerrada d'un expert, observant els seus mètodes de programació i resolent dubtes, pot ser molt beneficiós pel teu aprenentatge amb Vue. 

T'aconsellem que ho facis!

[¿Cómo funciona la reactividad en VueJS? Implementando un sistema reactivo desde cero | T3chFest 2019 - YouTube](https://www.youtube.com/watch?v=axXwWU-L7RM)



## VUE DEBUGGING

### Vue Debug en VSCode

A vegades és més com posar els **breakpoints** en VSCode en lloc del browser, el següent vídeo et mostra com fer-ho:

[3 Ways To Debug Your Vuejs Apps With VS Code And Chrome - YouTube](https://www.youtube.com/watch?v=lyGt1TmleoU)



### Vue DevTools

**Vue DevTool** és una extensió per a navegadors Google Chrome o Firefox, útil per perfilar i depurar aplicacions desenvolupades amb Vue:

[Vue DevTools (Curso Vue.js ) - YouTube](https://www.youtube.com/watch?v=wBtNNomNGVc)



## PART PRÀCTICA - S7. PRESSUPOST

SSS
