<template>
    <div>
    <input id="inputt" type="text" placeholder="Pesquisar">
    <button @click="search()" class="button">Click Aqui</button>
    </div>
</template>


<script>
   // addEventListener("click", search)
export default{
    methods:{
        search: function(){
            //let variavel = document.createElement('input')
            //variavel.id = 'inputt'
            //variavel.style = '../assets/css/style.css'
            let valor = document.getElementById("inputt").value
            if (valor != null){
               var tabela = document.getElementById("tabela")
               var tr = tabela.getElementsByTagName("tr")
               var td
               for(var i = 0; i < tr.length;i++){
                   td = tr[i]
                   if(td){
                       if(td.innerHTML.indexOf(valor) > -1){
                           tr[i].style.display = ""
                       }else{
                           tr[i].style.display = "none"
                       }
                   }
               }

            }else{
                valor = null
            }
        }
    }
}

</script>


