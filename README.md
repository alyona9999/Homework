public class HomeWorkApp {
    // объявляем метод main
    public static void main (String[] args) {
        printThreeWords();
        checkSumSign();
        printColor();
        compareNumbers();
    }
    // объявляем метод printThreeWords
    public static void printThreeWords() {
            System.out.println("Orange");
            System.out.println("Banana");
            System.out.println("Apple");
    }
    public static void checkSumSign() {
        int a = -40;
        int b = 30;
        int c = a + b;
        if ( c >= 0) {
            System.out.println("Сумма положительная");
        } else {
           System.out.println("Сумма отрицательная");
        }

    }
    public static void printColor() {
        int value = 101;
        if (value <= 0) {
            System.out.println("Красный");
        } else if (value <= 100) {
            System.out.println("Желтый");
        } else {
            System.out.println("Зеленый");
        }
    }
    public static void compareNumbers() {
        int a = -20;
        int b = -50;
        if ( a >= b) {
            System.out.println("a >= b");
        } else {
            System.out.println("a < b");
        }
    }
}
