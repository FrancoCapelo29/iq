<p>NestJS es un framework de desarrollo basado en NodeJS para aplicaciones del lado del servidor, que utiliza TypeScript y está orientado a objetos. Fue diseñado para mejorar la productividad de los desarrolladores y ofrecer una arquitectura escalable y modular para aplicaciones empresariales. También incorpora características de Angular y permite integrar diferentes tecnologías y herramientas en su estructura de aplicación. En general, NestJS es un framework progresivo y uno de los más populares para construir aplicaciones backend eficientes, escalables y de nivel empresarial en NodeJS.</p>
<h1>NEST JS EN CONSOLA</h1>
<p>Para instalar NestJS en la consola, primero debes instalar la interfaz de línea de comandos de NestJS a través de npm. Puedes hacerlo siguiendo estos pasos:

1. Abre la terminal o consola en tu sistema operativo.
2. Escribe el siguiente comando y presiona Enter:

![[Pasted image 20230731100947.png]]

3. Espera a que la instalación termine, y luego podrás usar los comandos de NestJS en la consola de tu sistema.
</p>
<h1>COMO LEVANTAR NEST JS</h1>
<p>Para levantar un servidor NestJS, debes seguir los siguientes pasos:

1. Abre la terminal o consola en tu sistema operativo.
2. Navega hasta la ubicación de tu proyecto NestJS.
3. Escribe el siguiente comando y presiona Enter:

![[Pasted image 20230731101322.png]]

4. Espera a que el servidor se levante correctamente, y ya podrás acceder a tu aplicación NestJS en el navegador web a través de la dirección [http://localhost:3000/](http://localhost:3000/) o la que hayas especificado en la configuración del servidor.</p>


<h1>Corregir cats</h1>
<p>import { Controller, Get } from '@nestjs/common';
@Controller('cats')
export class CatsController {
@Get()
findAll(): string{
return 'This action return all cats'
}
}</p>

<h1>Postman</h1>
Postman es una herramienta de software que se utiliza para probar, desarrollar y documentar APIs. Permite a los desarrolladores realizar peticiones HTTP a cualquier API de manera sencilla, y de esta forma, testear sus aplicaciones. Además, Postman permite colaborar en equipo en la creación y mantenimiento de colecciones de APIs, lo que mejora la productividad y la eficiencia en el desarrollo de proyectos de software que involucran el uso de diferentes servicios web. En resumen, Postman es una plataforma muy útil para los desarrolladores que trabajan con APIs y servicios web .
