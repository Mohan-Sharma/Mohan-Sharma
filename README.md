    public class MohanSharma {
    
        public static void main(String[] args) {
            MohanSharma human = new MohanSharma();
            human.tellMeAboutYourself();
    
            Profession profession = new Profession();
            profession.currentProfession();
            profession.pastProfessions();
            profession.technologyAndTools();
    
            Education education = new Education();
            education.highestEducation();;
            education.otherEducation();
        }
    
        private void tellMeAboutYourself() {
            System.out.println("*********************************************************************");
            System.out.println("Hola :wave:, my name is Mohan Sharma.");
            System.out.println("I am a Passionate Learner | Erudite | Inquisitive | Loving Brother & Son.");
            System.out.println("I Enjoy watching Sci-fi movies and tv series, curious about the vast emptiness of the universe, love playing soccer. Lastly, waiting for SpaceX to deliver human to Mars.");
            System.out.println("*********************************************************************");
        }
    }
    
    class Profession {
    
        public void currentProfession() {
            System.out.println("*********************************************************************");
            System.out.println("Current position : Senior SAP Commerce Cloud Consultant at SAP Labs.");
            System.out.printf("From Nov 4, 2018 to %s.%n", java.time.LocalDate.now().format(java.time.format.DateTimeFormatter.ofPattern("MMM d, yyyy")));
            System.out.println("*********************************************************************");
        }
    
        public void pastProfessions() {
            System.out.println("*********************************************************************");
            System.out.println("Past Position : SAP Commerce Cloud developer at Landmark Group.");
            System.out.println("From Apr 3, 2017 to Oct 23, 2018.");
            System.out.println("Past Position : Software Engineer at NthDimenzion Solutions.");
            System.out.println("From Aug 16, 2013 to Mar 31, 2017.");
            System.out.println("*********************************************************************");
        }
    
        public void technologyAndTools() {
            System.out.println("*********************************************************************");
            System.out.println("Expertise in : Java, Spring, Spring boot, Hibernate, SAP Commerce Cloud.");
            System.out.println("Well versed with : SAFe, Agile, CI/CD methodologies and tools.");
            System.out.println("Enjoy working on IntelliJ Idea.");
            System.out.println("Worth mentioning other skills: JavaScript, Maven, Cloud Foundry, Git, Spring cloud, Spring Data, Spring security.");
            System.out.println("Last but not the least skill: Reading all the docs/specs for developing a new feature using a new API but fixing the bug using Stackoverflow :p");
            System.out.println("*********************************************************************");
        }
    }
    
    class Education {
    
        public void highestEducation() {
            System.out.println("*********************************************************************");
            System.out.println("Highest Education: Bachelor of Technology in Computer Science.");
            System.out.println("GPA: 7.9");
            System.out.println("*********************************************************************");
        }
    
        public void otherEducation() {
            System.out.println("*********************************************************************");
            System.out.println("Other Education: Intermediate in Science stream.");
            System.out.println("GPA: 7.3");
            System.out.println("Other Education: High School.");
            System.out.println("GPA: 8.3");
            System.out.println("*********************************************************************");
        }
    }
