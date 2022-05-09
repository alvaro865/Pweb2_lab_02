<div align="center">
<table>
    <theader>
        <tr>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/epis.png?raw=true" alt="EPIS" style="width:50%; height:auto"/></td>
            <th>
                <span style="font-weight:bold;">UNIVERSIDAD NACIONAL DE SAN AGUSTIN</span><br />
                <span style="font-weight:bold;">FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS</span><br />
                <span style="font-weight:bold;">ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMAS</span>
            </th>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/abet.png?raw=true" alt="ABET" style="width:50%; height:auto"/></td>
        </tr>
    </theader>
    <tbody>
        <tr><td colspan="3"><span style="font-weight:bold;">Formato</span>: Guía de Práctica de Laboratorio / Talleres / Centros de Simulación</td></tr>
        <tr><td><span style="font-weight:bold;">Aprobación</span>:  2022/03/01</td><td><span style="font-weight:bold;">Código</span>: GUIA-PRLD-001</td><td><span style="font-weight:bold;">Página</span>: 1</td></tr>
    </tbody>
</table>
</div>

<div align="center">
<span style="font-weight:bold;">GUÍA DE LABORATORIO</span><br />
<span>(formato docente)</span>
</div>


<table>
<theader>
<tr><th colspan="6">INFORMACIÓN BÁSICA</th></tr>
</theader>
<tbody>
<tr><td>ASIGNATURA:</td><td colspan="5">Programación Web 2</td></tr>
<tr><td>TÍTULO DE LA PRÁCTICA:</td><td colspan="5">Git - GitHub</td></tr>
<tr>
<td>NÚMERO DE PRÁCTICA:</td><td>01</td><td>AÑO LECTIVO:</td><td>2022 A</td><td>NRO. SEMESTRE:</td><td>III</td>
</tr>
<tr>
<td>FECHA PRESENTACION::</td><td>25-Abr-2022</td><td>HORA DE PRESENTACION:</td><td>29-Abr-2022</td><td></td><td></td>
</tr>
<tr>
<td>INTEGRANTES::</td><td>
<ul>
<li>Suasaca Pacompia Alvaro Gustavo</li>
<li>el que sigue</li>
</ul>
<td>NOTA</td><td></td><td></td><td></td>
</td>
</tr>
<tr><td colspan="6">DOCENTES:
<ul>
<li>Richart Smith Escobedo Quispe (rescobedoq@unsa.edu.pe)</li>
</ul>
</td>
</<tr>
</tdbody>
</table>


# SOLUCION Y RESULTADOS

## I. SOLUCION DE EJERCICIOS/PROBLEMAS

- Solucion del Ejercicio 1 al 5:
  https://github.com/alvaro865/Pweb2_lab_02
- Solucion al Ejericio 6:
  https://flipgrid.com/837b6633

## II. SOLUCION DEL CUESTIONARIO

 - ¿Como se pueden resolver los warnings?
    Siguiendo las respuestas de stackoverflow nos da algunas opciones como el de usar foreach pues el solo usar for sin un tamaño predefinido nos puede mandar 
    problemas, otra opcion que nos indican es el de preestablecer un tamaño al array antes de usar el for, y una mas es el de usar la herramienta map y debemos
    de indicar que cuando se usa esta herramienta las funciones son en flecha.
    
 - ¿Se puede resolver usando map?¿Como? 
    Hice algunos cambios en la function como por ejemplo:
    function myFunction(n, min, max) {
	let a = new Array(n);
    let b = a.map(function(n){return n*(Math.random() * (max -min) +min)});
    return b[1];
    }
    Pero cuando lo ejecuto me manda indefinido por lo que aun no pude resolverlo con map

## III. CONCLUSIONES


