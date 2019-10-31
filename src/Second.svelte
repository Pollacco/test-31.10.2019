<script>
// Array.from(document.querySelector('section').children).forEach(elem => {
//     elem.addEventListener('click', e => {
//         e.target.classList.toggle('.active');
//         console.log('click', event);
//     });
// });
</script>

<style>
.red{
    width: 300px;
    height: 100px;
    background: red;
}
.blue{
    width: 300px;
    height: 100px;
    background: blue;
}
.green{
    width: 300px;
    height: 100px;
    background: green;
}

.active{
    visibility: hidden;
}
</style>

<section>
    <div class="red active">
    </div>
    <div class="blue">
    </div>
    <div class="green">
    </div>
</section>