# Research-Repositary
Assignment3
#Single Responsibilty Principle:The single responsibility principle is one of the SOLID principles of object-oriented programming, and it states that the class should have only one reason to change. in other words class should have one responsibility or job.
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


    # Total area of shapes:
    def calculate_total_area
        



    



