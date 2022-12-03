class Animal{
    private var num_of_leg:Int
    private var age:Int
    private var name:String
    public init(Num_of_leg:Int,Age:Int,Name:String){
        num_of_leg = Num_of_leg
        age = Age
        name = Name
    }
    public func sleep(){
        print("mewzzzzzzzzzz")
    }
    public func eat(){
        print("emmmm....yummy!")
    }
}
class Dog : Animal{
    public var dogname:String
    public init(Dogname:String){
        dogname = Dogname
        super.init(Num_of_leg: 4,Age: 5,Name: "Dog")
    }
}
class Human : Animal{
    var name : String
    var dogname : String
    var dog = Dog(Dogname: "NULL")
    public func do_homework(){
        print("fewk off😅")
    }
    public func go_angry(){
        print("cnm")
    }
    public func speak(){
        print("Hello~")
    }
    public init(name:String,dogname:String){
        self.name = name
        self.dogname = dogname
        var dog = Dog(Dogname: dogname)
        self.dog = dog
        super.init(Num_of_leg: 2, Age: 18,Name: "Human")
    }
    
}
var a_human = Human(name: "ROBIN",dogname: "Corgi")
print(a_human.dog.dogname)
a_human.speak()

import Darwin
protocol Calculator{
    var perimeter: Double {get}
    var square: Double {get}
}
class Triangle:Calculator{
    var a:Double
    var b:Double
    var c:Double
    init(a:Double,b:Double,c:Double){
        self.a = a
        self.b = b 
        self.c = c
    }
    var perimeter: Double{
        return a+b+c;
    }
    var square: Double{
        let p = 0.5*(a+b+c)
        return sqrt(p*(p-a)*(p-b)*(p-c))
    }
}
var triangle = Triangle(a: 3,b: 4,c: 5)
print("三角形周长为："+String(triangle.perimeter))
print("三角形面积为："+String(triangle.square))
class Rectangle:Calculator{
    var a: Double
    var b: Double
    init(a :Double,b: Double){
        self.a = a
        self.b = b
    }
    var perimeter: Double{
        return a+b+a+b
    }
    var square: Double{
        return a*b
    }
}
var rectangle = Rectangle(a: 3, b: 4)
print("长方形周长为："+String(rectangle.perimeter))
print("长方形面积为："+String(rectangle.square))
class Square:Calculator{
    var a: Double
    init(a :Double){
        self.a = a
    }
    var perimeter: Double{
        return a*4
    }
    var square: Double{
        return a*a
    }
}
var square = Square(a: 7)
print("正方形周长为："+String(square.perimeter))
print("正方形面积为："+String(square.square))
