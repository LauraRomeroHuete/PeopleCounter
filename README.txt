Guia d’instal·lació

A continuació es detallaran els passos a realitzar per poder instal·lar els programes i llibreries necessàries per poder executar l’aplicació realitzada:
	
	01.	Descarregar i instal·lar Visual Studio 2019 [13].
	02.	Descarregar el .zip del codi del projecte.
	03.	Descomprimir el .zip.
	04.	Obrir el projecte des del Visual Studio 2019.
	05.	Descarregar l’openCV 3.4 [23], 
	06.	Afegir les llibreries d’OpenCV al projecte:
		a.	Obrim les propietats del projecte
		b.	En l’apartat VC++ Directories > Include Directories afegim el path “XXX/opencv/build/include”.
		c.	En l’apartat VC++ Directories > Library Directories afegim el path “XXX/opencv/build/x64/VC14/lib”.
		d.	En l’apartat Linker > Additional Dependencies afegim el nom del fitxer “opencv_world3412d.lib” que trobem dins del path de l’apartat c.
	07.	Executem el projecte.
