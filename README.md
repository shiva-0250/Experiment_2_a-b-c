# Experiment_2a
## Title:impliment ofmechanism of class
## course code:
```
java

class Square {
    int area(int side) {
        return side * side;
    }
    int perimeter(int side) {
        return 4 * side;
    }
    public static void main(String[] args) {
        Square sq = new Square();
        int side = 5;
        int area = sq.area(side);
        int perimeter = sq.perimeter(side);
        System.out.println("Side of square: " + side);
        System.out.println("Area of square: " + area);
        System.out.println("Perimeter of square: " + perimeter);
    }
}
```
#output
![output of square](square.png)
