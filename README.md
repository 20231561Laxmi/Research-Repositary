# Research-Repositary
Assignment3
# Single Responsibilty Principle:The single responsibility principle is one of the SOLID principles of object-oriented programming, and it states that the class should have only one reason to change. in other words class should have one responsibility or job.
class Order:
    def __init__(self,order_id,customer):
        self.order_id=order_id
        self.customer=customer
        self.order_items=[]
    
    def add_item(self,product,quantity):
        item= orderitem(product,quantity)
        self.order_item.append(item)
    
    def calculate_total(self):
        total=0
        for item in self.orer_items:
            total+=item.calculate_item_total()
            return total

 # open and closed principle:The open and close is another SOLID principle, which states that software entitles(class,modules,functions,etc) should be open for extension but closed for modification.In other words, you should be able to add new functionality to a system without altering existing code.
    # Different shapes 
    class Rectangleshape:
        def __init__(self,width, height):
            self.width=width
            self.height=height

        def area(self):
            return self.width* self.height

    class circleshape:
        def __init__(self,radius):
            self.radius=radius

        def area(self):
            return 3.14159* self.radius*self.radius

        #function that calculates the total area of shapes 
        def calculate_total _area(shape):
        total_area=0
        for shape in shapes:
        total_area+=shape.area()
        return total_area

# Example usuage
rectangle1=Rectangle(5,10)
circle1= Circle(4)
shapes= [rectangle,circle1]

total_area= calculate _total_area(shapes)
print(f"Total Area: {total_area}")



# DRY principle helps to save time while avoiding to have creat same code repedatedly for a same result.
class Circle:
    def __init__(self, radius):
        self.radius = radius
    
    def area(self):
        return 3.14159 * self.radius ** 2

class Area:
    def run(self):
        circle = Circle(5)
        circle_area = Circle.area(circle)
        print(circle_area)

area= Area()
area.run()
# below is a example of not using DRY pricple, if you want area of 20 circles you can use DRY princple and get the result at once intead having to write 20 lines. 
circle1= 3.14159 * 3 ** 2
print(circle1)
circle2= 3.14159 * 5 ** 2
print(circle2)
        






    



    



