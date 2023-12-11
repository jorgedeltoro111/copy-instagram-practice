<script>
    import Comments from "./Comments.svelte";
</script>

<div class="Card">
    <div class="Card-container">
        <div class="Card-header">
            <div class="Card-user">
                <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.zaunk.com%2Fblog%2Frazas%2Fyorkshire-terrier-caracteristicas-y-cuidados%2F&psig=AOvVaw0hgoWqp7XerFiXUa21lmR6&ust=1702410177596000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCIjH-72SiIMDFQAAAAAdAAAAABAD" alt="">
                <h2>Terry</h2>
                <span>Guadalajara, Jalisco</span>
            </div>
            <div class="Card-settings">
                <i class="fas fa-ellipsis-h"/>
            </div>
        </div>
        <div class="Card-photo">
            <figure>
                <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.zaunk.com%2Fblog%2Frazas%2Fyorkshire-terrier-caracteristicas-y-cuidados%2F&psig=AOvVaw0hgoWqp7XerFiXUa21lmR6&ust=1702410177596000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCIjH-72SiIMDFQAAAAAdAAAAABAD" alt="">
            </figure>
        </div>
        <div class="Card-icons">
            <div class="Card-icons-first">
                <i class="fas fa-heart"/>
                <i class="fas fa-paper-plane"/>
            </div>
            <div class="Card-icons-second">
                <i class="fas fa-bookmark"/>
            </div>
        </div>
        <div class="Card-description">
            <h3>terry</h3>
            <span>Hola!</span>
        </div>
        <Comments/>
    </div>
</div>