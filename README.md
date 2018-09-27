# front-office-personal-assignment-
Using GUI,create login,logout,charts

//this is a frame for the login page
public class PersonaAssignment {
     public static void main(String[] args) {
        JFrame myframe=new JFrame("Login Page");
        myframe.setSize(500,400);
        myframe.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        myframe.setVisible(true);}
        
       
      //this is the panels for the login page
      package personal.assignment;
package personal.assignment;
import java.awt.FlowLayout;
import javax.swing.JFrame;
import javax.swing.*;
s
public class PersonaAssignment {

    
    public static void main(String[] args) {
        JFrame myframe=new JFrame("Login Page");
        //to help with the arrangement of the panels
        JPanel mypanel=new JPanel(new FlowLayout());
        JLabel namelabel=new JLabel("User Name: ");
        JLabel passwordlabel=new JLabel("Password:");
        //this is where the names and passwords will be written
        JTextField username=new JTextField(10);
        JTextField password=new JTextField(15);
        JButton Login=new JButton("login");
        JButton Exit=new JButton("Exit");
        //we are adding panels into the frame
        mypanel.add(namelabel);
        mypanel.add(username);
        mypanel.add(passwordlabel);
        mypanel.add(password);
        mypanel.add(Login);
        mypanel.add(Exit);
        myframe.add(mypanel);
        myframe.setSize(500,400);
        myframe.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        myframe.setVisible(true);
        //to interact with user
        String Username;
    String Password;

    Password = "123";
    Username = "wisdom";

    Scanner input1 = new Scanner(System.in);
    System.out.println("Enter Username : ");
       Scanner input2 = new Scanner(System.in);
    System.out.println("Enter Password : ");
    if (username.equals(Username) && password.equals(Password)) {

        System.out.println("Access Granted! Welcome!");
    }

    else if (username.equals(Username)) {
        System.out.println("Invalid Password!");
    } else if (password.equals(Password)) {
        System.out.println("Invalid Username!");
    } else {
        System.out.println("Invalid Username & Password!");
    }


        // TODO code application logic here
    
    
}
