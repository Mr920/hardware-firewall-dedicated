---

copyright:
  years: 2017
lastupdated: "2018-11-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:download: .download}

# Ignorar las reglas de cortafuegos

Para ignorar las reglas de cortafuegos:

1. En el navegador, abra el [Portal de clientes ![Icono de enlace externo](../../icons/launch-glyph.svg "Icono ce enlace externo")](https://control.softlayer.com/){: new_window} e inicie sesión en su cuenta.
2. En la navegación del Portal de clientes, vaya a **Red > Gestión de IP > VLAN** y pulse el dispositivo de cortafuegos que desea ignorar.
3. En la página **Detalles de dispositivo**, en el separador **Configuración**, utilice el menú desplegable **Acciones** para seleccionar **Definir omisión de ruta** o pulse **Ignorar reglas** en la sección **Estado:**. 

	Otra opción es sortear el cortafuegos pulsando **Direccionar alrededor**. En cualquier caso, obtendrá un diálogo de confirmación. Pulse **Sí** para confirmar la acción. La omisión de las reglas tarda aproximadamente dos minutos en aplicarse. En la modalidad de omisión, el "Estado" será "Direccionando ALREDEDOR del cortafuegos".

## Habilitar las reglas de nuevo

Para volver a habilitar las reglas, siga las instrucciones anteriores para llegar al separador **Configuración** del dispositivo, pulse el menú desplegable **Acciones** y elija **Definir omisión de ruta**. Obtendrá un diálogo de confirmación. Pulse **Sí** para confirmar la acción. El "estado" cambiará de nuevo a "Direccionando A TRAVÉS del cortafuegos" pasados dos minutos.
