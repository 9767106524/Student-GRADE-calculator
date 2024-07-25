public class StudentGradingSystem {
    public static void main(String[] args) {
        int marks = 85; // Assume the marks are out of 100
        char grade = calculateGrade(marks);
        System.out.println("The grade is: " + grade);
    }

    public static char calculateGrade(int marks) {
        if (marks >= 90) {
            return 'A';
        } else if (marks >= 80) {
            return 'B';
        } else if (marks >= 70) {
            return 'C';
        } else if (marks >= 60) {
            return 'D';
        } else {
            return 'F';
        }
    }
}
