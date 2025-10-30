<script>
    import Comments from "./Comments.svelte";
</script>

<div class="Card">
    <div class="Card-container">
        <div class="Card-header">
            <div class="Card-user">
                <img
                    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQtJ9ljbEXvHgnR3bcho-9ZLG_8WCvHc1UAgA&s"
                    alt=""
                    width="100px"
                />
                <h2>Elmo.corg</h2>
                <span>Bogota, Colombia</span>
            </div>
            <div class="Card-settings">
                <i class="fa-solid fa-ellipsis"></i>
            </div>
        </div>
        <div class="Card-photo">
            <figure>
                <img
                    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQtJ9ljbEXvHgnR3bcho-9ZLG_8WCvHc1UAgA&s"
                    alt=""
                />
            </figure>
        </div>
        <div class="Card-icons">
            <div class="Card-icons-first">
                <i class="fa-solid fa-heart"></i>
                <i class="fa-solid fa-paper-plane"></i>
            </div>
            <div class="Card-icons-second">
                <i class="fa-solid fa-bookmark"></i>
            </div>
        </div>
        <div class="Card-description">
            <h3>Elmo.corg</h3>
            <span>Hola</span>
        </div>
        <Comments />
    </div>
</div>
