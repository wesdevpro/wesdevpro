<template>
   <footer class="footer">
      <div class="level">
         <div class="level-left">
            <div class="level-item">
               <div style="display: flex; flex-direction: row">
                  <div style="flex: 1" class="mx-1">
                     <a href="https://github.com/wesdevpro">
                        <font-awesome-icon
                           class="fa-4x mx-1"
                           style="color: #6e5494"
                           :icon="['fab', 'github-square']"
                        />
                     </a>
                  </div>
                  <div style="flex: 1" class="mx-1">
                     <a
                        href="https://www.linkedin.com/in/wesley-ford-developer"
                     >
                        <font-awesome-icon
                           class="has-text-info fa-4x"
                           :icon="['fab', 'linkedin']"
                        />
                     </a>
                  </div>
               </div>
            </div>
         </div>
         <div class="level-center has-text-centered">
            <img
               src="../assets/full-logo.png"
               style="
                  display: block;
                  margin-left: auto;
                  margin-right: auto;
                  max-width: 65%;
               "
               class="is-128x128"
            />
         </div>
         <div class="level-right has-text-right-bottom">
            <strong class="has-text-right"
               ><b>Contact</b><br />Wesley Ford<br />
               <a href="mailto:wes@wesdev.pro"> wes@wesdev.pro </a>
            </strong>
         </div>
      </div>
   </footer>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
@media screen and (max-width: 768px) {
   .level-left,
   .level-center,
   .level-right {
      text-align: center;
      margin-top: 10px;
      margin-bottom: 10px;
   }
}
svg {
   height: 48px;
}
</style>
