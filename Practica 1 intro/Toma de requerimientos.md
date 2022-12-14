# Toma de Requerimientos

-------------------------------------------------------------------------------------------------------------------------------------------------------------

**Caso: Abogabot**
Descripción:

1- Es un despacho de abogados que quiere automatizar las demandas de sus clientes, esto lo harán a traves de una página web llenando un formulario.
<br/>
2- Al momento de llenar el formulario se manda al proceso de pago para finalizar la transacción.
<br/>
3- Para dar seguimiento a su demanda, el cliente crea una cuenta en la plataforma y verá el seguimiento de cada una de las actualizaciones del proceso legal.
<br/>
4- El administrador del sitio recbe la notificación de una nueva demanda y con los datos llenados del formulario se crea automaticamente el documento legal en formato word para empezar el proceso.
<br/>
5- El administrador recibe el pago y debe de ser capaz de verlo en un dashboard para ver la cantidad de ingresos recibidos.
<br/>
6- El administrador actualiza el proceso de la demanda y agrega comentarios en cada paso del proceso.
<br/>
7- Al usuario le llegan correos de notificación para saber el avance de su proceso.
<br/>
8- La página debe de ser responsive para poderla ver desde el celular.
<br/>
9- La preferncia de colores del cliente es azul marino y blanco, pero acepta propuestas.

-------------------------------------------------------------------------------------------------------------------------------------------------------------


## 1. Descripción General del Requerimiento

<table>
    <tr>
        <th>Proyecto: </th>
        <td>Abogabot</td>
    </tr>
    <tr>
        <th>Nombre Requerimiento: </th>
        <td>-</td>
    </tr>
    <tr>
        <th>Fecha Solicitud: </th>
        <td>07/11/2022</td>
    </tr>
    <tr>
        <th>Responsable(s) Solicitud: </th>
        <td>Launch-X</td>
    </tr>
    <tr>
        <th>Dependencia(s) Solicitante: </th>
        <td>Launch-X</td>
    </tr>
    <tr>
        <th>Responsable Funcional designado por el equipo de desarrollo de software: </th>
        <td>Kevin Correa</td>
    </tr>
</table>

## 2. Fase de Formalización

<table>
    <tr>
        <th>Descripción de la solicitud</th>
    </tr>
    <tr>
        <td><b>Usuario Solicitante</b></td>
    </tr>
    <tr>
        <td>
            <p>
                <li>Es un despacho de abogados que quiere automatizar las demandas de sus clientes, esto lo harán a través de una página web llenando un formulario.</li>
                <li>Al momento de llenar el formulario se manda al proceso de pago para finalizar la transacción.</li>
                <li>Para dar seguimiento a su demanda, el cliente crea una cuenta en la plataforma y verá el seguimiento de cada una de las actualizaciones del proceso legal.</li>
                <li>El administrador del sitio recibe la notificación de una nueva demanda y con los datos llenados del formulario se crea automaticamente el documento legal en formato word para empezar el proceso.</li>
                <li>El administrador recibe el pago y debe de ser capaz de verlo en un dashboard para ver la cantidad de ingresos recibidos.</li>
                <li>El administrador actualiza el proceso de la demanda y agrega comentarios en cada paso del proceso.</li>
                <li>Al usuario le llegan correos de notificación para saber el avance de su proceso.</li>
                <li>La página debe ser responsive para poderla ver desde el celular.</li>
                <li>La preferencia de colores del cliente es azul marino y blanco, pero acepta propuestas.</li>
            </p>
        </td>
    </tr>
    <tr>
</table>

## 3. Análisis de requisitos y requerimientos

