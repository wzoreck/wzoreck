# About me

```java
import java.util.Arrays;

public class Dev {
	public static String name = "Daniel Wzoreck";
	public static String current_job = "SENAI Institute of Innovation in Embedded Systems";
	public static String position = "Junior - Web Developer";
	public static String linkedIn = "https://www.linkedin.com/in/daniel-wzoreck-206384197";
	public static String[] arrayOfKnowledge = new String[] {
		"Python", "Django", "FastAPI",
		"Java", "JS", "React",
		"HTML", "CSS", "Bootstrap",
		"SQL", "UML", "Docker", "Git",
		"A little bit of other things..."
	};

	public static String presentation() {
		return "Hello! My name is " + name + ", I work at the " + current_job + " as a " +
				position + ",\nif you want to follow me on LinkedIn, use this link: " + linkedIn +
				"\nLately I've been working with these technologies: " + Arrays.toString(arrayOfKnowledge);
	}
}

```
