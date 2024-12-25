# AI (LIZE) FOR ASHISH MEENA

public class AI_Lize {
    private String name;

    public AI_Lize(String name) {
        this.name = name;
    }

    public void greet() {
        System.out.println("Hello, " + name + "! Welcome to the AI Lize program.");
    }

    public static void main(String[] args) {
        AI_Lize aiLize = new AI_Lize("Ashish Meena");
        aiLize.greet();
    }
}
