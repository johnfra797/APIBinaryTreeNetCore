# APIBinaryTree!
El API escucha por el puerto 55600, esta hecha en NetCore y tiene los siguientes endpoints

 - /api/binarytree/crear (Simplemente crea un arbol binario)
 - /api/binarytree/LowestCommonAncestor?key1=24&key2=78 (Este método nos ayuda a buscar los padres comunes entre dos nodos recibe dos parametros, si no encuentra nada retorna 0)
 - /api/binarytree/Ancestor?key1=24 (Este metodo nos ayuda a buscar el padre de un nodo especifico, si no encuentra nada retorna 0)
