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
import javax.swing.JFrame;
import javax.swing.*;

public class PersonaAssignment {

   
    public static void main(String[] args) {
        JFrame myframe=new JFrame("Login Page");
        JPanel mypanel=new JPanel();
        JLabel namelable=new JLabel("User Name: ");
        JLabel passwordlabel=new Jlabel("Password:")
        JTextField username=new JTextField();
        JButton Login=new JButton("login");
        JButton Exit=new JButton("Exit");
        mypanel.add(username);
        mypanel.add(Login);
        mypanel.add(Exit);
        myframe.add(mypanel);
        myframe.setSize(500,400);
        myframe.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        myframe.setVisible(true);
        // TODO code application logic here
    }
    
}


         
