
# **Acerca de Mi**

## _Don Santiago_

Hola a todos mi nombre es Brayan Santiago, soy estudiante de la escuela de ingenieria de sistemas y administracion de empresas, tengo 21 años, me gusta leer todo tipo de temas, toca guitarra, quiero aprender a toca el ukelele.\
Mi autor favorito es Huxley, recomiendo mucho el libro _Un mundo Feliz_ y actualmente trabajo en el programa mas grande de Bogota y parque lineal mas grande del mundo que es **CICLOVIA** 

### Escuela Colombiana de Ingenieria
La escuela colombiana de Ingenieria es la universidad donde estoy realizando mis dos primeros pregrados, en esta pagina puede encontrar toda la informacion acerca de esta [Escuela Colombiana de Ingenieria Julio Garavito] (https://www.escuelaing.edu.co/es/)

![Foto Escuela](https://cloudfront-us-east-1.images.arcpublishing.com/elespectador/TKGDUH4SQJG2BKD5RKHHKWXFRQ.jpg)


El Codigo que nunca olvidaremos `print ("Hello World")`

y algo de codigo complejo:

```
package presentacion;

import aplicacion.*;
import java.awt.Color;
import java.awt.Graphics;
import javax.swing.JPanel;
import javax.swing.*;
import java.awt.*;
import java.lang.Thread;
import java.io.*;
import java.awt.image.*;
import javax.imageio.ImageIO;
/**
*		------------------------------------------------------------------------
*		------------------------ PONG ------------------------------------------
*		------------------------------------------------------------------------
*
* CLASE: Primera pantalla que se muestra en el juego Pong, en donde se da inicio al juego
		 alli se muestra la imagen principal del juego para poder iniciar
*
* @author: Santiago Buitrago
* @author: Brayan Macias
*
* @version 4.5 Final	
*/

public class pantallaInicioPong extends JPanel{
	
	private Image fondo;
	
	/** 
		Contructor: Primera pantalla que se muestra en el juego Pong, en donde se da inicio al juego
		alli se muestra la imagen principal del juego para poder iniciar
	*/
	public pantallaInicioPong(){
		setPreferredSize(new Dimension(1500,1000));  
		setBackground(Color.white);
		prepareElementos();
		setLayout(null);
	}
	
	/**
		Encargado de preparar los elementos necesarios para mostrar la pantalla de Inicio correctamente
		como lo es el fondo, el tamaño entre otros
	*/
	public void prepareElementos(){
		fondo=(new ImageIcon(getClass().getResource("/configuracion/ComponentesMultimedia/FondosInterfaz/Fondo7.gif")).getImage());
		Dimension size = new Dimension(1500,1000);
		setPreferredSize(size);
		setMinimumSize(size);
		setMaximumSize(size);
		setSize(size);
		setOpaque(false);
	} 
	
	/**
		Metodo Sobre escrito, para poder visualizar lo que se desea pintar en la pantalla 
		inicial del juego
	*/
	@Override
    public void paintComponent(Graphics g) {
		super.paintComponent(g);
		g.drawImage(fondo,0,0,1500,1000,this);
    }
}
```

###	CICLOVIA
[Ciclovia][1] es el parque lineal mas grande del mundo
 
 ![](https://www.eltiempo.com/files/article_main/uploads/2019/12/13/5df37c717c0ba.jpeg) 
	
#### Hobbys

* Montar Bicicleta
* Entrenar GYM y Crosfit
* Tocar guitarra
* Leer
* Bailar y Tomar MUCHO
* Compartir con mis seres queridos 
* Escribir 

#### Pasos para ser Feliz

1. No complicarse con estres
5. Disfrutar cada segundo 
8. Sonreir
10. Hacer lo que te llena de satisfaccion
15. Simplemente **_VIVIR_**

##### Imagenes

![](https://github.com/DonSantiagoS/LAB1CVDS/blob/master/Santiago/Imagenes/Tutorial.PNG) "Tutorial Markdown"
![](https://github.com/DonSantiagoS/LAB1CVDS/blob/master/Santiago/Imagenes/Numero1.PNG) "Tutorial Markdown"
![](https://github.com/DonSantiagoS/LAB1CVDS/blob/master/Santiago/Imagenes/Numero2.PNG) "Tutorial Markdown"


[1]:https://www.idrd.gov.co/ciclovia-bogotana#overlay-context=

