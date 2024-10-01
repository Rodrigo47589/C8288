´´´
class UsuarioBase{
    name: String;
    correo: String;

}

//Para aplicar herencias,se utiliza el "extends" 
class Admin extends UsuarioBase {
    gestionarUsuario():void {
        
    }


}


class SuperAdmin extends Admin {


}

class GestorDePermisos<T extends UsuarioBase> {
    
} 
 '''

