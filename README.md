[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=3320306&assignment_repo_type=AssignmentRepo)
import javax.swing.JOptionPane;
public class Name
{
public static void main(String[] args)
{
String first = JOptionPane.showInputDialog("What is your first name");
String middle = JOptionPane.showInputDialog("What is your middle name");
String last = JOptionPane.showInputDialog("What is your last name");
JOptionPane.showMessageDialog(null, "Hello " + first + " " + middle + " " + last)
}
}
