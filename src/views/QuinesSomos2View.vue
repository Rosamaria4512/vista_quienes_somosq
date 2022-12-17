<template>
    <nav>
        <nav-componente/>

    </nav>
   <div  class="parallax1 my-8 mb-5 mt-1" >
            <!-- <div class="heading">Tu Sena</div>
            <div class="heading2">Hola que hace</div> -->

            <img src="../assets/sd.jpg" alt="">
            
          </div>
      
          <section>
            <h1>Misión</h1>
            <div class="two-col">
              <p>El grupo de Investigación INNOVATEC CTPI es un grupo integrado por instructores(as) investigadores(as) y aprendices del Centro de Teleinformática y Producción Industrial del SENA Regional Cauca, cuya orientación es la promoción de las capacidades investigativas en la comunidad científica y académica del centro de formación, a través del desarrollo de procesos teórico prácticos de formación profesional integral, la aplicación de las competencias laborales de los aprendices y el aporte a las necesidades tecnológicas de las empresas afines a las áreas estratégicas del centro, para generar la habilidad de trabajo en equipo, impulsar la formación permanente y facilitar la interacción entre lo académico y lo práctico a través de la investigación interdisciplinaria.</p>
            </div>
          </section>
          <h1>Visión</h1>
          <div class="two-col">
            <p>Para el año 2025, el grupo de investigación INNOVATEC CTPI será un grupo reconocido, que liderará procesos de investigación aplicada con un carácter interdisciplinario, apoyado en las redes sectoriales de conocimiento, e impactará con sus resultados y productos científicos en la formación profesional integral que se imparte al interior del SENA y en los sectores productivos del Departamento del Cauca, como parte de las nuevas tendencias tecnológicas que presenta el mundo contemporáneo, para el mejoramiento de la innovación y la competitividad</p>
          </div>
      
         
      
          <section class="dark">
            <h2>Objetivos</h2>
            <h3>Objetivo General</h3>
            <p>Desarrollar procesos de investigación aplicada, desarrollo tecnológico e innovación en las áreas y sectores de influencia del Centro de Teleinformática y Producción Industrial del SENA Regional las Políticas Institucionales Y Optimizando Los Recursos.</p>
      <h3>Objetivos Específicos</h3>
      <p>1.	Fomentar una cultura de investigación e innovación en los aprendices asociados a los programas de formación del Centro de Teleinformática y Producción Industrial (CTPI) mediante la implementación de semilleros y actividades científico-tecnológicas que generen proyectos de investigación al interior del centro.<br>
        2.	Promover el vínculo del grupo de investigación con los sectores productivos, fortaleciendo las capacidades e innovación tecnológica de las empresas, cadenas productivas y clústeres.<br>
        3.	Promover la transferencia de tecnología para mejorar la productividad de las empresas, así como la transferencia de conocimientos al SENA, para el beneficio de la formación profesional integral y la formación para el trabajo.<br>
        4.	Participar en actividades de investigación, innovación y desarrollo tecnológico, ocupacional y social, que contribuyan a la actualización y mejoramiento de la formación profesional integral y la formación para el trabajo.<br>
        5.	Fortalecer el perfil investigativo de los instructores del centro, mediante el desarrollo de proyectos reales, aplicando metodologías actualizadas.<br>
        </p>
      
          </section>
        
        <section>
          <div>
            <h3>Valores</h3>
            <div class="two-col">
              <p>Nuestras actividades se fundamentan en valores que guían y caracterizan el quehacer diario de las personas que conforman el grupo de investigación y configuran su ambiente y cultura de investigación, que son:</p>
              <p>•	Honestidad: Actuando siempre con fundamento en la verdad, cumpliendo los deberes con trasparencia, rectitud y favoreciendo siempre el interés general.<br>
                •	Respeto: Comprendiendo a las personas, valorando sus intereses y necesidades, y ofreciendo soluciones a través de la investigación y el desarrollo tecnológico.<br>
                •	Compromiso: Siendo conscientes de la importancia de nuestro rol como investigadores y estando en disposición permanente para comprender y resolver las necesidades de las personas con las que nos relacionamos en nuestras labores cotidianas, buscando siempre mejorar su bienestar.<br>
                •	Integridad: Actuando con entereza moral, rectitud y honradez, proyectando confianza hacia la comunidad, a través de los procesos de investigación que emprendemos.<br>
                •	Creatividad: Creando, innovado, generando ideas y conceptos que nos lleven a nuevas conclusiones, para resolver problemas con soluciones originales y valiosas que contribuyan a cambiar el entorno. <br>
                •	Responsabilidad: Cumpliendo con las obligaciones y tomando decisiones cuidadosas en el desarrollo de los procesos de investigación, desarrollo tecnológico e innovación requeridos por la sociedad. <br>
                •	Liderazgo: Influenciando positivamente en la forma de ser o actuar de las personas, haciendo del trabajo en equipo con entusiasmo, el medio para el logro de las metas y objetivos propuestos por el Centro de Teleinformática y Producción Industrial. 
             </p>
               
            </div>
            </div>
        
          
        </section>
      
          <!-- <div class="parallax4">
            <div class="two-col">
                Principios:<br>
                •	Ética científica<br>
•	Trasparencia<br>
•	Eficiencia<br>
•	Celeridad<br>

            </div>
          </div> -->
      
          <section class="dark">
            <h3>Principios:</h3>
                •	Ética científica •	Trasparencia •	Eficiencia •	Celeridad<br>
            
            <h2>Plan</h2>
            <p>• Plan estratégico • Plan Operativo Anual
            </p>
          </section>

          <div>
            <FooterComponente/>
          </div>
</template>

<script> 
import FooterComponente from '@/components/FooterComponente.vue';
import NavComponente from '@/components/NavComponente.vue'
import '../assets/css/style.css'

export default{
  components: { NavComponente, FooterComponente },
    name:'QuienesSomos2View'
}

</script>
