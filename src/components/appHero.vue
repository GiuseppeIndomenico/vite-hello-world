:<template>
    <div class="hero">
        <appTitle/>
        <div class="cont">
            <img src="../assets/logo.svg" alt="">
            <h3>Spero di aver capito come Farlo...!</h3>
        </div>
    </div>
</template>

<script>
import appTitle from './appTitle.vue';
    export default {
        components:{
            appTitle
        }
    }
</script>

<style lang="css" scoped>
.hero{
    width: 100%;
    height: 90vh;
    background-color: lightblue;
}
img{
    width: 100px;
    height: 100px;
    margin: 20px;

}
.cont{
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 50%;
    margin: 3rem auto;
}
</style>