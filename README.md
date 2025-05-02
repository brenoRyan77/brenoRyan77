```java
public class BrenoRyan {

    private String cargo = "Desenvolvedor FullStack";
    private String empresa = "Fóton";
    private String linguagemPrincipal = "Java";
    private String frameworkBackend = "Spring Boot";
    private String frameworkFrontend = "Angular";

    public static void main(String[] args) {
        BrenoRyan breno = new BrenoRyan();
        breno.sobreMim();
        breno.conectar();
    }

    void sobreMim() {
        System.out.println("🛠 " + cargo + " na " + empresa);
        System.out.println("💻 Backend com " + linguagemPrincipal + " e " + frameworkBackend);
        System.out.println("🌐 Frontend com " + frameworkFrontend);
    }

    void conectar() {
        System.out.println("🔗 LinkedIn: https://www.linkedin.com/in/breno-ryan-09a45b220/");
    }
}
