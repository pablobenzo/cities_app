EL proyecto esta realizado en Swift con librerias SwiftUI y UIKit, el patron de diseño elejido para el proyecto es MVVM (ModelView-ViewModel)
debido al pequeño tamaño del mismo. Para solventar la sobrecarga de memoria se realiza una carga constante de la List a traves de una funcion
a medida que se va realizando scroll por la ScrollView, asi impedimos un Memory Leak y crasheo de la aplicacion.
Utilizamos MapKit para utilizacion de mapas inApp.
