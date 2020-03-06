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