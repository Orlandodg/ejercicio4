# ejercicio4
empleado
public class Empleado2 {

    
public class Empleados {
    private String nombre;
    private String paterno;
    private String materno;
    private double salarioMensual;
    
    public Empleados(String nombre, String paterno, String materno, double salarioMensual) {
        this.nombre = nombre;
        this.paterno = paterno;
        this.materno = materno;
        this.salarioMensual = salarioMensual;
    }
    
    public String getNombre() {
        return nombre;
    }
    
    public void setNombre(String nombre) {
        this.nombre = nombre;
    }
    
    public String getPaterno() {
        return paterno;
    }
    
    public void setPaterno(String paterno) {
        this.paterno = paterno;
    }
    
    public String getMaterno() {
        return materno;
    }
    
    public void setMaterno(String materno) {
        this.materno = materno;
    }
    
    public double getSalarioMensual() {
        return salarioMensual;
    }
    
    public void setSalarioMensual(double salarioMensual) {
        if (salarioMensual <=0){
            System.out.print("0");
        } else{
            this.salarioMensual = salarioMensual;
        }
    }
    
    public Empleados() {
    }
    
    public double obtenerSalarioAnual(){
        double sa;
        
        sa= (salarioMensual * 12);
        System.out.println("El salario anual del empleado es: ");
        return sa;
    }
    public double obtenerAumento(){
        double am,saa; 
        
        am=(salarioMensual *.10);
        
        saa= (salarioMensual +am)*12;
        
        System.out.println("El salario anual del empleado con el aumento del 10% es: ");
        return saa;
    }

}
    }
    

