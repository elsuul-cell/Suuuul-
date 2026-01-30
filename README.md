public class Tecnm {
    private int[] numeros;

    // Constructor que recibe un arreglo de enteros
    public Tecnm(int[] numeros) {
        this.numeros = numeros;
    }

    // Método para obtener el arreglo
    public int[] getNumeros() {
        return numeros;
    }

    // Método para establecer el arreglo
    public void setNumeros(int[] numeros) {
        this.numeros = numeros;
    }

    // Método para mostrar los números
    public void mostrarNumeros() {
        System.out.print("Números: ");
        for (int num : numeros) {
            System.out.print(num + " ");
        }
        System.out.println();
    }

    // Método principal para probar la clase
    public static void main(String[] args) {
        int[] arreglo = {10, 20, 30, 40, 50};
        Tecnm tec = new Tecnm(arreglo);
        tec.mostrarNumeros();
    }
}
