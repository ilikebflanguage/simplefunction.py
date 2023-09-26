# simplefunction.py
#super simple feel free to ask to use
def show_cars(cars , message):
    print(message)
    for car in cars:
        print(car.title())
cars = ['toyota hilux' , 'ford mustang' , 'dodge challenger']
cars.sort()
show_cars(cars, "\nHello everyone we have these cars available!")
