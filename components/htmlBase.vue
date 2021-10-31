<template>
    <article>

      <section>
        <!------------------------------------------------------->
        <!--navbar-->
          <template>
              <navBar/>
          </template>
          <!--fim nav bar-->
      </section>

      <!------------------------------------------------------------>
      <!--main body-->
      <main>
          <!--left side bar-->
          <section>
              <template>
                  <leftSideBar/>
              </template>
          </section>
          <!--fim da left side bar-->

          <!------------------------------------------------------------>
          <!--table-->
          <section>

              <input/>
              <!--button-->
                <buttonPesquisa/>

              <!--tabela-->
              <tabela/>
          </section>
          <!--Fim da table-->

          <!------------------------------------------------------------>
          <!--right side bar-->
          <section>


               <template>
                  <RightSideBar/>
              </template>
          </section>
          <!--fim-->
      </main>
      <footer>
        <script src="./assets/script.js"></script>
      </footer>
    </article>
</template>
