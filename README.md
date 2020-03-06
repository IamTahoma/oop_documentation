# Document OOP on Dart/Flutter

A repository to document everything about object-oriented programming. For me of the future.

### Class
Classes are molds that contain attributes and methods.

    class Cube {
        //Atributes
        String name;
        Color color;
    }

### Methods
subroutine defined in a class, for its construction.

    class Cube {
        //Atributes
        String name;
        Color color;
        
        //Methods
        Cubo({
            this.name,
            this.color
        });
    }

### Heredity
Lets inherit objects that already exist for reuse.

    Class Build extends Cube {
        //heredity
        List cubesForConstruction = [
            Cube(
                name: 'Granite',
                color: 'green'
            ),
            Cube(
                name: 'Iron',
                color: 'gray'
            ),
        ];
        
        Build buildHouse(List cubesForConstruction){
            "....."
        };
    }

### Encapsulation
It is used to define which functions or methods are private or public. Attributes, functions or private methods. It can only be used within the same class.

    Class Build extends Cube {
        //Atributes privates and publics
        String windows // publics
        String door // public
        String _keys //private
        //heredity
        List cubesForConstruction = [
            Cube(
                name: 'Granite',
                color: 'green'
            ),
            Cube(
                name: 'Iron',
                color: 'gray'
            ),
        ];
        
        //Method or Function Public
        Build buildHouse(List cubesForConstruction){
            String copyKey = _getkeyfromHouse();
            "......."
        };
        //Method or Function Private
        String _getKeyFromHouse(){
            return _key;
        }
    }