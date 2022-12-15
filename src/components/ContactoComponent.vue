<template>
    <main>
        <div>
            <header>
                <section class="color"></section>
            </header>
        </div>
        <div>
            <section class="contacto">
            <form action="grbbar.html" method="get"></form>
            <p>
                Nombre: <input type="text" maxlength="50" placeholder="">
            </p>
            <p>
                Apellido: <input type="text" maxlength="50" placeholder=""><br>
            </p>
            <p>
            Asunto:<input type="text" maxlength="50" placeholder=""><br>
            </p>
            <p>
            Mensaje: <input type="text" maxlength="50" placeholder=""><br>
            </p>
        </section>
        </div>
        <div>
        <footer>
            <p class="llama">Llama +57 3143268481
            </p>
            <p class="correo">Escribe angelcantero3@gmail.com</p>
        </footer>
    </div>
    <div>
        <button class="boton" @click="$router.push('/Contacto')">Enviar</button>
    </div>
    </main>
</template>

<script>
export default{
    name: 'ContactoComponent',
    data(){
    }
}
</script>

<style scoped>
.color{
background-color: antiquewhite;
width: 100%;
height: 500px;
}

.contacto{
    background-color: rgb(253, 255, 255);
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    padding:20px 20px 60px 15px;
    border: 1px solid black;
    border-radius: 6px;
    margin: 0 auto;
    width: 400px;
    text-align: left;
    box-shadow: 10px 10px 13px rgb(250, 220, 195);
    position: absolute;
    top: 350px;
    left: 400px;
}
.boton{
    background-color: rgb(253, 253, 253);
    width: 90px;
    height: 50px;
    border-radius: 10px;
    border: 1.5px solid gray;
    position: absolute;
    top:575px;
    left: 560px;
    box-shadow: 10px 10px 13px gray;
}
.boton:hover{
    background-color: rgb(255, 223, 181);
}

footer{
    display: flex;
    position: absolute;
    left: 1000px;
}
.llama{
    display: inline-block;
    padding: 10px;
    
}
.correo{
    display: inline-block;
    padding: 10px;
}
</style>