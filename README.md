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
        // TODO code application logic here
    }
    
}
