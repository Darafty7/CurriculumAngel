<template>
    <main>
        <div>
            <header>
                <section class="color">
                </section>
            </header>
        </div>
        <div>
            <p class="estudio"><strong>Educacion</strong></p>
            <header class="flex-box">
                <section class="año">
                    <h1>2018</h1>
                </section>
                <section class="texto">
                    <div>
                        <p class="contenedor">Termine un tecnico en cocina en el PEC.</p>
                    </div>
                </section>
            </header>
        </div>
        <div>
            <header class="flex-box2">
                <section class="año2">
                    <h1>Nov 2019</h1>
                </section>
                <section class="texto2">
                    <div>
                        <p class="contenedor2">Termine mis estudios basica secundaria en la Institucion Educativa Simon Bolivar Piendamo - Cauca.</p>
                    </div>
                </section>
            </header>
        </div>
        <div>
            <header class="flex-box3">
                <section class="año3">
                    <h1>Jul - 2022</h1>
                </section>
                <section class="texto3">
                    <div>
                        <p class="contenedor3">Curso especial en aplicacion de la metodologia SCRUM para proyectos de desarrollo de sofware SENA.</p>
                    </div>
                </section>
            </header>
        </div>
        <div>
        <footer>
            <p class="llama">Llama
                +57 3205694796
            </p>
            <p class="correo">Escribe angelcantero3@gmail.com</p>
        </footer>
    </div>
    </main>
    
</template>

<script>
export default{
    name: 'CurriculumComponent',
    data(){
    }
}
</script>

<style scoped>
.color{
background-color: antiquewhite;
width: 100%;
height: 1150px;
}
.estudio{
    font-family: Verdana, Geneva, Tahoma, sans-serif     ;
    position: absolute;
    top: 450px;
    left: 400px;
    color: black;
}
.flex-box{
    display: flex;
    margin: auto;
    border: 1px solid black;
    width: 50%;
    height: 200px;
    background-color: rgb(255, 255, 255);

    position: absolute;
    top: 550px;
    left: 400px;

    box-shadow: 10px 10px 13px gray;
}
.año{
    width: 50%;
    margin: auto;
    color: rgb(0, 0, 0);
}
.texto{ 
    width: 50%;
    margin: auto;
}
.contenedor{
    font-size: medium;
    text-align: left;
}


.año1{
    width: 50%;
    margin: auto;
    color: rgb(0, 0, 0);
}
.flex-box2{
    display: flex;
    margin: auto;
    border: 1px solid black;
    width: 50%;
    height: 200px;
    background-color: rgb(255, 255, 255);

    position: absolute;
    top: 800px;
    left: 400px;

    box-shadow: 10px 10px 13px gray;
}
.año2{
    width: 50%;
    margin: auto;
    color: rgb(0, 0, 0);
}
.texto2{
    width: 50%;
    margin: auto;
}
.contenedor2{
    font-size: medium;
    text-align: left;
}
.flex-box3{
    display: flex;
    margin: auto;
    border: 1px solid black;
    width: 50%;
    height: 200px;
    background-color: rgb(255, 255, 255);

    position: absolute;
    top: 1050px;
    left: 400px;

    box-shadow: 10px 10px 13px gray;
}
.año3{
    width: 50%;
    margin: auto;
    color: rgb(0, 0, 0);
}
.texto3{
    width: 50%;
    margin: auto;
}
.contenedor3{
    font-size: medium;
    text-align: left;
}

footer{
    display: flex;
    position: absolute;
    left: 300px;
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