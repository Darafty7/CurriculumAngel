<template>
    <main>
        <div>
            <header>
                <section class="lado1">
                </section>
                <section class="lado2">
                </section>
            </header>
        </div>

        <div class="foto">
            <header>
                <section class="foto1">
                    <img
                        src="../assets/fotocv.jpg"
                        alt=""
                    >
                        <h2>Angel Cantero</h2>
                </section>
                <section class="texto">
                    <h1>Un poco sobre mi</h1>
                    <div class="contenido">
                        <p>
                            Soy programador en formación en el tecnologo ADSI en el Sena C.T.P.I
                        </p>
                    </div>

                </section>
            </header>
        </div>
        <div>
            <button
                class="boton1"
                @click="$router.push('/Curriculum')"
            >Curriculum</button>
        </div>
        <div>
            <button
                class="boton2"
                @click="$router.push('/Proyecto')"
            >Proyecto</button>
        </div>
        <div>
            <footer>
                <strong>
                    <p class="llama">Llama: +57 3117632674
                    </p>
                    <p class="correo">Email: angelcantero3@gmail.com</p>
                </strong>
            </footer>
        </div>
    </main>

</template>

<script>
export default {
  name: "SobreMiComponent",
  data() {},
};
</script>

<style scoped>
header {

  display: flex;
}

.lado1 {
  background-color: rgb(240, 204, 158);
  width: 40%;
  height: 700px;
}
.lado2 {
  background-color: rgb(246, 246, 246);
  width: 60%;
  height: 700px;
}
.foto {
  position: absolute;
  top: 300px;
  left: 350px;

  border-radius: 4px;
}
.foto1 {
  background-color: rgb(243, 224, 200);
  padding: 50px 50px 50px 50px;
  box-shadow: 10px 10px 13px gray;
}
img {
  width: 250px;
  height: 250px;
  box-shadow: 10px 10px 13px gray;
  border-radius: 50%;
}
.texto {
  background-color: rgb(255, 255, 255);
  box-shadow: 10px 10px 13px gray;
  width: 40%;
}
.contenido p {
  font-size: medium;
  text-align: center;
}
.boton1 {
  background-color: rgb(247, 247, 247);
  width: 100px;
  height: 100px;
  border-radius: 50%;
  border: 1.5px solid rgb(4, 2, 14);
  position: absolute;
  top: 550px;
  left: 750px;
  box-shadow: 12px 12px 12px rgb(255, 190, 150);
}
.boton1:hover {
  background-color: rgb(246, 221, 188);
}
.boton2 {
  background-color: rgb(247, 247, 247);
  width: 100px;
  height: 100px;
  border-radius: 50%;
  border: 1.5px solid rgb(3, 1, 12);

  position: absolute;
  top: 550px;
  left: 890px;
  box-shadow:12px 12px 12px rgb(255, 191, 159);
}
.boton2:hover {
  background-color: rgb(246, 221, 188);
}

footer {
  display: flex;
  position: absolute;
  left: 300px;
}
.llama {
  display: inline-block;
  padding: 10px;
}
.correo {
  display: inline-block;
  padding: 10px;
}
</style>