public class Tanishq {

    private final String role = "Full Stack Developer";

    private final String[] skills = {
        "Java",
        "Python",
        "JavaScript",
        "React",
        "Node.js",
        "Express.js",
        "MongoDB",
        "MySQL"
    };

    private final String[] interests = {
        "System Design",
        "Scalable Architecture",
        "Backend Engineering",
        "Clean Code",
        "Problem Solving"
    };

    private final String currentlyBuilding =
        "Modern Full Stack Applications";

    private final String currentlyLearning =
        "System Design, Cloud & Performance Optimization";

    private final String availableFor =
        "Internships & Full-Time Opportunities";

    // Featured Projects

    private final Project craftMyFolio = new Project(
        "CraftMyFolio",
        "AI-powered Portfolio Builder",
        "React • Node.js • Express.js • MongoDB • Gemini API"
    );

    private final Project urlShortener = new Project(
        "URL Shortener",
        "Scalable URL shortening service with analytics",
        "Node.js • Express.js • MongoDB"
    );

    private final Project[] featuredProjects = {
        craftMyFolio,
        urlShortener
    };

    public void code() {
        while (true) {
            learn();
            build();
            improve();
            repeat();
        }
    }

    record Project(
        String name,
        String description,
        String techStack
    ) {}
}
