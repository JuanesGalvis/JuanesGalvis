<h1 align="center"> 🚀 JUAN ESTEBAN GALVIS 😎 </h1>
<h3 align="center"> Frontend 💻 - UI Designer 🎨 - Aspirante a Periodista Digital 🗞 </h3>

<p align="center"> <a href="https://twitter.com/JuanEGalvis"> <img src="https://img.icons8.com/fluent/48/000000/twitter.png" /> </a> <a href="https://www.linkedin.com/in/juanegalvis/"> <img src="https://img.icons8.com/color/48/000000/linkedin.png" /> </a> <a href="https://www.instagram.com/juanesgalvisb/"> <img src="https://img.icons8.com/fluent/48/000000/instagram-new.png" /> </a>
</p>

<h3> Vue 💚 </h3>

````
<script>
    export default = {
        name: 'Juan Esteban Galvis',
        data() {
            return {
                Nacionalidad: 'Colombia',
                Perfil: "Frontend MEVN - UI Designer",
                Estudios: [
                    'Estudiante de Ingeniería Informática',
                    'Técnico en programación de Software'
                ],
                Conocimientos: [ "Vue.js", "Figma", "Illustrator", "Notion", "JavaScript", "GitHub" ]
            }
        }.
        created() {
            this.Saludar();
        },
        methods: {
            Saludar() {
                console.log("🎉 BIENVENIDOS A MI PERFIL DE GITHUB 🎉")
            }
        }
    }

</script>
````

---------------------------------------------

<h3> React 💙 </h3>

````
import React, { Component } from 'react';

class JuanGalvis extends Component {
    state = { 
        Estudios: [
            'Estudiante de Ingeniería Informática',
            'Técnico en programación de Software'
        ],
        Conocimientos: [ "Vue.js", "Figma", "Illustrator", "Notion", "JavaScript", "GitHub" ]
     }

    handlerClick = () => {
        console.log('🎉 BIENVENIDOS A MI PERFIL DE GITHUB 🎉');
    }

    render() { 
        return ( 
            <main className="Presentacion">
                <section className="Presentacion__Personal">
                    <h1>Juan Esteban Galvis</h1>
                    <h2>Frontend - UI Designer</h2>
                </section>
                <section className="Presentacion__Estudios">
                    <h3> Estudios: </h3>
                    <ul>
                        {
                            this.state.Estudios.map((item) => <li>{ item }</li> )
                        }
                    </ul>
                </section>
                <section className="Presentacion__Conocimientos">
                    <h3> Conocimientos: </h3>
                    <ul>
                        {
                            this.state.Conocimientos.map((item) => <li>{ item }</li> )
                        }
                    </ul>
                </section>
                <button onClick={handlerClick} className="Presentacion__Saludar"> Saludar </button>
            </main>
         );
    }
}
 
export default JuanGalvis;
````

---------------------------------------------

<h3> Métricas </h3>
<p align="center">  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JuanesGalvis&theme=highcontrast" width="350" /> <img src="https://github-readme-stats.vercel.app/api?username=JuanesGalvis&theme=highcontrast" width="450" height="300" /> </p>

---------------------------------------------