<table>
    <tr>
        <td><b>Fecha Inicio</b></td>
        <td>07/12/2022</td>
        <td><b>Fecha Final</b></td>
        <td>13/12/2022</td>
    </tr>
    <tr>
        <td colspan=4><b>Modelamiento de Negocio</b></td>
    </tr>
    <tr>
        <td colspan=4>
            <!-- <img src=""> -->
            ---
            <p>(Diagrama del modelamiento del negocio)</p>
        </td>
    </tr>
    <tr>
        <td colspan=4><b>Términos de Referencia</b></td>
    </tr>
    <tr>
        <td colspan=1><b>Alcance de la solución</b></td>
        <td colspan=3>
            <p>La solución incluye del desarrollo de una plataforma web que permita la automatización de la comunicación entre el cliente y los abogados, la plataforma permite generar y dar seguimiento a una demanda. La plataforma permite la realización de cobros por parte del despacho jurídico y cobro hacia los clientes.</p>
            <p>La plataforma permite la creación de cuentas y administra inicios de sesión. Para los administradores del sitio (abogados) permite la generación de documentos en formato Word los cuales sirven como plantillas de inicio para el desarrollo del caso. El cliente podrá dar seguimiento a su caso desde la plataforma y ver los detalles de cada paso del proceso legal.</p>
            <p>La plataforma debe considerar el envío de <i>e-mails</i> para notificar al cliente actualizaciones del caso.</p>
        </td>
    </tr>
    <tr>
        <td colspan=1><b>Requerimientos Funcionales y criterios de aceptación</b></td>
        <td colspan=3>
            <p>Se espera que la plataforma cuente con una interfaz de usuario llamativa e intuitiva, que sea sencilla de utilizar tanto para clientes como administradores del sitio. Se requiere que la plataforma sea responsive para poderla visualizar desde dispositivos móviles. Los colores preferidos por el cliente son azul marino y blanco, pero está dispuesto a ver propuestas.
            </p>
            <p>Se espera que la plataforma implemente WebSockets para realizar cambios y comunicación en tiempo real. Se debe considerar que la plataforma de igual forma puede notificar sobre nuevos casos y deberá actualizar el dashboard en tiempo real.</p>
            <p>Se debe considerar la implementación de servicios SMTP para el envío de <i>e-mails</i> a los clientes.</p>
            <p>El despliegue de la aplicación debe ser mediante los servicios de Azure.</p>
        </td>
    </tr>
    <tr>
        <td colspan=1><b>Requerimientos no Funcionales y de calidad </b></td>
        <td colspan=3>
            <p>La plataforma debe implementar estrategias de protección de datos personales ya que es información que debe ser confidencial.</p>
            <p>Se deben implementar medidas de seguridad de información para evitar que caiga en manos de personas malintencionadas.</p>
        </td>
    </tr>
    <tr>
        <td colspan=1><b>Interesados en la solución</b></td>
        <td colspan=3>
            <table>
                <tr>
                    <th>Nombre/Rol/Perfil</th>
                    <th>Descripción</th>
                </tr>
                <tr>
                    <td>Cliente</td>
                    <td>El perfil del cliente se beneficiará de la automatización de la comunicación ya que de esta forma sin necesidad de intermediarios podrá conocer en qué parte del proceso se encuentra la demanda que desde la plataforma generó.</td>
                </tr>
                <tr>
                    <td>Abogados</td>
                    <td>Los abogados se benefician de la plataforma ya que pueden notificar a los clientes progreso en el caso. Además podrán consultan los detalles de la demanda de una forma organizada y beneficiarse del uso de los documentos <i>Word</i> generados para agilizar el tiempo de resolución de los casos.</td>
                </tr>
            </table>
        </td>
    </tr>
    <tr>
        <td colspan=1><b>Precondiciones</b></td>
        <td colspan=3>
            <li>El cliente deberá aprobar los requerimientos.</li>
            <li>Se deberá proporcionar el 50% del presupuesto para poder iniciar el desarrollo de la plataforma.</li>
        </td>
    </tr>
    <tr>
        <td colspan=1><b>Requisitos Técnicos</b></td>
        <td colspan=3>
            <table>
                <tr>
                    <th>Tipo de desarrollo: </th>
                    <td>
                        <input type="checkbox" name="web-serv" checked disabled>
                        <label for="web-serv">WebApp</label>
                    </td>
                </tr>
                <tr>
                    <th>Base de datos</th>
                    <td>
                        <input type="checkbox" name="database" checked disabled>
                        <label for="database">MySQL</label>
                    </td>
                </tr>
                <tr>
                    <th>Lenguaje</th>
                    <td>
                        <input type="checkbox" name="database" checked disabled>
                        <label for="database">HTML</label>
                        <input type="checkbox" name="database" checked disabled>
                        <label for="database">CSS</label>
                        <input type="checkbox" name="database" checked disabled>
                        <label for="database">JavaScript (NodeJS)</label>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
    <tr>
        <td colspan=1><b>Viabilidad Técnica</b></td>
        <td colspan=3>
            Luego de adelantado el análisis de los requisitos y requerimientos es proponer una solución técnica para esta solicitud: <b>SI (X)</b> NO ().
        </td>
    </tr>
</table>
