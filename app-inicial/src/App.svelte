<script>
  //importamos el componente parImpar.svelte y lo llamamos ParImpar
  import Parlmpar from "./lib/parlmpar.svelte";
</script>
<main>
  <!--Llamamos el componente ingresando un numero impar en este caso 5-->>
  <Parlmpar numero={5}/>
  <!--Llamamos nuevamente el componente ingresando un numero par en este caso 20-->>
  <Parlmpar numero={20}/>
  <!--Llamamos el componente ingresando un numero 0-->>
  <Parlmpar numero={0}/>
  
</main>