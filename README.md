## 1.
* **Class<T>**
  * **newInstance()** da classe Class<T> foi descontinuado a partir do JDK 9, pois não verificava Exceptions checked.
  * **Constructor<T>**
    * **newInstance()** da classe Constructor<T> válida Exceptions checked.
    * **getConstructor()** recupara construtor **público** com ou sem parâmetro, é só informar na chamda.
    * **getConstructors()** recuperar todos construtores publicos.
    * **getDeclaredConstructor()** recupara construtor **privado** com ou sem parâmetro, é só informar na chamda.
    * **getDeclaredConstructors()** recupera todos construtores públicos e privados.
